# some useful commands
sudo adduser newuser
cut -d: -f1 /etc/passwd

- install SAMBA
sudo apt update
sudo apt install samba
whereis samba
  /etc/samba
sudo nano /etc/samba/smb.conf
[dirName]
    comment = Samba on Ubuntu
    path = /home/username/sambashare
    read only = no
    browsable = yes
    
sudo smbpasswd -a userName


- add user to sudo
sudo adduser <username> sudo


