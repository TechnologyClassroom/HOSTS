# HOSTS
HOSTS files can help protect educational environments from inappropriate materials online.

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br>Copyright © Michael McMahon 2011-2016.  Except where otherwise specified, the text on <a href="https://github.com/TechnologyClassroom/HOSTS/">HOSTS</a> by Michael McMahon is licensed under the <a href="https://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike License 4.0 (International) (CC-BY-SA 4.0)</a>.

The goal is to only allow games on Fridays while keeping a generally safe environment for children.  Creative projects should be made Monday-Thursday.

Manually updating and copying these files can be cumbersome so the process should be automated such as <a href="https://github.com/BlueHillBGCB/BAT">this example for Windows</a> or <a href="https://github.com/BlueHillBGCB/bash/blob/master/updatehosts.sh">this example for Mac</a>.

WARNING: I use this in addition to a content filter.  This is not complete and does not claim to be.

There are five main types of files here.
  * F files allow games.
  * MTWR files block games.
  * win files use the End of Line formatting for Windows systems.
  * unix files use the End of Line formatting for Linux, Mac, routers, and Unix systems.
  * LS files redirect to a local web server instead of giving an error.

I am looking for help with the following:
  * adding domains to HOSTSMTWRwin.txt or HOSTSFwin.txt
  * correcting improper categorazation

More information:
  * localhost is used to configure the loopback interface.
  * Loopbacks can redirect the domain to the IP address of your choosing.
  * 127.0.0.1 goes nowhere.
  * LS files can redirect inappropriate websites to a local web server full of constructive opportunities.  This is much better than the alternative of hitting a content filter dead end.
  * <a href="https://github.com/BlueHillBGCB/bash/blob/master/updateallhosts.sh">This script</a> builds each variation of these files automatically.
