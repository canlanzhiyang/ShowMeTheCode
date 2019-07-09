```shell
系统环境：CentOS7
代码运行环境：bash shell
```

## 安装最新版本的EPEL

`sudo yum install epel-release`

## 用yum安装python3

### 当前可用

`sudo yum install python36`

### 模板
匹配特定版本号

`sudo yum install python3[1-6]`

## 附加安装pip

```shell
curl -O https://bootstrap.pypa.io/get-pip.py
sudo /usr/bin/python3.4 get-pip.py
```