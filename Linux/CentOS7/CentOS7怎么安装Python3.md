    系统环境：CentOS7
    代码运行环境：bash shell
    最后确认日期：2019年7月9日

### 安装最新版本的EPEL

```shell
sudo yum install epel-release
```

### 用yum安装python3

```shell
sudo yum install python36
```

### 附加安装pip

```shell
curl -O https://bootstrap.pypa.io/get-pip.py
sudo /usr/bin/python3.6 get-pip.py
```