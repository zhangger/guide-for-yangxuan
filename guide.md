# 翻译说明文档


## 1\. 翻译前须知

- 首先阅读协作规范，里面介绍了 markdown 的使用语法以及 github 的使用方法和极客学院的翻译风格。

[协作规范](https://github.com/jikexueyuanwiki/guide/blob/master/README.md)

## 2\. 本次项目规范

- 每个文章翻译后需要写上出处 时间和原作者 然后再写一小段介绍性的话 类似序言之类 写在文章的最前面 [序言由自己书写，大约50到100字]

#### **每篇文章统一格式**：

从上到下标题——》图片——》(文章翻译、发表时间、原文作者（作者如果有链接的话需要提供链接))—》关于本文—》文章内容(正文）—>版权声明 

可以复制该模板：

```
# 标题

![01](images/图片名)

文章翻译 ：[你的姓名](你的微博账号或者博客或者github账号)

发表时间：2015 年 x 月 x 日  //此处数字和中文之间要空格

原文作者：XXXXXX

## 关于本文

XXXXXXXXXXXXXXXXXXX大约50到100字

## 文章内容
XXXXXXXXXXXXXX......

> 版权声明：   
> 本译文仅用于学习和交流目的。非商业转载请注明译者、出处，并保留文章在极客学院的完整链接   
> 商业合作请联系 wiki@jikexueyuan.com   
> 原文地址：[XXXXXXX](XXXXXXX)
```

效果：

# 标题

![01](images/图片名)

文章翻译 ：[你的姓名](你的微博账号或者博客或者github账号)

发表时间：2015 年 x 月 x 日  //此处数字和中文之间要空格

原文作者：XXXXXX

## 关于本文

XXXXXXXXXXXXXXXXXXX大约50到100字

## 文章内容
XXXXXXXXXXXXXX......

> 版权声明：   
> 本译文仅用于学习和交流目的。非商业转载请注明译者、出处，并保留文章在极客学院的完整链接   
> 商业合作请联系 wiki@jikexueyuan.com   
> 原文地址：[XXXXXXX](XXXXXXX)

#### 实例：请参见周倍同同学翻译的格式。

[使用 ionic 将数据保存到本地存储中](https://github.com/yangxuanxc/wiki-journal-201507-1/blob/master/persisting-data-local-storage.md)

- 文章中的图片

如果文章中有图片，那么将文章中的图片保存在本地 

命名格式为 md文件名 + 图片名（序号，第几张图就为几） + 后缀名 如 md 文件名为 **persisting-data-local-storage.md**

那么图片名就为 persisting-data-local-storage-01.jpg（或者png，后缀名由图片决定）

将改好的图片通过QQ传递给小组长杨旋 QQ:517225344 ,由小组长统一上传至images文件夹

在内容中引用图片统一采用相对路径，那么在内容中引用的路径请写 ： images/图片名

比如 ：

```
![01](images/persisting-data-local-storage-01.jpg) 
```
#### 如果翻译的文章中没有图片，那么大家自己在网上找一个相符的图片放在文章标题下，按照上述格式，最好用 google 或者 bing 图片搜索。


- 如果文章中视频 

进行截图，然后当做图片处理。然后在图片下面附上视频的地址

```
![01](images/图片名)

[视频地址](xxxxxxxx)
```
- 文章中的代码

代码块 ```后面要跟上语言类型 

github可以对相关语言解析高亮 
比如javascript 就写成 

\`\`\`javascript  
function show5(){if(!document.layers&&!document.all)  
return  
var Digital=new Date()  
var hours=Digital.getHours()  
var minutes=Digital.getMinutes()  
var seconds=Digital.getSeconds()  
var dn="AM"  
if(hours>12){dn="PM"  
hours=hours-12  
}if(hours==0)  
hours=12  
if(minutes<=9)  
minutes="0"+minutes  
if(seconds<=9)  
seconds="0"+seconds  
//change font size here to your desire  
myclock="<font size='5' face='Arial'><b><font size='1'>Current Time:</font></br>"+hours+":"+minutes+":"  
+seconds+" "+dn+"</b></font>"  
if(document.layers){document.layers.liveclock.document.write(myclock)  
document.layers.liveclock.document.close()  
}else if(document.all)  
liveclock.innerHTML=myclock  
setTimeout("show5()",1000)  
}
\`\`\`

效果 ：

```javascript
function show5(){if(!document.layers&&!document.all)
return
var Digital=new Date()
var hours=Digital.getHours()
var minutes=Digital.getMinutes()
var seconds=Digital.getSeconds()
var dn="AM"
if(hours>12){dn="PM"
hours=hours-12
}if(hours==0)
hours=12
if(minutes<=9)
minutes="0"+minutes
if(seconds<=9)
seconds="0"+seconds
//change font size here to your desire
myclock="<font size='5' face='Arial'><b><font size='1'>Current Time:</font></br>"+hours+":"+minutes+":"
+seconds+" "+dn+"</b></font>"
if(document.layers){document.layers.liveclock.document.write(myclock)
document.layers.liveclock.document.close()
}else if(document.all)
liveclock.innerHTML=myclock
setTimeout("show5()",1000)
}
```

## 3\. 任务提交时间

正常情况下，提交时间从分配任务开始 ，你完成的时间为 你的总单词数/1000（天），比如在今天给你分配了3000词，那么你的提交时间最晚就在三天后，希望大家积极提交。提交后如果有新的任务，会优先进行分配。

## 4\. 翻墙问题

因为有些文章需要翻墙才能查看，所以遇到需要需要翻墙的时候请参考该教程

[翻墙教程](http://blog.ss-link.com/archives/23)

## 5\. 投稿文章

大家如果看到有比较好的文章也可以积极告诉组长，组长交由经理确认后就可以进行翻译

如下几个条件：

1\. 国外最新IT技术类文章(英文，发表时间1个月内)

2\. 选题内容要求在目前互联网最热领域（分类见 [TOC](https://github.com/yangxuanxc/wiki-journal-201507-1/blob/master/TOC.md)）

3\. 字数不多于1500字(可用工具，比如http://www.wordcounter.net/）

4\. 最好有配图，内容要让开发人员眼前一亮

## 6\. 提交文章

请在 TOC 页面提交，提交后请 pull request 然后再顺便告知组长。
