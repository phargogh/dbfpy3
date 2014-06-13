dbfpy3
======

Port of DBFPY to Python 3

The code contained in this repository was originally created by Jeff Kunce and
Hans Fiby for the viewing, editing and creation of DBF/dBase/xBase files.
The Python 2.x version of the package is available on the project's original
sourceforge page, dbfpy.sourceforge.com.  This package is a straight port of
dbfpy's original functionality to Python 3.x.

jjk  11/15/99
2000-10-06 Hans Fiby

I have used this code, in various forms, to read .dbf files.
It includes some experimental code to write to .dbf files.
This code may provide a starting point for others.

Files:
    dbf.py      reads (and possibly writes) .dbf file data directly from disk
    dbfload.py  reads an entire .dbf file into memory, provides access to data
    binnum.py   a module to decode/encode binary numbers
    strutil.py  a module of string utilities
    dbfnew.py   a module to create new .dbf files
    county.dbf  a sample .dbf file
    readme.txt  this file
    dbfpy.tgz   the distribution tarball

dbf.py and dbfload.py are independent ways to access .dbf files.

*** !!  USE AT YOUR OWN RISK    !! ***
*** !! NO WARRANTIES WHATSOEVER !! ***

Jeff Kunce <kuncej@mail.conservation.state.mo.us>
http://starship.python.net/crew/jjkunce/
Hans Fiby <hans@fiby.at>
http://www.fiby.at
