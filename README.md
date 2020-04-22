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


sudo nano /etc/modprobe.d/blacklist.conf

blacklist snd
blacklist snd_bcm2835
blacklist hci_uart
blacklist rfcomm
blacklist btintel
blacklist bluetooth
blacklist btintel
blacklist btqca
blacklist btbcm
blacklist bnep
blacklist snd_seq_midi
blacklist snd_seq_dummy
blacklist ip_tables
blacklist snd_pcm_oss
blacklist snd_mixer_oss
blacklist x_tables
blacklist snd_seq_oss
blacklist snd_bcm283
blacklist snd_seq_midi_event
blacklist snd_rawmidi
blacklist snd_pcm_oss
blacklist snd_pcm
blacklist uio
blacklist uio_pdrv_genirq
blacklist parport



sudo rmmod rfcomm
sudo rmmod bnep
sudo rmmod snd_pcm_oss
sudo rmmod snd_mixer_oss
sudo rmmod x_tables
sudo rmmod snd_seq_oss
sudo rmmod snd_bcm283

sudo rmmod snd_seq_midi_event
sudo rmmod snd_rawmidi


