GStreamer Pocketsphinx Demo
===========================

This is a demo of pocketsphinx working with gstreamer 0.10 in python 2.7 on ubuntu 14.04.

Much of it follows from the CMUSphinx wiki page
["Using PocketSphinx with Gstreamer and Python (or Vala)"](http://cmusphinx.sourceforge.net/wiki/gstreamer?s[]=languagemodelhowto),
but modified to make the demo simpler and more likely to work with current software versions (it was last updated in 2012).


Dependencies
------------

This demo requires pocketsphinx and its python bindings to be installed, as well as gstreamer-0.10. At this time, pocketsphinx 
is dependent on v0.10 and cannot run with v1.0 (see [this request](https://bugs.tizen.org/jira/browse/TIVI-2749)).

Installation of pocketsphinx can be done via:


Installation of dependencies can be done on Ubuntu 14.04 with the following console command:
`sudo apt-get install gstreamer-0.10 python-gst0.10 gstreamer-0.10-pocketsphinx`

