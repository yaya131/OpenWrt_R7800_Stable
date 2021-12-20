新增ipq806x系列linksys.config是默认编译8350固件！如果需要编译linksys的ipq806x其他机型，请fork本项目，进入配置文件linksys.config。然后把#删除即可！举例子：#CONFIG_TARGET_ipq806x_generic_DEVICE_linksys_ea8500=y  只需要删除前面的#即可编译8500该机型！非常的简单！


集成全部USB网卡驱动，支持安卓USB共享网络！

精简仅集成如下

CONFIG_PACKAGE_luci-app-adguardhome=y

CONFIG_PACKAGE_luci-app-easymesh=y

CONFIG_PACKAGE_luci-app-frpc=y

CONFIG_PACKAGE_luci-app-frps=y

CONFIG_PACKAGE_luci-app-guest-wifi=y

CONFIG_PACKAGE_luci-app-jd-dailybonus=y

CONFIG_PACKAGE_luci-app-mwan3=y

CONFIG_PACKAGE_luci-app-ntpc=y

CONFIG_PACKAGE_luci-app-openclash=y

CONFIG_PACKAGE_luci-app-passwall=y

CONFIG_PACKAGE_luci-app-pptp-server=y

CONFIG_PACKAGE_luci-app-pushbot=y

CONFIG_PACKAGE_luci-app-qos=y

CONFIG_PACKAGE_luci-app-smartdns=y

CONFIG_PACKAGE_luci-app-sqm=y

CONFIG_PACKAGE_luci-app-syncdial=y

CONFIG_PACKAGE_luci-app-ttyd=y

CONFIG_PACKAGE_luci-app-udpxy=y

CONFIG_PACKAGE_luci-app-uhttpd=y

CONFIG_PACKAGE_luci-app-usb-printer=y

CONFIG_PACKAGE_luci-app-wifischedule=y

CONFIG_PACKAGE_luci-app-wireguard=y

AP版本仅有passwall,smartdns,usb共享，clash。
