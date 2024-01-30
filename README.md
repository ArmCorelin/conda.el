# conda.el 
## Added set & unset env feature to necaris' original conda.el


## Issues

Tnanks for necaris original version of conda.el, we can use conda command in Emacs.
But I found some issues and I try to fix it.

* Now conda command needs some more environment Variables manipulation.
  Such as 'unset' or 'set' command to deactivate it properly.
  
(I found other issues but I don't touch them now.)

Now you can deactivate in your shell in emacs even Vterm.

Please find original Documents to use.
[README is here](https://github.com/ArmCorelin/conda.el/blob/main/README.md "https://github.com/ArmCorelin/conda.el/blob/main/README.md").

enjoy!

X account: https://twitter.com/ARMcoreLinux

## Change-log

240119 Added automatic lsp restart when (de)activate envs.
       Now lsp-mode follows your current environment.
240131 Changed 2nd parameter for setenv, '' to nil
