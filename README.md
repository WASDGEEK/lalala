# lalala
domain;0;16;tls;ws;path=/v2ray|host=domain|inside_port=10550|outside_port=443

systemctl stop firewalld.service.

docker version > /dev/null || curl -fsSL get.docker.com | bash

service docker restart

mkdir v2ray-agent  &&  \
cd v2ray-agent && \
curl https://raw.githubusercontent.com/WASDGEEK/lalala/master/install.sh -o install.sh && \
chmod +x install.sh && \
bash install.sh
