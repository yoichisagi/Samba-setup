# samba set-up

Change IPv4

sudo apt install openssh-server

sudo systemctl status ssh

GO TO WIN powesell> ssh user@192.168.10.

sudo apt install samba

samba --version	

mkdir
```
sudo nano /etc/samba/smb.conf
```
edit :  
[haven-share]
	comment = Haven Samba Share
	path = /home/haven/haven-share
	read only = no
	browsable = yes
```	
sudo service smbd restart
sudo ufm allow samba
sudo smbpasswd -a haven

```


WIN TERMINAL >  \\192.168.10. \haven
