# 4.CSS

#### css格式规范
* 个人习惯使用tab (4个空格键) 进行缩进
* 不建议使用id来写样式
* 避免使用@import引入其他css
* 选择器嵌套层级,尽量少于3级

* css代码本身都是全局的,所以应当采用css模块化思想,榆树css的规则,尽量减少对全局的污染
* 避免使用document.write生成标签


* class的属性尽量使用简写或缩写 
* 0单位和0前缀都省略
* 属性名的冒号后面,最好空格

> eg:
 ```
 font: 100%/1.6 palatino, georgia, serif;
 opacity: .5;
 font-size: .8rem;
 margin: 0;
 margin-top: 0; /* 不推荐 */
 margin-bottom: 0; /* 不推荐 */
 ```

* 颜色属性尽量使用3个字符的16进制  

> eg:
```
color: #f90;   
color: #ff9900;  /*不推荐*/
```

* 最佳实践的属性显示顺序如下:

> 先 结构性属性：
```
display
position, left, top, right etc.
overflow, float, clear etc.
margin, padding
```
> 再 表现性属性:
```
background, border etc.
font, text
```