# Huawei-multi(`开源项目`）
《Huawei构建微服务架构》微`服务`化`开发平台`，具有统一授权、认证后台管理系统，其中包含具备用户管理、资源权限管理、网关API管理等多个模块，支持多业务系统并行开发，可以作为后端服务的开发脚手架。代码简洁，架构清晰，适合学习和直接项目中使用。核心技术采用`Spring Boot2`以及`Spring Cloud (Finchley.M8)`相关核心组件，前端采用`vue-element-admin`组件。

## Huawei 学习教程
	##《Huawei构建微服务架构》系列 - version
	## Huawei微服务实战 : Eureka + Zuul + Feign/Ribbon + Hystrix Turbine + Spring Config + sleuth + zipkin
	
	 Huawei-multi

		欢迎大家fork me，项目中用到的技术有：
		
		springboot 快速搭建项目
		
		eureka 服务注册（发现）中心
		
		consul 服务注册（发现）中心，consul单独开consul分支，默认eureka
		
		springcloud config/Apollo 配置中心，apollo会开单独分支，目前未做
		
		ribbon rest请求客户端负载平衡器，springboot自带
		
		feign rest请求声明性REST客户端，基于ribbon
		
		Hystrix 断路器
		
		turbine 聚合多个实例Hystrix指标流
		
		zuul 路由器和过滤器
		
		Sleuth 分布式跟踪
		
		Zipkin 结合Sleuth实现链路跟踪
		
		项目启动顺序：
		
		eureka/consul -> config -> 剩下其他的服务``


