使用方法：

使用root用户登录，运行以下命令：

wget --no-check-certificate -O shadowsocks-go.sh https://raw.githubusercontent.com/teddysun/shadowsocks_install/master/shadowsocks-go.sh

chmod +x shadowsocks-go.sh

./shadowsocks-go.sh 2>&1 | tee shadowsocks-go.log



卸载方法：

使用 root 用户登录，运行以下命令：

./shadowsocks-go.sh uninstall

安装完成后即已后台启动 Shadowsocks-go ，运行：

/etc/init.d/shadowsocks status

可以查看 Shadowsocks-go 进程是否已经启动。

本脚本安装完成后，已将 shadowsocks-go 加入开机自启动。

使用命令：

启动：/etc/init.d/shadowsocks start

停止：/etc/init.d/shadowsocks stop

重启：/etc/init.d/shadowsocks restart

状态：/etc/init.d/shadowsocks status




