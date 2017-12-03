### 安装方法
    wget --no-check-certificate https://raw.githubusercontent.com/Yuanjiali/shadowsocks-/master/ShadowsocksR/shadowsocksR.sh
    chmod +x shadowsocksR.sh
    ./shadowsocksR.sh 2>&1 | tee shadowsocksR.log
### 客户端
https://github.com/shadowsocksr-backup/shadowsocksr-csharp/releases
#### 配置文件路径
/etc/shadowsocks.json
#### 日志文件路径
/var/log/shadowsocks.log
#### 代码安装目录
/usr/local/shadowsocks
### 多用户配置
    {
    "server":"0.0.0.0",
    "server_ipv6": "[::]",
    "local_address":"127.0.0.1",
    "local_port":1080,
    "port_password":{
        "8989":"password1",
        "8990":"password2",
        "8991":"password3"
    },
    "timeout":300,
    "method":"aes-256-cfb",
    "protocol": "origin",
    "protocol_param": "",
    "obfs": "plain",
    "obfs_param": "",
    "redirect": "",
    "dns_ipv6": false,
    "fast_open": false,
    "workers": 1
    }
