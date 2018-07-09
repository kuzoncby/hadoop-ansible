# Install Hadoop by Ansible

You need at least 3 CentOS to run this playbook.

Edit [production.ini](./production.ini) and [all.yaml](./group_vars/all.yaml)

## Test connection

```bash
make test
```

## Install Hadoop 3

```bash
make install
```

## Access web console

Access http://storage-1.cluster.local:9870/dfshealth.html#tab-overview

## License

MIT