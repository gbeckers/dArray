Release notes
=============

Version 0.2.2
-------------
- fixed bug that sometimes wouldn't allow for deleting a file on Windows
  because of a Windows timing issue
- add more tests
- create conda-forge package


Version 0.2.1
-------------
- fixed bug checking file consistency for very large files


Version 0.2.0
--------------
- improved the ability to work with multiple references to same array
- implement truncate ragged array
- remove 'view' method as it created problems on Windows
- added 'open' method to partially replace view
- fixed truncate bug that sometimes occurred in Windows
- improved explanation in array README
- better documentation of ragged arrays
- refactoring code into more, smaller modules


Version 0.1.11
--------------
- fixed bugs in read code generation Matlab
- removed dependency on numpy.testing (was giving problems with pytest and
  numpy 1.15)
- iterappend for ragged arrays (not optimally efficient yet)

Version 0.1.10
--------------
- cleaned up checksum handling
- refactored handling read code for other languages
- read code for ragged arrays (experimental)
- improved ragged arrays (experimental)

Version 0.1.9
-------------
- archive and compress darr objects

Version 0.1.8
-------------
- create and open arbitrary (non-protected) files in darr array directory
- export darr to `zarr <https://github.com/zarr-developers/zarr>`__
- asarray works on zarr arrays more efficiently
- added support for Maple
- removed set_accessmode method, now set accessmode attribute directly

Version 0.1.7
-------------
License file included, necessary for conda-forge

Version 0.1.6
-------------
More tests and documentation

Version 0.1.3
-------------
Fixed delete bug array list

Version 0.1.2
-------------
Fixed truncate bug on Windows