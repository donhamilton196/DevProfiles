all:
	@echo "home=${HOME} ... (you may have to set it)"
	@echo use 'make install' to push sandbox into your environment
	@echo use 'make install-MyUbuntu' to push platform dependent sandbox into your environment
	@echo use 'make install-MyWin10' to push platform dependent sandbox into your environment
	@echo use 'make install-MyWinDesktop' to push platform dependent sandbox into your environment
	@echo use 'make ns' to pull envionment back into the sandbox

install: install_profile
install: install_bashrc
install: install_bash_aliases
install: install_bash_git_aliases
install: install_gitconfig
install: install_gtk.css

install-MyUbuntu: install
	-touch ${HOME}/.bash_MyUbuntu ${HOME}/.bash_MyUbuntu-backup
	-cp ${HOME}/.bash_MyUbuntu ${HOME}/.bash_MyWinUbuntu-backup
	cp dot_bash_MyUbuntu ${HOME}/.bash_MyUbuntu

install-MyWin10: install
	-touch ${HOME}/.bash_MyWin10 ${HOME}/.bash_MyWin10-backup
	-cp ${HOME}/.bash_MyWin10 ${HOME}/.bash_MyWin10-backup
	cp dot_bash_MyWin10 ${HOME}/.bash_MyWin10

install-MyWinDesktop: install
	-touch ${HOME}/.bash_MyWinDesktop ${HOME}/.bash_MyWinDesktop-backup
	-cp ${HOME}/.bash_MyWinDesktop ${HOME}/.bash_MyWinDesktop-backup
	cp dot_bash_MyWinDesktop ${HOME}/.bash_MyWinDesktop

install_bashrc:
	-touch ${HOME}/.bashrc ${HOME}/.bashrc-backup
	-cp ~/.bashrc ${HOME}/.bashrc-backup
	cp dot_bashrc ${HOME}/.bashrc

install_bash_aliases:
	-touch ${HOME}/.bash_aliases ${HOME}/.bash_aliases-backup
	-cp ${HOME}/.bash_aliases ${HOME}/.bash_aliases-backup
	cp dot_bash_aliases ${HOME}/.bash_aliases

install_bash_git_aliases:
	-touch ${HOME}/.bash_git_aliases ${HOME}/.bash_git_aliases-backup
	-cp ${HOME}/.bash_git_aliases ${HOME}/.bash_git_aliases-backup
	cp dot_bash_git_aliases ${HOME}/.bash_git_aliases

install_profile:
	-touch ${HOME}/.profile ${HOME}/.profile-backup
	-cp ${HOME}/.profile ${HOME}/.profile-backup
	cp dot_profile ${HOME}/.profile

install_gitconfig:
	-touch ${HOME}/.gitconfig ${HOME}/.gitconfig-backup
	-cp ${HOME}/.gitconfig ${HOME}/.gitconfig-backup
	cp dot_gitconfig ${HOME}/.gitconfig

install_gtk.css:
	-mkdir -p ${HOME}/.config
	-mkdir -p ${HOME}/.config/gtk-3.0
	-touch ${HOME}/.config/gtk-3.0/gtk.css ${HOME}/.config/gtk-3.0/gtk.css-backup
	-cp ${HOME}/.config/gtk-3.0/gtk.css ${HOME}/.config/gtk-3.0/gtk.css-backup
	cp gtk.css ${HOME}/.config/gtk-3.0/gtk.css

ns:
	-cp ${HOME}/.bashrc dot_bashrc
	-cp ${HOME}/.profile dot_profile
	-cp ${HOME}/.bash_MyWin10 dot_bash_MyWin10
	-cp ${HOME}/.bash_MyWinDesktop dot_bash_MyWinDesktop
	-cp ${HOME}/.bash_MyUbuntu dot_bash_MyUbuntu
	-cp ${HOME}/.bash_MyWinDesktop dot_bash_MyWinDesktop
	-cp ${HOME}/.bash_MyWin10Desktop dot_bash_MyWin10Desktop
	-cp ${HOME}/.bash_MySANDBOX dot_bash_MySANDBOX
	-cp ${HOME}/.bash_aliases dot_bash_aliases
	-cp ${HOME}/.bash_git_aliases dot_bash_git_aliases
	-cp ${HOME}/.config/gtk-3.0/gtk.css gtk.css
	-cp ${HOME}/.gitconfig dot_gitconfig
