2016/10/26
目前的自动部署是初级版本，主要还是为了减少环境搭建的时间，但是有些东西的安装需要进行交互或者复杂判断，包括salt可以利用jinja模板动态生成文件
，这些东西在目前的版本中都没有体现。由于我目前任务比较多，只能先做的这个程度，如果以后需要的话，可以考虑。

目前完成的模板有：
--hadoop
--hbase
--jdk
--kafka
--mahout
--maven
--mysql
--scala
--spark
--storm
--zookeeper

2016/10/31
根据领导要求删除HA配置

