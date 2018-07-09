# 使用 Ansible 安装 Hadoop

存储节点将设置磁盘。

编辑[production.ini](./production.ini)以及[all.yaml](./group_vars/all.yaml)文件。

## 测试连接状态

```bash
make test
```

## 安装

```bash
make install
```

## 检测

访问 http://storage-1.cluster.local:9870/dfshealth.html#tab-overview