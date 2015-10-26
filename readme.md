## 1.  实验背景
PAAS平台和容器技术的应用将会对系统集成的方法带来显著变化，本实验主要考察被测试人员能否利用现有技能快速适应PAAS平台的集成及在PAAS平台之上应用的部署
## 2.  平台选择   
1. cloudfoundry
2. openshift
3. kubernetes
4. cloudify

## 3.  实验内容
1. 完成平台搭建  
要求平台具备PAAS平台常见核心功能，包括应用部署、日志管理、健康监控、运行时集成、服务集成等
2. 部署应用  
完成一个php应用集群+redis集群部署；  
php代码通过代码仓库发布到平台中；通过平台能力部署到php运行时中；  
php集群具备负载均衡能力；负载均衡能力要求通过平台方式实现，非手工部署  
redis集群具备主从和sharding模式；通过平台方式实现，非手工部署    
两集群需通过服务发现方式衔接；对服务发现本身的实现方式不做要求  

## 4. 其他说明
1. 实验完成后需实验者通过本机演示实验的完整过程，实验者需要从实验部署架构、实验开发经历、实验实际操作、实验可改进方面等内容进行介绍
2. 实验周期为7天，不要求全部完成
3. 其他未尽事宜可随时联系