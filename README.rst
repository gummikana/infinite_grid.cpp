infinite_grid.cpp
=================

infinite_grid.cpp is a small utility that does a templated 2 dimensional array that's "infinite".
By "infinite" it means it's of size -2147483648 to 2147483647 in both dimensions. It could easily
be modified to be a bit bigger since it's "wasting" about 7 bits at the moment. But I feel that's
big enough of a grid. 

I tried looking for a good example of how to do an infinite grid, but failed to find one. 

How it works
------------

infinite_grid dynamically creates a bunch of smaller 2d arrays (128 x 128 by default) based on the
coordinates of the cell that you're asking for. It puts these 2d arrays into a std::map sorted by
their coordinates. 


How to use this
---------------

Do what ever you feel with it. I highly recommend just hacking it.
 
Future
------

This will most likely be added to the poro framework. https://github.com/gummikana/poro
So the future versions and bug fixes are probably in the poro framework. Look in there
for a newer version. It's probably under utils/infinitegrid


License
-------

infinite_grid.cpp is provided under a MIT style license

