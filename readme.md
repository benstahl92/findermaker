### FinderMaker ###

Ported to Python 3 by Benjamin Stahl, July 2019

Installation note: this requires an old version of aplpy. Use the following command to make sure you have a suitable version:
```
pip install "aplpy<2"
```

Usage is identical the example below. Use the original repo (not this fork) for Python 2 compatibility.

*Isaac Shivvers,
July 2014,
ishivvers@berkeley.edu*

This is an interactive Python code to create nice finder charts
 with offset stars.  To use this, you need a fits image with
 your object clearly detected or the (accurate!) coordinates
 of your object.


Example:
```
    ipython --pylab
    from findermaker import FinderMaker
    F = FinderMaker( ra='09 55 42.14', dec='+69 40 26.0', name='SN 2014J' )
```
