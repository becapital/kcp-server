## KCP-Server

## 感谢[kcptun](https://github.com/xtaci/kcptun)提供这么优秀的软件

## 安装平台：CentOS、Debian、Ubuntu。

### 安装

```Bash
wget --no-check-certificate https://raw.githubusercontent.com/becapital/kcp-server/master/install-kcp-server.sh -O ./install-kcp-server.sh
chmod 500 ./install-kcp-server.sh
./install-kcp-server.sh install
```
## kcpserver配置文件修改： vi /usr/local/kcp-server/server-kcptun.json
修改后VPS需要reboot

### 服务器管理
```Bash
    Usage: /etc/init.d/kcp-server {start|stop|restart|status}
```
/etc/init.d/kcp-server restart
 
/etc/init.d/kcp-server status

./install-kcp-server.sh uninstall

./install-kcp-server.sh update
