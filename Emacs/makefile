all:
	@echo use make install to push sandbox to your environment
	@echo use make zhu to pull environment back to the sandbox

install:
	-cp $(HOME)/.emacs $(HOME)/.emacs-backup
	-cp DotEmacs $(HOME)/.emacs
	-mkdir -p $(HOME)/elisp
	-cp elisp/cmake-mode.el $(HOME)/elisp/cmake-mode.el
	-cp elisp/csharp-mode.el $(HOME)/elisp/csharp-mode.el
	-cp elisp/web-mode.el $(HOME)/elisp/web-mode.el
	-cp elisp/clang-format.el $(HOME)/elisp/clang-format.el

zhu:
	-cp $(HOME)/.emacs DotEmacs
	-cp $(HOME)/elisp/cmake-mode.el elisp/cmake-mode.el
	-cp $(HOME)/elisp/csharp-mode.el elisp/csharp-mode.el
	-cp $(HOME)/elisp/web-mode.el elisp/web-mode.el
	-cp $(HOME)/elisp/clang-format.el elisp/clang-format.el
