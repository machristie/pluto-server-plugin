# Eclipse Pluto Server Plug-in #

To make developing portlets with Eclipse a little bit easier when using the Pluto bundled with Tomcat, I developed a little server plug-in that will automatically rewrite the web.xml as needed when publishing a portlet web application to the Pluto server on deployment from within Eclipse. This provides a nice lightweight rapid development environment without needing to maintain an additional pluto specific web.xml file.

Tested with Eclipse 3.3 (Europa) and requires WTP 2.0.3+.

## News ##

  * Jun 22, 2008 - Open sourced on Google Code, released minor version 0.2.5 to reference the new update site
  * Jun 01, 2008 - Added a [sample eclipse project](http://pluto-server-plugin.googlecode.com/files/test-portlet.zip), roughly equivalent to the hello world portlet in the [screencast demo](http://pluto-server-plugin.googlecode.com/files/demo.htm).
  * Oct 21, 2007 - Added a [screencast demo](http://pluto-server-plugin.googlecode.com/files/demo.htm).
  * Sept 13, 2007 - Released version 0.2.4.

## Update site ##

http://pluto-server-plugin.googlecode.com/svn/trunk/pluto.server.update

Just create a new "remote site" in the Eclipse update manager, using the above location, to install the Pluto server plug-in.

**Eclipse Europa users**: Make sure that you run the Update Manager to pull in the latest updates for WTP (at least version 2.0.3).  See [issue #2](http://code.google.com/p/pluto-server-plugin/issues/detail?id=2&can=1) for more details.

## Demo ##

See the [screencast](http://pluto-server-plugin.googlecode.com/files/demo.htm) which demonstrates how to install the plug-in, and how to create and deploy a simple portlet to Pluto.

## Screenshot ##

![http://pluto-server-plugin.googlecode.com/svn/www/new_server.png](http://pluto-server-plugin.googlecode.com/svn/www/new_server.png)

Adding a Pluto (bundled with Tomcat) server