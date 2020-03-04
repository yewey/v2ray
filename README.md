ubuntu/debian 系统安装 Curl 方法: apt-get update -y && apt-get install curl -y

centos 系统安装 Curl 方法: yum update -y && yum install curl -y

安装v2ray

bash <(curl -s -L https://git.io/v2ray.sh)

安装自己的配置

git clone https://github.com/yewey/v2ray -b master

cd v2ray

chmod +x install.sh

./install.sh local
