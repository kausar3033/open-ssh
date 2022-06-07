## Welcome to Install OpenSsh

### Install openssh-server
		sudo apt-get install openssh-server
	
### Enable the ssh service	
		sudo systemctl enable ssh
	
### Start the ssh service	
		sudo systemctl start ssh
	
### Test it by login into the system using	
		ssh userName@Your-server-name-IP
		
### Configure firewall and open port 22
	sudo ufw allow ssh
	sudo ufw enable
	sudo ufw status
