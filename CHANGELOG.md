0.10.1 - 2015.02.21
===================

* update url domain changed from store.oregpreshaz.eu to bag.oregpreshaz.eu because startssl policy

0.10 - 2014.12.14
=================

* Add french language in locales - Thomas Baguet
* Use encodeURIComponent when sending login name and password

0.9 - 2014.07.26
================

* Allow installing on Thunderbird 31.* 

0.8 - 2014.01.10
================

* Ability to create library if doesn't exist

0.7 - 2014.01.08
================

* Handle if library not exist. (throw authErr)

0.6 - 2014.01.04
================

* fix for internationale characters in filename [unescape(encodeURIComponent(fileName))]
  - http://andre.arko.net/2012/09/18/force-encoding-in-javascript/

0.5 - 2014.01.03
================
* update url in install.rdf

0.4 - 2014.01.03
================
* do not uri encode filename at all (still can't upload, but at least it throw an error)

0.3 - 2014.01.03
================
* fix issue that not all files are uploaded in to /apps/mozilla_thunderbird

