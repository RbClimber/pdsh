pdsh-2.29.tar.bz2为源码包
pdsh-2.31.tar.gz为rpm压缩包
使用方法：
源码包：
tar jxvf pdsh-2.29.tar.bz2
cd pdsh-2.29
./configure --with-ssh --without-rsh --with-dshgroups --with-machines=/etcsh/machines
make && make install
pdsh -V
rpm：
解压，rpm -ivh *.rpm/yum -y --disablerepo=\* localinstall *.rpm
