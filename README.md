# VB6_StringBuilder
VB 6 String Builder Class

======================================================================================
Name:     vbAccelerator cStringBuilder
Author:   Steve McMahon (steve@vbaccelerator.com)
Date:     1 January 2002

Copyright © 2002 Steve McMahon for vbAccelerator
--------------------------------------------------------------------------------------
Visit vbAccelerator - advanced free source code for VB programmers
http://vbaccelerator.com
--------------------------------------------------------------------------------------

VB can be slow to append strings together because of the continual
reallocation of string size.  This class pre-allocates a string in
blocks and hence removes the performance restriction.

Quicker insert and remove is also possible since string space does
not have to be reallocated.

Example:
Adding "http://vbaccelerator.com/" 10,000 times to a string:
Standard VB:   34s
This Class:    0.35s

======================================================================================
