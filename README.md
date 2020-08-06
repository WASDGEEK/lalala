# lalala
docker version > /dev/null || curl -fsSL get.docker.com | bash
service docker restart

mkdir v2ray-agent  &&  \
cd v2ray-agent && \
curl https://raw.githubusercontent.com/WASDGEEK/lalala/master/install.sh -o install.sh && \
chmod +x install.sh && \
bash install.sh
