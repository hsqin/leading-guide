# 3.HTML

* HTML规范

* 引入资源使用相对路径，不要指定资源所带的具体协议 ( <code>http:,https:</code> ) ，除非这两者协议都不可用

* 使用双引号来标识html的属性 
> eg：
~~~
<a class="a-recommend">推荐使用双引号</a>
<a class='a-recommend'>不推荐不推荐使用单引号</a>
~~~

* img 

* logo尺寸

#### 语义化标签
* 尽量少用无语义的div和span标签; 多使用语义化标签
* [新的语义和结构元素,参考菜鸟教程](http://www.runoob.com/html/html5-new-element.html)


常用标签| 说明|备注
:--:|:--:|
header|文档的头部区域|下图有示例
nav| 导航链接的部分|
article| 页面独立的内容区域|
setion|文档中的节（section、区段）|
aside|定义页面的侧边栏内容|
footer|定义 section 或 document 的页脚|
mark|给文件加特殊标记|下图有示例
dialog|定义对话框，比如提示框|
datalist|定义选项列表。input 元素配合使用|是新表单元素,有示例
details|描述文档或文档某个部分的细节| 下图有示例
summary| summary标签包含 details 元素的标题| 下图有示例

> 语义化标签结构
![语义化](https://image.tracup.com/snapshot_1532067445236.png)

---

> mark标签
![mark.png](https://upload-images.jianshu.io/upload_images/6781040-2f65dc88289335c3.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

---

> details summary
![details-summary.png](https://upload-images.jianshu.io/upload_images/6781040-c6a26a4ff6d55b5d.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

---

> datalist
![datalist.png](https://upload-images.jianshu.io/upload_images/6781040-6851a5aa9378500f.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
