# openvpn_as_crack
openvpn access server install file and crack file.


1、安装
rpm -ivh openvpn-as-2.5.2-CentOSrelease.x86_64.rpm

yum -y install openvpn-as

passwd openvpn

https://****:943/admin

2、破解
cp pyovpn-2.0-py2.7.egg /usr/local/openvpn_as/lib/python2.7/site-packages/
cd /usr/local/openvpn_as/bin
./ovpn-init

如报错找不到相关模块，编辑_ovpn-init 注解掉即可

DELETE
yes
