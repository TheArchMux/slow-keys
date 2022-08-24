# slow-keys

[![License: GPL
v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0) [![MELPA](https://melpa.org/packages/slow-keys-badge.svg)](https://melpa.org/#/slow-keys)

Emacs minor mode to avoid RSI.

It forces you to type slowly by inhibiting typing for a customizable amount of
time and issuing a warning when you type too quickly.

Chris Done created [the original
package](https://github.com/chrisdone/chrisdone-emacs/blob/master/packages/slow-keys/slow-keys.el). Manuel Uberti merely
extracted it from its configuration and polished it for MELPA.

## Screenshot

![Screenshot](https://github.com/manuel-uberti/slow-keys/blob/master/screenshot.png)

## Setup

`slow-keys` is available on MELPA. You can easily install and configure it with
[use-package](https://github.com/jwiegley/use-package):

``` emacs-lisp
(use-package slow-keys
  :ensure t
  :init (slow-keys-mode 1))
```

## Configuration without `use-package`

``` emacs-lisp

(setq slow-keys-sleep-for 1.0)
(setq slow-keys-min-delay 0.03)

```
