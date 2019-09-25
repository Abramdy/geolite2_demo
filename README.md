# geolite2_demo
GeoLite2的Java实现，Jar包部署可用

# 一、需求

通过输入一个IP地址，解析并获取信息，比如国家、国家代码、省份、省份代码、城市、邮政编码、经纬度等等信息

例如，解析ip（128.101.101.101）的信息如下：

![img](https://img-blog.csdnimg.cn/20190925094245809.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0Nyb3duUA==,size_16,color_FFFFFF,t_70)



# 二、实现形式

**使用在线第三方提供的api：**

- ip-api.com
- ip.taotao.com
- 百度地图api
- 新浪 iplookup

**使用离线查询方式：**

- 纯真库
- GeoLite2
- 埃文科技

**数据丰富度对比：**![img](https://img-blog.csdnimg.cn/20190925095729296.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0Nyb3duUA==,size_16,color_FFFFFF,t_70)![点击并拖拽以移动](data:image/gif;base64,R0lGODlhAQABAPABAP///wAAACH5BAEKAAAALAAAAAABAAEAAAICRAEAOw==)

**查询准确率比较：**![img](https://img-blog.csdnimg.cn/20190925095852922.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0Nyb3duUA==,size_16,color_FFFFFF,t_70)![点击并拖拽以移动](data:image/gif;base64,R0lGODlhAQABAPABAP///wAAACH5BAEKAAAALAAAAAABAAEAAAICRAEAOw==)
**查询速度比较：**
![img](https://img-blog.csdnimg.cn/20190925095958344.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0Nyb3duUA==,size_16,color_FFFFFF,t_70)![点击并拖拽以移动](data:image/gif;base64,R0lGODlhAQABAPABAP///wAAACH5BAEKAAAALAAAAAABAAEAAAICRAEAOw==)​



**总结：       需要速度用离线，需要准确率用在线，需要数据丰富性GeoLite2、埃文科技，需要免费用GeoLite2（埃文科技虽说国内头头，奈何收费）**



# 三、具体代码

**请查看代码，已写好详细注释！**

