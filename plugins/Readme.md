#Version 0.4.0
 
 
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
changes to Eclipse may break this plugin, and I don't have a lot of time to support it.  If you find something, feel free ot create a 
bug/feature report through the 'tracker', but don't expect much.

 
-----------------------------------------------------------------------------------------------------------
#Change log

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

