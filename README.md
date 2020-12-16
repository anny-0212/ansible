
學習網站：http：// dic.vbird.tw/network_project/zunit05.php
#針對主機安裝 server(control node)
1.  yum install platform-python
2.  yum search release-ansible
3.  yum install centos-release-ansible-29
4.  yum config-manager --disable centos-ansible-29 yum config-manager --disable centos-release-ansible-29
5.  yum install platform-python python36 python3-libselinux python3-dnf

查看文件 ex:yum
ex:ansible-doc yum

##管理 managed host 
1. inventory 新增機器
