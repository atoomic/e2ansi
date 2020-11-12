# Installing e2ansi with emacs

## Install package face-explorer

Add this to ~/.emacs to load packages from other sources

```
(require 'package)
(package-initialize)

(add-to-list 'package-archives
             '("marmalade" . "http://marmalade-repo.org/packages/") t)

(add-to-list 'package-archives '("melpa" . "http://melpa.org/packages/"))
```

References:
https://www.emacswiki.org/emacs/InstallingPackages
https://batsov.com/articles/2012/02/19/package-management-in-emacs-the-good-the-bad-and-the-ugly/

M-X is escape-X
so we can use the list 

Type `M-x list-packages` to open the package list. `wait....`

Press `‘i’` to mark for installation, `‘u’` to unmark, and `‘x’` to perform the installation. 
Press `‘RET’` to read more about installing and using each package.

Look for face-explorer, and install it.