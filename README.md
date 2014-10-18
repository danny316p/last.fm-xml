last.fm-xml
===========

Simple XML/xsltproc scripts for easily viewing/customizing data from last.fm

Although the last.fm API gives you access to more data, you can use this code (or your own variations of it, which you are encouraged to share back to this repository) to more easily manipulate even the data from the regular last.fm website. On the "Charts" page of any user's profile, there's a link marked "Feeds" at the top right of the chart. Click on it for a variety of XML data (limited in size - for your complete data, you need to use the API). Once you've downloaded the XML, you can use xsltproc on the command line to format the data as you'd like. 

Example:
xsltproc single_line.xslt topartists.xml > testfile
