# maxViewRCE
maxView系统dynamiccontent.properties.xhtml接口远程代码执行
漏洞描述：
由于用户可输入系统命令，且web应用对用户输入的命令没有限制，导致用户可以随意输入系统命令执行，造成极大危害

![image](https://github.com/user-attachments/assets/46d70d4e-96fb-4134-a726-575ee8a4bae4)

项目介绍:

该工具用于检测maxView系统dynamiccontent.properties.xhtml接口是否存在rce漏洞

工具使用：

python maxView系统.py -u http://www.xxx.com  即可进行单个url漏洞检测

python maxView系统.py -u targetUrl.txt 即可对选中文档中的网址进行批量检测,结果会存储在同一目录下的rce.txt文件中
