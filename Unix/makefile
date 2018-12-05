all:
	@echo use 'make install' to push sandbox into your environment
	@echo use 'make zhu' to pull envionment back into the sandbox

install:
	-cp $(HOME)/.bashrc $(HOME)/.bashrc-backup
	cp dot_bashrc $(HOME)/.bashrc
	-cp $(HOME)/.bash_aliases $(HOME)/.bash_aliases-backup
	cp dot_bash_aliases $(HOME)/.bash_aliases
	-cp $(HOME)/.profile $(HOME)/.profile-backup
	cp dot_profile $(HOME)/.profile

zhu:
	-cp $(HOME)/.bashrc dot_bashrc
	-cp $(HOME)/.profile dot_profile
	-cp $(HOME)/.bash_aliases dot_bash_aliases
