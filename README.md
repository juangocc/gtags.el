gtags.el
========

vanilla copy of http://cvs.savannah.gnu.org/viewvc/*checkout*/global/global/gtags.el?revision=HEAD

Test on :

"GNU Emacs 23.4.1 (i486-pc-linux-gnu, GTK+ Version 2.24.10)
 of 2012-09-09 on murphy, modified by Debian"
 
 How it works
 ============
 
 In your .emacs file, include directories separated by colon (:).
Example :

(require 'gtags)
(autoload 'gtags-mode "gtags" "" t)
(gtags-external-libraries "/usr/include:/usr/lib")
 
  NEWS 
  ======
  [2014-07-4 Fri] 3.8.1
  ======================

1.    New command gtags-external-libraries , Search GTAGSLIBPATH for references and symbols..
