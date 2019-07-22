# 添加本仓库分享自己工作和学习中使用和整理的ansible playbook
- CentOS7常规初始化
- kubeadm安装

## kubernetes相关
### 前置要求
- CentOS装完操作系统（Mini版)
- 配置好网络
- 设置好root密码
- 创建普通账号
- 给普通账号sudo权限
- 给普通账号添加ssh认证公钥

### 基于kubeadm的kubernetes集群安装
- 入口：kubeadm.yml
- 在hosts中配置好master和worker的ip地址列表

### 基于minikube的kubernetes单结点集群安装
- 入口：minikube.yml
