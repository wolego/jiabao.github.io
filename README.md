# wolego.github.io
在搭建GitHub个人主页之前，我希望你能熟悉下面几个知识点：

git操作命令

github

HTML、CSS、JS基本知识

MarkDown基础语法

第一步：新建github项目 
在github上新建一个项目，命名为xxx.github.com，比如我的命名为funga.github.com.

第二步：添加index.html 
将项目clone到本地，根目录下添加index.html，也就是主页的首页。然后push到远程仓库。

第三步：访问xxx.github.com 
一般不会立即生效，等待一段时间之后，浏览器访问xxx.github.com（xxx.github.io也可以），比如我的主页地址就是funga.github.io。出现的主页就是index.html的内容。

第四步：绑定自己的域名 
比如我注册了funga.cn的域名，现在想通过funga.cn来访问我的github主页，首先，我们在项目中根目录添加一个文件CNAME，内容为funga.cn，将该文件push到远程仓库。然后funga.cn设置解析，CNAME到funga.github.io。然后访问funga.cn即可。

第五步：漂亮的网站 
GitHub主页我们使用的是相对路径，我们可以把需要的CSS、JS、图片资源等直接放在工程下，直接在html页面里面引用即可，这样，就可以渲染出漂亮的页面。以我的主页为例，index.html其实是一个首页目录。使用markdown写好文章，推送到仓库。都放在根目录下的data文件夹下面，通过funga.cn/data/xxx.html就可以进行访问了。

第六步：评论、分享、统计和广告 
如果你和我一样是博客网站，推荐你也可以使用搜狐畅言评论系统，还可以有广告，只需将生成的JS代码引入到博客网页即可。百度分享插件的JS代码引入博客网页，即可实现分享功能。统计使用的站长之家的服务，将统计JS代码引入即可。

至此，你应该能够实现搭建个人github主页了，如果遇到什么问题欢迎留言讨论
