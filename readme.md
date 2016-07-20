#MongodbStudy#

##在32位win7安装mongodb##
1. 下载安装包安装
2. 安装目录一般是:C:\Program Files\MongoDB\Server\3.2\bin
3. 在安装目录下：mongod --dbpath D:\Yanjie\SourceCode\NodejsStudy\db  --logpath D:\Yanjie\SourceCode\NodejsStudy\log\MongoDB.log --install --serviceName "MongoDB" --journal --storageEngine=mmapv1
4. 启动服务:net start MongoDB
5. 进入安装目录，打开mongo.exe就可以在控制台输入命令
6. 命令熟悉请参照 http://www.cnblogs.com/liyonghui/p/mongodb.html


##在树莓派ubuntu16.04上安装mongodb##
1. 直接使用sudo  apt-get  install  mongodb




##使用总结##
1. javascript区分大小写，mongo.exe支持javacsript语法
2. ）{比{单独开一行的好处是在命令行中知道代码没有敲完，会继续敲
3. 典型的键/值类型应用，类json
4. 分布式数据库  ObjectId




##FAQ##
1.[thread1]SyntaxError:missing;before statement@(shell):1:4



##使用场景##
1. python使用mongodb
2. PHP使用mongodb



