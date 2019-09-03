# 如何在github上传本地项目代码（新手使用）
首先你要在github上申请一个账号
网址：https://github.com/

然后你要下载一个git工具
网址：https://gitforwindows.org/

进入官网直接下载就行，下载完成后进入github首页，点击新项目new repository，如下图所示：
![Image text](https://github.com/15234477664/github-upload/blob/master/img/1.png)

然后进入如下页面，主要填写红色圈起来的几个部分，如下图：
![Image text](https://github.com/15234477664/github-upload/blob/master/img/2.png)

最后点击Create repository,生成如下页面：
![Image text](https://github.com/15234477664/github-upload/blob/master/img/3.png)

按红色圈圈画的步骤，先点击Clone or download, 然后复制第二步的地址，待会上传项目有用.
接下来就是在本地操作了，在此之前你一定要把git安装好，然后找到你要上传的文件夹项目，右键点击文件夹（注意：不能选单个文件或者压缩包）在选项里会有

Git Gui Here,Git Bash Here出现，选择Git Bash Here，会出现下图：
![Image text](https://github.com/15234477664/github-upload/blob/master/img/4.png)

然后把你之前在clone or download里复制的地址按下图粘贴，或者手动输入：
记住地址前面要加git clone.
![Image text](https://github.com/15234477664/github-upload/blob/master/img/5.png)


然后你的项目文件里就会增加一个你在github上创建的项目名称，如下图：红色圈圈画起来的文件夹meituan,就是新增的文件夹，然后把你在这个目录要上传的文件复制到meituan文件夹里。

![Image text](https://github.com/15234477664/github-upload/blob/master/img/6.png)

然后在git命令行切换目录在meituan文件里，输入命令cd meituan回车，如下图所示：
![Image text](https://github.com/15234477664/github-upload/blob/master/img/7.png)
然后输入命令" git add . "(注意" . "不能省略，此操作是把meituan文件夹下面新的文件或修改过的文件添加进来，如果有的文件之前已经添加了，它会自动省略)
![Image text](https://github.com/15234477664/github-upload/blob/master/img/8.png)
然后输入git commit  -m  "提交信息" （提交的信息是你的项目说明）（注： git commit 后面加 -m 表示可以直接输入提交说明，如果不加 -m ，直接输入git commit，就会弹出一个类似于 vim 的界面，让你输入提交说明。)
有些刚开使用的用户输入提交时会出现错误，如下图：
![Image text](https://github.com/15234477664/github-upload/blob/master/img/9.png)

这时你要先全局配置好在git上的用户名和邮箱，如下图所示输入命令：
![Image text](https://github.com/15234477664/github-upload/blob/master/img/10.png)

然后再输入提交的命令，如图：
![Image text](https://github.com/15234477664/github-upload/blob/master/img/11.png)

这样就快上传成功了，最后输入命令git push -u origin master（此操作目的是把本地仓库push到github上面，此步骤需要你输入登录github上的帐号和密码）
![Image text](https://github.com/15234477664/github-upload/blob/master/img/12.png)

然后进入里的github页面，刷新下页面就会显示你的项目，如下图所示：
![Image text](https://github.com/15234477664/github-upload/blob/master/img/13.png)

这样你的项目就成功上传了。
