![http://voxforge.googlecode.com/files/voxforge-logo.jpg](http://voxforge.googlecode.com/files/voxforge-logo.jpg)

The SubmitSpeech page on the VoxForge Google site contains a Java applet.  A [Java applet](http://en.wikipedia.org/wiki/Java_applet) is basically a Java program that runs on the [Java Run-time Environment](http://en.wikipedia.org/wiki/Java_Runtime_Environment) on your PC, but looks like it forms part of a web page.  Part of the start-up process for any Java applet is a check to see if the applet is going to use any resources on your PC - like accessing to your hard drive, the Internet, etc.

## Java Security Warning Pop-up ##

The VoxForge Speech Submission Application is a Java Applet.  It creates temporary files on your PC to hold your audio as you record each prompt line (in addition to your responses to the form questions, and the prompts themselves) and then moves them to a zip file to be uploaded to the VoxForge server.  Because of this, the Java Run-time Environment on your PC displays a Security Warning pop-up like this:

![http://voxforge.googlecode.com/files/SecurityWarning.jpg](http://voxforge.googlecode.com/files/SecurityWarning.jpg)

It is up to you to decide whether you want to permit the VoxForge Speech Submission Application to run on your PC.

Please be aware that by clicking the "run" button you are permitting this application to run without the security restrictions normally provided by Java.

However, the intent of this application is only to create temporary files to permit you to record your speech and upload the result to the VoxForge server.  We don't collect any information from your PC (though there will be a log entry on the web server when you upload your file).  Once your close your browser, and your Java Run-time Environment terminates normally, these files will be removed from your PC.

The  good thing about Open Source software is that the [source code](http://www.dev.voxforge.org/projects/Main/browser/Trunk/SpeechSubmission/VFSpeechSubmission/java/src/speechrecorder) for this application is available for review, and anyone can confirm this.

## What is Thawte? ##

From their [Wikipedia](http://en.wikipedia.org/wiki/Thawte) entry:

> [Thawte Consulting](http://www.thawte.com/) is a [certificate authority](http://en.wikipedia.org/wiki/Certificate_authority) (CA) for [X.509](http://en.wikipedia.org/wiki/X.509) certificates. Thawte, (pronounced like "thought"), was founded in 1995 by [Mark Shuttleworth](http://en.wikipedia.org/wiki/Mark_Shuttleworth) in South Africa and is the second largest public CA on the Internet.

Thawte offers [free email certificates](http://www.thawte.com/secure-email/personal-email-certificates/index.html) that can be used sign Java code for use in Java Applets (Richard Dallaway's [Java Web Start and Code Signing](http://www.dallaway.com/acad/webstart/) page provides the details on how this can be done).  This is why "Thawte E-mail Member" appears as the publisher on the certificate.

## Why voxforge.googlecode.com rather than www.voxforge.org? ##

Simply because the front-end server for [voxforge.org](http://www.voxforge.org) is on a server connected to a low-bandwidth Internet connection.  [voxforge.googlecode.com](http://voxforge.googlecode.com) is located on a Google server which has a much higher bandwidth connection.

|Note: Any submitted speech gets uploaded to the VoxForge repository on [read.voxforge1.org](http://read.voxforge1.org/).  This is the same server that currently houses the [VoxForge Speech Corpus](http://www.repository.voxforge1.org/downloads/SpeechCorpus/Trunk/).|
|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|

## More Info ##

If you click the "more info", you will see something like this:

![http://voxforge.googlecode.com/files/MoreInformation.jpg](http://voxforge.googlecode.com/files/MoreInformation.jpg)

These are standard Java Applet warnings that appear when you start a Java Application that might use resources on your PC.

## Certificate Details ##

And if you click "Certificate Details", you will find a line like this (after clicking the Thawte Freemail Member item in the left-hand menu column):

![http://voxforge.googlecode.com/files/DetailsCertificate.jpg](http://voxforge.googlecode.com/files/DetailsCertificate.jpg)

This shows that the certificate, even though it has "Thawte E-mail Member" as the publisher, is registered to me: [kmaclean](http://www.voxforge.org).

© 2006-2010 [VoxForge](http://www.voxforge.org/); Legal: [Terms and Conditions](http://www.voxforge.org/home/about/legal)