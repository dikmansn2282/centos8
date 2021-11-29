# centos8
Centos 8

# Java
https://linuxize.com/post/install-java-on-centos-8/

# Ansible
https://linuxhint.com/install_ansible_centos8/

# Docker
https://linuxhint.com/install-use-docker-centos-8/

# Jenkins
https://linuxize.com/post/how-to-install-jenkins-on-centos-8/

# Github Link
https://github.com/yankils/Simple-DevOps-Project





# .bash_profile

# Get the aliases and functions
if [ -f ~/.bashrc ]; then
        . ~/.bashrc
fi

# User specific environment and startup programs
JAVA_HOME=/usr/lib/jvm/java-1.8.0-openjdk-1.8.0.312.b07-2.el8_5.x86_64
M2_HOME=/opt/maven
M2=/opt/maven/bin
PATH=$PATH:$HOME/bin:$JAVA_HOME:$M2:$M2_HOME

export PATH
