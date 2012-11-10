ldtp
====

LDTP client

Linux Desktop Testing Project - http://ldtp.freedesktop.org LDTP works on Windows/Linux/Mac/Solairs/FreeBSD/NetBSD/Palm Source, yes its Cross Platform GUI testing tool. Please share your feedback with us (nagappan@gmail.com).

 * Linux GUI testing is known to work on GNOME / KDE (QT >= 4.8) / Java Swing / LibreOffice / Mozilla application on all major Linux distribution
 * Windows GUI testing is known to work on application written in .NET / C++ / Java / QT on Windows XP SP3 / Vista SP2 / Windows 7 / Windows 8 development version
 * Mac GUI testing is known to work on OS X Snow Leopard/Lion/Mountain Lion. Where ever ATOMac runs, LDTP should work on it

Supported languages to write test script:

Python >= 2.5
Java >= 1.5
C# >= 3.5
VB.NET
Power Shell
Ruby >= 1.8.x
Perl
Clojure

For Java compilation:

Download commons-codec-1.6.jar, ws-commons-util-1.0.2.jar, xmlrpc-client-3.1.3.jar, xmlrpc-common-3.1.3.jar, commons-logging-1.1.1.jar, commons-logging-adapters-1.1.1.jar, commons-logging-api-1.1.1.jar and place it in ldtp/Java/lib/

Download jar files from this location or any other apache mirror. Make sure you have the version mentioned in the jar or latest
http://mirror.cc.columbia.edu/pub/software/apache/commons/codec/binaries/commons-codec-1.6-bin.zip
http://www.apache.org/dyn/closer.cgi/ws/xmlrpc/
http://commons.apache.org/logging/download_logging.cgi

In eclipse its compiled by default. FIXME: Write how to compile from command line

To create Ldtp.jar

cd ldtp\JavaLDTP\bin
jar cvf ..\..\Ldtp.jar * # Note: Tested this on Mac with a forward slash though, haven't created Jar on Windows

To use LDTP Java library:

Include Ldtp.jar file available under ldtp folder in your project

How do I contact LDTP team incase of any help ?

  - Join the LDTP team on IRC for technical help, online
    Server  : irc.freenode.net
    Channel : #ldtp
  - Join the LDTP Mailing List - http://ldtp.freedesktop.org/wiki/Mailing_20list
