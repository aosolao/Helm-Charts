# Helm-Charts
该项目记录了一些常用服务的自制Chart

目前已包含：
- [rocketmq-operator](./rocketmq-operator)

## 使用方法
1. 将chart复制到本地

2. 根据环境与需求修改`values.yaml`中的配置

3. 使用Helm命令安装服务
    ```bash
    cd chart路径
    helm install [服务名称] ./
    ```
4. 卸载服务
    ```bash
    cd chart路径
    helm uninstall [服务名称]
    ```


## 如何安装 Helm
请参考 Helm 官网：https://helm.sh/