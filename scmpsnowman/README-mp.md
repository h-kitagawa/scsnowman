# scmpsnowman

This is a port of the scsnowman package to use mplib library
(the MetaPost library which is integrated into LuaTeX), instead of TikZ.

## Requirements

This package does NOT require "tikz" package.
On the other hand, this package requires following packages:
 - luamplib
 - color
 - etoolbox
 - keyval

Loading the xcolor package is highly recommended, since "getting
current foreground color" requires it. 
In other words, {\color{red}\scsnowman}} draws a snowman in black, 
not red, without loading the xcolor package.

