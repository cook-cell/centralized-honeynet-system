## 📁 项目描述

基于K3s云原生技术构建的SaaS化欺骗防御平台。
通过在用户网络中分布式部署轻量级探针来创建诱饵(影子服务)，将攻击流量透明转发到后端由平台集中编排的高交互蜜罐中。


## ✔️ 环境准备

- **虚拟环境**: VMware Workstation 16.1.2 Pro
- **系统要求**: CentOS-7-x86_64-DVD-1810.iso
- **建议配置：**: 内存4G、处理器4、磁盘空间20G


## ✔️ 快速部署

```shell
git clone https://github.com/cook-cell/centralized-honeynet-system.git
cd Ehoney && chmod +x quick-start.sh && ./quick-start.sh
# 选择ens33虚拟网卡的ip地址作为服务器地址

# 此安装过程会比较耗时、耐心等待

**all the services are ready and happy to use!!!**
# 代表安装成功。
```

访问 `http://IP:8082/decept-defense` 进入系统登录页  (IP=ens33)

默认账户
       <font color=Blue>用户名: `admin`</font>
       <font color=Blue>密码: `123456`</font>
