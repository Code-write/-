# -
#man Manual translation chinese
#
首先安装这个是google出的translate-shell 命令行翻译
按照要求安装

https://github.com/soimort/translate-shell

之后在命令行里运行

man trans | trans -no-auto -b -o output.txt :zh

这里是把trans在man手册里的内容通过管道传给google-trans进行在线翻译之后保存在当前的目录下

如果运行后等待很长时间是正常的这家伙一个词一格词翻译然后前后关联优化QAQ

还是非常好用的虽然翻译会出现误差但比其他方法快些
收起来重装系统用的上
