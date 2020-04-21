# devsetup
echo "# devsetup" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/110crosswalk/devsetup.git
git push -u origin master
                
…or push an existing repository from the command line
git remote add origin https://github.com/110crosswalk/devsetup.git
git push -u origin master
…or import code from another repository
You can initialize this repository with code from a Subversion, Mercurial, or TFS project.


#!/bin/bash


hostnamectl set-hostname 'scan-dev' 

echo "resu ALL=(ALL) NOPASSWD: ALL" > /etc/sudoers

apt-get update
apt-get upgrade


apt-get install mc -y
apt-get -y install git
apt-get -y install gcc
apt-get -y install make linux-headers-generic build-essential
apt-get -y install aircrack-ng
