# gzgz-elasticsearch
分布式搜索引擎
Lucense 是一套信息检索工具包，jar包 ，不包含搜索引擎系统，包含索引结构，读写索引工具，排序、搜索规则等  

ElasticSearch是Lucense 做了一些封装和增强

## elasticsearch 安装
1. 准备工作
- 下载 [elasticsearch-7.10.0](https://www.newbe.pro/Mirrors/Mirrors-Elasticsearch/)
- 下载 [可视化 elasticsearch-head-master](https://github.com/mobz/elasticsearch-head)
- 下载 [分词器 elasticsearch-analysis-ik-7.10.0](https://github.com/medcl/elasticsearch-analysis-ik/releases)
2. 安装
elasticsearch 安装解压即可
elasticsearch-head-master 安装：
- 谷歌插件安装  
~~~
安装插件： google ---》更多工具----》扩展程序  
将解压的elasticsearch-head.crx文件拖进来。  
提示程序包无效："CRX_HEADER_INVALID"  
将elasticsearch-head.crx更名为elasticsearch-head.rar 再解压；  
进入elasticsearch-head文件夹将_metadata文件夹重命名为metadata  
打开Google的扩展程序，点击加载已解压的扩展程序，选择解压elasticsearch-head文件夹即可添加插件成功
~~~
3.注意  
跨域及所有人访问配置  
http.cors.enabled: true  
http.cors.allow-origin: "*"
 
- Docker安装  
镜像拉取（待更新）



