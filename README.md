# go-dict
使用go语言开发了服务端+客户端+sqlite3导入工具，以完成客户端查词后，服务端返回json格式的查词结果。<br>
包括三个项目，如下所示：

## go-dict-client
项目功能：查词客户端<br>
项目地址：https://github.com/Carbs0126/go-dict-client

## go-dict-server
项目功能：服务端从sqlite3数据库中返回数据<br>
项目地址：https://github.com/Carbs0126/go-dict-server<br>
备注：两个数据库，一个是从A到K，另一个是从L到Z

## go-dict-server-prepare
项目功能：从csv格式的文件中读取单词以及解释，并将数据插入到sqlite3指定的数据库中<br>
项目地址：https://github.com/Carbs0126/go-dict-server-prepare<br>
备注：也可以不使用这个项目，因为 go-dict-server 项目已经有了准备好数据的数据库文件

# 感谢
https://github.com/skywind3000/ECDICT
