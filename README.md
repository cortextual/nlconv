nlconv
======

Fancy Schmanzy Newline Converter written in Tcl

Provided that you have tclsh installed properly, usage instructions like the following should be output
if you run the program without any arguments:

$ ./nlconv
usage: nlconv query [filelist]
    or nlconv [targetformat] [filelist]
where [targetformat] is one of cr, crlf, or lf
$ 

Why?
===

I wanted to learn Tcl and thought that the large proliferation of dos2unix, unix2dos, etc. didn't serve
all of my requirements, as I didn't find anything to deal with old MacOS style CR newlines. Also,
Tcl has a very, very forgiving attitude toward mixing styles of newlines in the routines I used
from it.

--
Andrew D. Ball
anball at gmail.com
