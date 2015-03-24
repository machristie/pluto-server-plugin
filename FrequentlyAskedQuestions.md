# Frequently Asked Questions (FAQ) #

### When I try to publish my portlet to Pluto, I get `Could not publish to the server. java.lang.NullPointerException` ###

This is caused by [bug 219627](https://bugs.eclipse.org/bugs/show_bug.cgi?id=219627) in WTP 2.0.2.  The Eclipse team provided a patch and also made a 2.0.3 maintenance release (containing the patch).  **However**, you don't get this bug fix with the latest version of Europa to download (the winter release).  You need to run the Eclipse update manager to download the latest updates.

The fix for this bug is already in WTP 3.0, which is the WTP version included with the JEE package of Eclipse Ganymede.