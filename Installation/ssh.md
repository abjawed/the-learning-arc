sshd(SSH) server Installation on Ubuntu:-
------------------------------------------------------
sudo apt update
sudo apt upgrade
sudo apt install openssh-server

sudo systemctl status ssh     	## To check the status the ssh Service
sudo systemctl enable ssh		## To Enable the ssh Service
sudo systemctl start ssh		## To Start the ssh Service
