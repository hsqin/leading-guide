# 5.JavaScript

#### 变量
* 每个var只能声明一个变量
	* 疑问: ***我记得性能里面说,最好一个var声明多个,难道我记错了?***

```
// good
var hangModules = [];
var missModules = [];
var visited = {};

// bad
var hangModules = [],
    missModules = [],
    visited = {};
```

#### 条件
* **建议使用 `===`**
* 仅当**判断 null 或 undefined 时 , 使用 `==`**


#### 注释
* 单行注释
	* 必须独占一行
	* `// `后跟一个空格
* 多行注释 
	* 避免使用` /*...*/`
	* 有多行时,使用多个单行注释
* 文档化注释
	* 强制使用` /**...*/` , 注释前必须空一行
	* 适用范围:
		* 文件
		* namespace
		* 类/函数/方法/事件
		* 全局变量/常量
		* AMD模块

```
/**
 * 函数描述
 *
 * @param {string} p1 参数1的说明
 * @param {string} p2 参数2的说明，比较长
 *     那就换行了.
 * @param {number=} p3 参数3的说明（可选）
 * @return {Object} 返回值描述
 */
 ```
 ---
 ```
 /**
 * 文件注释 
 * @file Describe the file
 * @author:hsqin
 */
```
***
```
/**
 * 常量说明
 *
 * @const
 * @type {string}
 */
 var REQUEST_URL = 'myurl.do';
 ```


#### 表达式
* 使用三元表达式来代替简单的if-else
> eg:
```
if(a){ b='c'}else{ b='d'}
简写: b = a?'c':'d'
```

* 使用 `&&`, `||` 代替简单的if
> eg:
```
if(b){ a = b}else{ a=3}
简写: a = b || 3
```

* 使用简短的判断
> eg:
```
if(name!=0 && name!=null && name!=undefined){ something}
简写: if(name){ something }
```

#### 循环
* 循环体中不要包含函数表达式,要先将表达式写在循环外面. 否则循环体中会生成多个函函数对象
* 对循环内使用的不变值,在循环外先用变量缓存
* 不要在array上使用for-in循环 for-in循环只适用于object/map/hash

*






