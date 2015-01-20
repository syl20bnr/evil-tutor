# evil-tutor
[![MELPA](http://melpa.org/packages/evil-tutor-badge.svg)](http://melpa.org/#/evil-tutor) [![MELPA Stable](http://stable.melpa.org/packages/evil-tutor-badge.svg)](http://stable.melpa.org/#/evil-tutor)

<!-- markdown-toc start - Don't edit this section. Run M-x markdown-toc/generate-toc again -->
**Table of Contents**

- [evil-tutor](#evil-tutor)
    - [Description](#description)
    - [Quick start](#quick-start)
    - [Install](#install)
        - [Package manager](#package-manager)
        - [Manually](#manually)
    - [Acknowledgement](#acknowledgement)

<!-- markdown-toc end -->

## Description

Vimtutor adapted for Evil and wrapped in a major mode.

Features:
- restore last working file
- fast navigation between lessons with `C-j` and `C-k`

## Quick start

    M-x evil-tutor-start

This will create a working file in `evil-tutor-working-directory` (defaults
to `~/.emacs.d/.tutor`)

## Install

### Package manager

You can either install `evil-tutor` from [MELPA][] (_available soon_):

```
 M-x package-install evil-tutor
```

Or add it to your `Cask` file:

```elisp
(source melpa)

(depends-on "evil-tutor")
```

### Manually

Add `evil-tutor.el` to your load path. `evil-tutor` requires `evil` to be
installed.

## Acknowledgement

This major-mode has been inspired by a [post][] on [/r/emacs][].

[MELPA]: http://melpa.org/
[/r/emacs]: http://www.reddit.com/r/emacs/
[post]: http://redd.it/2r1g3d
