# Shadowsocks
## 客户端
[Shadowsocks Windows客户端](https://github.com/shadowsocks/shadowsocks-windows/releases)  
[ShadowsocksR Windows客户端](https://github.com/shadowsocksrr/shadowsocksr-csharp/releases)
## 服务端
### 1.Shadowsocks-Python，ShadowsocksR，Shadowsocks-Go，Shadowsocks-libev版（四选一）。
### 2.Shadowsocks-Python 和 ShadowsocksR 安装后不可同时启动。
### 安装方法（使用root用户登录）：
    wget --no-check-certificate -O shadowsocks-all.sh https://raw.githubusercontent.com/Yuanjiali/Shadowsocks/master/shadowsocks-all.sh
    chmod +x shadowsocks-all.sh
    ./shadowsocks-all.sh 2>&1 | tee shadowsocks-all.log
### 卸载方法：
    ./shadowsocks-all.sh uninstall
### 启动脚本
启动脚本后面的参数含义，从上至下依次为：启动，停止，重启，查看状态。

#### Shadowsocks-Python 版：
    /etc/init.d/shadowsocks-python start
    /etc/init.d/shadowsocks-python stop
    /etc/init.d/shadowsocks-python restar
    /etc/init.d/shadowsocks-python status

#### ShadowsocksR 版：
    /etc/init.d/shadowsocks-r start
    /etc/init.d/shadowsocks-r stop
    /etc/init.d/shadowsocks-r restart
    /etc/init.d/shadowsocks-r status

#### Shadowsocks-Go 版：
    /etc/init.d/shadowsocks-go start
    /etc/init.d/shadowsocks-go stop
    /etc/init.d/shadowsocks-go restart
    /etc/init.d/shadowsocks-go status

#### Shadowsocks-libev 版：
    /etc/init.d/shadowsocks-libev start
    /etc/init.d/shadowsocks-libev stop
    /etc/init.d/shadowsocks-libev restart
    /etc/init.d/shadowsocks-libev status

### 各版本默认配置文件
#### Shadowsocks-Python 版：
/etc/shadowsocks-python/config.json

#### ShadowsocksR 版：
/etc/shadowsocks-r/config.json

#### Shadowsocks-Go 版：
/etc/shadowsocks-go/config.json

#### Shadowsocks-libev 版：
/etc/shadowsocks-libev/config.json


来自网络
