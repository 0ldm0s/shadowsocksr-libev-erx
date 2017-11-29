# shadowsocksr_edgerouter_x
shadowsocksr-libev debian package for EdgerRouter X

dpkg -b shadowsocksr-libev-debian

scp shadowsocksr-libev-debian.deb ubnt@RouterIP:/tmp

ssh ubnt@RouterIP

sudo -i

cd /tmp

dpkg -i shadowsocksr-libev-debian.deb
