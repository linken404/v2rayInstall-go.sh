# v2rayInstall-go.sh
替代已经被废弃的v2ray自动安装脚本："https://install.direct/go.sh"

安装命令：
bash <(curl -L -s https://linken404.github.io/v2rayInstall-go.sh/go.sh)

说明：
新版本v2ray安装包中部分路径以及安装包的发布下载地址出现变更，导致旧脚本不能正常使用。
本页面中，已针对新版本v2ray的调整修改了原脚本，目前可以正常使用，可以正常安装或更新v2ray服务端。
由于最新的v2ray安装包中已经取消了init引导文件，粗略看来只支持systemd方式的服务引导，支持CentOS7以及较新的debian系统等，尽量不要使用过旧的操作系统进行安装。
以上为简单的说明，此脚本仅做粗略调整，并未深入研究，如有bug请反馈。
