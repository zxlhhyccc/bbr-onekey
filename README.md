# BBR-onekey
仅适用于Debian/Ubuntu系统。

BBR.sh（更新新版内核并开启原版BBR）

执行下面脚本一键开启

wget --no-check-certificate -qO 'BBR.sh' 'https://raw.githubusercontent.com/hotplmm/bbr-onekey/master/BBR.sh' && chmod a+x BBR.sh && bash BBR.sh -f

-BBR.sh   (关闭原版bbr)

bash <(curl -s -L https://raw.githubusercontent.com/hotplmm/bbr-onekey/master/-BBR.sh)

查看bbr运行状态

lsmod |grep 'bbr'

进阶安装魔改版BBR

wget --no-check-certificate -qO 'BBR_POWERED.sh' 'https://raw.githubusercontent.com/hotplmm/bbr-onekey/master/BBR_POWERED.sh' && chmod a+x BBR_POWERED.sh && bash BBR_POWERED.sh

完成之后执行下面的命令检查是否安装成功

lsmod |grep 'bbr_powered'

如果结果有 bbr_powered 则说明加载成功！

关闭魔改版BBR

bash <(curl -s -L https://raw.githubusercontent.com/hotplmm/bbr-onekey/master/bbr-off.sh)

如果需要重新开启魔改版BBR，输入下面指令

bash <(curl -s -L https://raw.githubusercontent.com/hotplmm/bbr-onekey/master/bbr-on.sh)

来自网络 Vicer 大佬的脚本！新人试手只为方便查找参考而坐！
