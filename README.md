# www-label-php
Repository for the old tool PHP still used at EPFL VPSI -> label.php  

**:warning: Do not use this old tool for new developments :warning:**

Description
-----------
The label.php script generate an image from a text.

Configuration
-------------
A ProxyPass is configured in www servers (old homepage still used for web2010 EPFL libraries).
```
ProxyPass        /tools  http://wwwlabel.epfl.ch/tools
ProxyPassReverse /tools  http://wwwlabel.epfl.ch/tools
```
wwww.epfl.ch/tools -> wwwlabel.epfl.ch/tools  

The PHP script is deployed in the LAMP server.

Example usage
-------------
URL:  
`https://www.epfl.ch/tools/label.php?s=22&BG=99cccc&FG=ffffff&label=inForm`

Generate:  
<img alt="Exemple label.php" src="https://raw.githubusercontent.com/epfl-idevelop/www-label-php/master/exemple.png">

Who still used this tools
-------------------------
* inform.epfl.ch
* mediatheque-old.epfl.ch
* ticketshop.epfl.ch
* people.epfl.ch
* moodlearchive.epfl.ch
* LAMP websites
* archived websites (archive.epfl.ch)
* ...
