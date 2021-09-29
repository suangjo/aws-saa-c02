- Region 区域
    * 指AWS资源所在的实际地理位置，一般云服务的区域都是由可用区（Availability Zone）所构成
    * 主要分布在世界各地的大城市
    * 用户可以在每个区域分别构建云网络
- Availability Zone 可用区
    * 指IDC(Internet Data Center)互联网数据中心
    * 一般每个区域存在3~4个可用区
    * 一个区域中的某个可用区出现故障时，请求会被连接到其他可用区并执行
    * 在网络中，一个子网就只能存在于一个可用区中，一个可用区中可存在多个子网
- On-premise 本地部署的
    * 不使用云服务，使用的是传统型的基础设施，保有自己的数据中心或者计算中心
    * 在本地的构建的基础设施
- Edge Location 站点
    * Cloudfront服务中CDN(Content Delivery Network)内容分发网络所用到的缓存服务器
    * 分布在世界各地，站点之间数据共享
- Elasticity 弹性
    * 指的是在请求量突然变化时，增加或者减少（Scale out）某项服务的使用量的能力，类似于AWS Autoscaling功能。
- Scalability 扩展性
    * 是一个长远的概念，指的是在构架观念下，保有能充分扩展资源的可能性
- Severless 无服务器
    * 指减少用户直接进行服务器的部署，着重于产品本身的开发
- Pay as you go 按需付费
    * 经典的云计算价格体系，大多AWS服务采用的收费方式
