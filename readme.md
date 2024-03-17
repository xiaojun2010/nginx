官网：
https://segmentfault.com/a/1190000039055393?utm_source=tag-newest

https://docsify.js.org/#/

废话我就不多说了，直接安装docsify-cli :

npm i docsify-cli -g
然后我们建立一个测试文件夹叫note，命令行进入这个文件夹：

cd note
docsify init ./docs
就成功了！！！看到它叫你执行命令,本地启动一下：

docsify serve ./docs


说实在话，挺丑的，那就美化一下：
先加一个封面，需要在`index.html中，把下面的属性设置为true

coverpage: true
然后新建一个文件_coverpage.md:

# Mybatis摸索之路


> 这是我自己的笔记啊啊啊啊

[CSDN](https://blog.csdn.net/Aphysia)
[滚动鼠标](#introduction)
