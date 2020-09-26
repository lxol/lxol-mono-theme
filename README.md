Lxol mono themes
==================

A collection of lxol monochrome emacs themes in a couple of variants.

![lxol-mono-white](https://raw.githubusercontent.com/cryon/lxol-mono-themes/master/readme-files/lxol-mono-white.png)

![lxol-mono-black](https://raw.githubusercontent.com/cryon/lxol-mono-themes/master/readme-files/lxol-mono-black.png)

Installation
============

Use package
-----------
If you have use-package setup on your system loading lxol-mono-themes is as simple as:

```lisp
(use-package lxol-mono-themes
  :config
  ;; (load-theme 'lxol-mono-black t)
  (load-theme 'lxol-mono-white t))
```

Manual installation
-------------------
If you prefer, you can install lxol-mono-themes manually by downloading the elisp files in this repo  and place them somewhere in your <code>custom-theme-load-path</code>.

You can set your <code>custom-theme-load-path</code> by adding this to your <code>.emacs.d</code> or <code>.emacs.d/init.el</code>:

```lisp
(add-to-list 'custom-theme-load-path "~/.emacs.d/themes")
```

You should now be able to load lxol-mono-themes with <code>M-x load-theme RET lxol-mono-{white, black}</code>!
