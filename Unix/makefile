all:
	@echo use 'make install' to push sandbox into your environment
	@echo use 'make zhu' to pull envionment back into the sandbox

install:
	cp ~/.bashrc ~/.bashrc-backup
	cp dot_bashrc ~/.bashrc
	-cp ~/.bash_aliases ~/.bash_aliases-backup
	cp dot_bash_aliases ~/.bash_aliases
	cp ~/.profile ~/.profile-backup
	cp dot_profile ~/.profile

zhu:
	-cp ~/.bashrc dot_bashrc
	-cp ~/.profile dot_profile
	-cp ~/.bash_aliases dot_bash_aliases
