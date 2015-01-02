# evil-tutor

Vimtutor adapted for Evil.

    M-x evil-tutor/start

This will create a working file in `evil-tutor-working-directory` (defaults
to `~/.emacs.d/.tutor`)

Features:
- restore last working file
- fast navigation between lessons with `C-j` and `C-k`

This major-mode has been inspired by a [post][] on [/r/emacs][].

## Install

The package _will be available soon_ in [MELPA][].

If you have MELPA in `package-archives`, use

    M-x package-install RET evil-tutor RET

If you don't, open `evil-tutor.el` in Emacs and call
`package-install-from-buffer`.

[MELPA]: http://melpa.org/
[/r/emacs]: http://www.reddit.com/r/emacs/
[post]: http://redd.it/2r1g3d
