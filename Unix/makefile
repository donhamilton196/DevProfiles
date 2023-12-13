all:
	@echo "home=${HOME} ... (you may have to set it)"
	@echo use 'make install' to push sandbox into your environment
	@echo use 'make ns' to pull envionment back into the sandbox

install:
	-cp ~/.bashrc ${HOME}/.bashrc-backup
	cp dot_bashrc ${HOME}/.bashrc
	-touch ${HOME}/.bash_MyWinDesktop ${HOME}/.bash_MyWinDesktop-backup
	-cp ${HOME}/.bash_MyWinDesktop ${HOME}/.bash_MyWinDesktop-backup
	cp dot_bash_MyWinDesktop ${HOME}/.bash_MyWinDesktop
	-touch ${HOME}/.bash_MyUbuntu ${HOME}/.bash_MyUbuntu-backup
	-cp ${HOME}/.bash_MyUbuntu ${HOME}/.bash_MyUbuntu-backup
	cp dot_bash_MyUbuntu ${HOME}/.bash_MyUbuntu
	-touch ${HOME}/.bash_aliases ${HOME}/.bash_aliases-backup
	-cp ${HOME}/.bash_aliases ${HOME}/.bash_aliases-backup
	cp dot_bash_aliases ${HOME}/.bash_aliases
	-cp ${HOME}/.bash_git_aliases ${HOME}/.bash_git_aliases-backup
	cp dot_bash_git_aliases ${HOME}/.bash_git_aliases
	-touch ${HOME}/.profile ${HOME}/.profile-backup
	-cp ${HOME}/.profile ${HOME}/.profile-backup
	cp dot_profile ${HOME}/.profile
	-touch ${HOME}/.bash_MySANDBOX ${HOME}/.bash_MySANDBOX-backup
	-cp ${HOME}/.bash_MySANDBOX ${HOME}/.bash_MySANDBOX-backup
	cp dot_bash_MySANDBOX ${HOME}/.bash_MySANDBOX
	-mkdir -p ${HOME}/.config
	-mkdir -p ${HOME}/.config/gtk-3.0
	-touch ${HOME}/.config/gtk-3.0/gtk.css ${HOME}/.config/gtk-3.0/gtk.css-backup
	-cp ${HOME}/.config/gtk-3.0/gtk.css ${HOME}/.config/gtk-3.0/gtk.css-backup
	cp gtk.css ${HOME}/.config/gtk-3.0/gtk.css

ns:
	-cp ${HOME}/.bashrc dot_bashrc
	-cp ${HOME}/.profile dot_profile
	-cp ${HOME}/.bash_MyWinDesktop dot_bash_MyWinDesktop
	-cp ${HOME}/.bash_MyUbuntu .bash_MyUbuntu
	-cp ${HOME}/.bash_MyWin10Desktop .bash_MyWin10Desktop
	-cp ${HOME}/.bash_MySANDBOX .bash_MySANDBOX
	-cp ${HOME}/.bash_aliases dot_bash_aliases
	-cp ${HOME}/.bash_git_aliases dot_bash_git_aliases
	-cp ${HOME}/.config/gtk-3.0/gtk.css gtk.css
