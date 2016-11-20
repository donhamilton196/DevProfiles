all:
	@echo use make install to push sandbox to your environment
	@echo use make zhu to pull environment back to the sandbox

install:
	-cp ~/.emacs ~/.emacs-backup
	-cp DotEmacs ~/.emacs
	-(cd ./elisp ; tar cpf - ./)|(cd ~/elisp ; tar xpf -)

zhu:
	-cp ~/.emacs DotEmacs
	-(cd ~/elisp ; tar cpf - ./)|(cd ./elisp ; tar xpf -)
