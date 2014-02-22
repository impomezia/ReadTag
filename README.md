ReadTag
=======

Simple program and NSIS plugin for reading Google Omaha tags.

[ApplyTag](https://github.com/impomezia/ApplyTag) can be used to add a tag in a signed exe file.

Dependencies
------------
- cmake >= 2.8

Compilation
-----------
	mkdir build
	cd build
	cmake .. -G "NMake Makefiles" -DCMAKE_BUILD_TYPE=MinSizeRel
	nmake