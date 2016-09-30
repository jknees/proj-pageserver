# README #

A "getting started" project for CIS 322, software engineering 1 at University of Oregon.

### What do I need?  Where will it work? ###

* Designed for Unix, mostly interoperable on Linux (Ubuntu) or MacOS.
  Target environment is Raspberry Pi. 
  ** May also work on Windows, but no promises.  A Linux virtual machine
   may work, but our experience has not been good; if you don't have a 
   Raspberry Pi in hand yet, you may want to test on shared server ix. 
* You will need Python version 3.4 or higher. 
* Designed to work in "user mode" (unprivileged), therefore using a port 
  number above 1000 (rather than port 80 that a privileged web server would use)

### Assignment ###

* Basic web server that only replies to GET requests.
* Contains basic logic to deal with attempted access to web page
* Feeds the user trivia.html upon request as well as trivia.css

  ### Author: Jeffrey Knees , jknees@uoregon.edu ###

* Test deployment to other environments including Raspberry Pi.  Deployment 
  should work "out of the box" with this command sequence: 
  ** git clone <yourGitRepository> <targetDirectory>
  ** cd <targetDirectory>
  ** make configure
  ** make run 
  ** (control-C to stop program)
