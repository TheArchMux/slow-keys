# slow-keys

Emacs minor mode to avoid RSI.

It forces you to type slowly by inhibiting typing for a customizable amount of
time and issuing a warning when you type too quickly.

## Setup

`slow-keys` is not available on MELPA yet. You can easily install and configure
it with [use-package](https://github.com/jwiegley/use-package):

``` emacs-lisp
(use-package slow-keys
  :load-path "/path/to/slow-keys"
  :init (slow-keys-mode 1))
```
