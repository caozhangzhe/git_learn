该文件是线上远程仓库的读我文件 初始化时创立的
git中报unable to auto-detect email address 错误的解决办法
找到工程目录的.git文件夹，打开之后找到config文件，在最后边加上一句话
[user]
email=your email
name=your name
这是在dev分支下新加的内容