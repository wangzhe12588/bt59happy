# bt59happy
安装方法（宝塔 5.9.1 开心版面板）
使用 SSH 连接工具 连接到您的 Linux服务器后，根据系统执行相应命令开始安装（大约2分钟完成面板安装）：

centos安装脚本:
yum install -y wget && wget --no-check-certificate -O install.sh https://raw.githubusercontent.com/wangzhe12588/bt59happy/master/install-5.9-c.sh && sh install.sh

ubuntu安装脚本:
wget --no-check-certificate -O install.sh https://raw.githubusercontent.com/wangzhe12588/bt59happy/master/install-ubuntu.sh && sudo bash install.sh

debian安装脚本：
wget --no-check-certificate -O install.sh https://raw.githubusercontent.com/wangzhe12588/bt59happy/master/install-ubuntu.sh && bash install.sh

如果 你是免费的 5.x 宝塔面板 可以使用脚本 升到最新的开心版 5.9.1 面板 或者 输入：
curl https://raw.githubusercontent.com/wangzhe12588/bt59happy/master/update_pro.sh | bash 

恢复免费面板:
wget -O update.sh http://download.bt.cn/install/update.sh && bash update.sh free
