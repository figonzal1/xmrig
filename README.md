# XMRig

```sh
apt-get update &&
apt-get upgrade -y &&
apt-get install iputils-ping nano git -y && 
cd &&
git clone https://github.com/figonzal1/xmrig.git &&
cd xmrig &&
wget https://github.com/xmrig/xmrig/releases/download/v6.9.0/xmrig-6.9.0-linux-x64.tar.gz &&
tar -xzf xmrig-6.9.0-linux-x64.tar.gz &&
mv xmrig-6.9.0/xmrig xmrig &&
rm -rf xmrig-6.9.0 xmrig-6.9.0-linux-x64.tar.gz &&
./xmrig -c CONFIG_FILE
```