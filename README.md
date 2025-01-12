# awesome-scite

SciTE, or SCIntilla based Text Editor, is a cross-platform text editor created by Neil Hodgson.


## scite project

## plugin and package management

### extman

at least two versions:

  * original
  * subset, with same API but less features

both lost as lua forge died.

  * http://lua-users.org/wiki/SciteExtMan

### scipm

  * https://github.com/aminassianOLD/scipm - SciTE package manager (node.js)

## spell check

luahunspell the first, original website now dead.

  * https://code.google.com/archive/p/luahunspell/
      * https://github.com/clach04/luahunspell/releases - mirror

also see
  * https://bitbucket-archive.softwareheritage.org/new-static/b4/b492dfdd-81d2-4b96-aafc-bbcbd06f2843/attachments/
  * https://gitlab.com/rychly/luaspell


[Orthospell](http://web.archive.org/web/20161010154412/http://tools.diorama.ch/orthospell.html) by Urs Eberle is based on hunspell (uses original dll) and modified version of the original extman.lua (without spawner_ex.dll). It requires shell.dll to run! NOTE original website dead. There was a PDF manual (see https://github.com/clach04/luahunspell/issues/2#issuecomment-1722285721).

  * https://groups.google.com/g/scite-interest/c/Eu8D7E5yqrE
  * original download page http://web.archive.org/web/20150727024625/http://tools.diorama.ch/ortho_download.html
  * https://dreamcloud.artark.ca/scite-spell-check/
  * https://github.com/aminassianOLD/scipm.orthospell note needs [scipm](https://github.com/clach04/awesome-scite/blob/main/README.md#scipm)
      * https://github.com/robertluwang/scite-setting/blob/master/scite-spell.md

## shared libraries/ DDLs

commonly used compiled 3rd party libs:

 * spawner_ex.dll
 * shell.dll


https://github.com/mkottman/scite/blob/master/scite/custom/scite-debug/win32-spawner-ex.c

http://lua-users.org/wiki/SciteLuaDll

## lua

https://www.scintilla.org/SciTELua.html

http://lua-users.org/wiki/SciteExtMan

  * https://github.com/Ensequence/js2lua

plugins
<details>
  * https://github.com/mkottman/scite/blob/master/scite/custom/scite-debug/scite_lua/micromode.lua

</details>
## Python

## distributions

  * upstream have two, full and sc1
  * https://github.com/mkottman/scite/tree/master - old but includes some of the above libs and extensions

## Alternative Scintilla based editors

  * TextAdept

