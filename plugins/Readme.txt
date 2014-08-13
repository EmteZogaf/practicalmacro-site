#Version 0.4.8
 
 
* System Requirements: Eclipse 3.4+, JDK 1.5+.  
 
* Install (several ways to install) 
 
* Add a remote update site through Help->Software Updates:
http://puremvcnotificationviewer.googlecode.com/svn/trunk/PracticallyMacroGoogleUpdateSite.  The 
exact instructions differ depending on which version of Eclipse you are using.
You should be able to turn on Eclipse auto updates and 
be notified when a new version is published (if ever).  You may have to set up proxy 
settings in the Eclipse preferences if you are behind a corporate 
firewall.  Note: if you are running Eclipse 3.5 and the update site doesn't work
for you, try adding "/site.xml" on the end and see if that helps.  
 
* Download the zip file and extract the 2 plugins jars into the 
Eclipse dropins 
directory (Eclipse 3.4+) and restart Eclipse.  Enough people have had problems with this with Eclipse 3.4+ that I recommend only using the update site.
 
* Bugs: Undoubtedly.  I have not touched this project for some time and I hope it is helpful to people.  However,
changes to Eclipse may break this plugin, and I don't have a lot of time to support it.  If you find something, feel free to create a 
bug/feature report through the 'tracker', but don't expect much.

 
-----------------------------------------------------------------------------------------------------------
#Change log

###0.4.8

8/13/2014

####New Features

* Added a second mark
* Show mark positions during macro debug

####Fixes

* Changed mark to not move if the inserted text is at the mark position.  This seems like a more natural behavior that matches selection semantics.
  
###0.4.6

6/16/2014

####New Features

* None.

####Fixes

* http://sourceforge.net/p/practicalmacro/bugs/19/ -- code folding caused problems with find/replace
  
###0.4.5

1/4/2014

####New Features

* None.

####Fixes

* https://sourceforge.net/p/practicalmacro/bugs/8/  Shift+UpArrow, Shift+DownArrow and Ctrl+Backspace 
didn't work.  Had to add those into my manual key handling.
  
###0.4.4

12/28/2013

####New Features

* None.

####Fixes

* http://sourceforge.net/p/practicalmacro/bugs/17/  Bug when used on Eclipse 4.3 and 4.3.1 where certain
commmon commands (like Copy) don't work correctly because of asynchronous processing of selection 
changes.  

###0.4.2

7/13/2013

####New Features

* None.

####Fixes

* Key bindings didn't work in Eclipse 4+.  This was caused by some changes in Eclipse as part of the
new architecture.  I believe I have mostly hacked around the problem in a way that works in both Eclipse
3.x and 4.x, but it's possible I have missed something.  The Eclipse bug: https://bugs.eclipse.org/bugs/show_bug.cgi?id=407749 

###0.4.0

11/10/2012
####New Features

* None.

####Fixes

* Find dialog while recording macro should now work in Eclipse 4.2 (Juno) 

###0.3.4

9/1/2011
####New Features

* None.

####Fixes

* Defined macros should now be runnable via Ctrl+3 

