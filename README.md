# HOSTS
HOSTS files can help protect educational environments from inappropriate materials online.

Michael McMahon

The goal is to only allow games on Fridays while keeping a generally safe environment for children.  Creative projects should be made Monday-Thursday.

Manually updating and copying these files can be cumbersome so the process should be automated such as <a href="https://github.com/BlueHillBGCB/BAT">this example for Windows</a>.

WARNING: I use this in addition to a content filter.  This is not complete and does not claim to be.

There are five main types of files here.
  * F files allow games.
  * MTWR files block games.
  * win files use the End of Line formatting for Windows systems.
  * unix files use the End of Line formatting for Linux, Mac, routers, and Unix systems.
  * LS files redirect to a local web server instead of giving an error.

I am looking for help with the following:
  * adding domains to this list
  * correcting improper categorazation

More information:
  * localhost is used to configure the loopback interface.
  * Loopbacks can redirect the domain to the IP address of your choosing.
  * 127.0.0.1 goes nowhere.
  * LS files can redirect inappropriate websites to a local web server full of constructive opportunities.  This is much better than the alternative of hitting a content filter dead end.
