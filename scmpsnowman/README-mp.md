# scmpsnowman

This is a port of the scsnowman package to use MetaPost, instead of TikZ.

## Requirements

This package does NOT require "tikz" package.
On the other hand, this package requires following packages:
 - luamplib (luatex) or gmp (other engines)
 - color
 - etoolbox
 - keyval

Notes:
 - The xcolor package is not required, but highly recommended.
 - If you use this package with engines other than Lua(La)TeX,
   specifying "shellescape" option to the gmp package and
   specifying "-shell-escape" in the command line are recommended.

