# ansible-awx-test
  vi /etc/sysconfig/selinux
      reboot
      sestatus
      yum install -y epel-release
      yum install -y yum-utils device-mapper-persistent-data lvm2 ansible git python-devel python-pip python-docker-py vim-enhanced wget net-tools
      yum install git gcc gcc-c++ ansible nodejs gettext device-mapper-persistent-data lvm2 bzip2 python3-pip -y
     sudo yum install -y yum-utils
     yum-config-manager     --add-repo     https://download.docker.com/linux/centos/docker-ce.repo
     sudo yum install docker-ce docker-ce-cli containerd.io docker-compose-plugin
     systemctl start docker && systemctl enable docker
     yum install -y yum-utils device-mapper-persistent-data lvm2 ansible git python-devel python-pip python-docker-py vim-enhanced wget net-tool
     update-alternatives --config python
     update-alternatives --install /usr/bin/python python /usr/bin/python3.6 1
     update-alternatives --install /usr/bin/python python /usr/bin/python2.7 2
     update-alternatives --config python
     vim /usr/bin/yum
     yum-config-manager --add-repo=https://download.docker.com/linux/centos/docker-ce.repo
     vim /usr/bin/yum-config-manager
     yum-config-manager --add-repo=https://download.docker.com/linux/centos/docker-ce.repo
     pip3 install --upgrade setuptools
     pip3 install setuptools-rust
     pip3 install wheel
     pip3 install "pip>=20"
     pip3 install docker-compose
     openssl rand -base64 30
     cd /root ; wget https://github.com/ansible/awx/archive/15.0.0.tar.gz
     tar zxvf 15.0.0.tar.gz
     ln -s awx-15.0.0/ awx
     mkdir /var/lib/pgdocker
     cd awx/installer
     ansible-playbook -i inventory install.yml

