CEF WITH SYPHON
---------------

This is an application for Mac OS X which makes it poosible to share the contents of a web browser (based on Chrome) using Syphon. It implements most of the things you'd expect except pop up windows (at the moment). Complicated html pages do not run as fast as a real Chrome browser but e.g. Flash and WebGL seems to run smoothly.

Build the code or download CefWithSyphon.zip from the project

DISCLAIMER
----------

The application was created by modifying the cefclient sample application that comes with the OS X download from this page: 
http://www.magpcss.net/cef_downloads/index.php?query=label%3A%7EDeprecated+label%3ACEF3+label%3Abinary#list

This is a quick hack so far but it might be useful as it is. It is not really tested so post any issues here on Github and we'll see what happens... 
I am not affiliated with the CEF development team and I have limited knowledge of the underlying technology.

The modification was done by adding the Syphon framework plus a handful of changes to the code. Find them by searching for 'syph' in the comments. Note that compiler settings may need to be changed - see the Cef-readme.txt

BUILDING WITH XCODE
-------------------

Because Github has a 100 MB size limit on files I cannot upload the project ready to compile. Instead you have to first unzip the cef_binary_3-1.1547.1412_macosx32 and then drop 1) The cefclient folder, 2) the xcode project and 3) the Syphon framework into the unzipped folder.

ABOUT SYPHON
------------

Syphon is a brilliant (Mac OS X only) way to share frames between applications with almost no performance penalty. It is used a lot in live visual performance and creative coding circles.
Learn about Syphon: http://syphon.v002.info

CEF - Chromium Embedded framework
---------------------------------

As the name implies this application uses CEF3. This is a wrapper around Chromium which makes it possible to use the Chrome technology embedded in regular desktop applications for Mac OSX, Windows and Linux. Chromium is the open source project behind Google Chrome.

http://code.google.com/p/chromiumembedded/
http://www.chromium.org