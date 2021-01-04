# XMRig

```sh
apt-get update &&
apt-get upgrade -y &&
apt-get install iputils-ping nano git -y && 
cd &&
git clone https://github.com/figonzal1/xmrig.git &&
cd xmrig &&
tar -xzf xmrig-6.7.0-linux-x64.tar.gz &&
cd xmrig-6.7.0 &&
rm config.json &&
cp ../config.json config.json &&
./xmrig
```