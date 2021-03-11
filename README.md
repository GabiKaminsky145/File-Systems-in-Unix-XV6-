﻿# File-Systems-in-Unix-XV6-

This version of XV6 includes an implementation of exceeding the file size system on Xv6, and also added support to Symbolic links.

The original XV6 only supports one-level indirect links in the i-node object, therefore the maximum size of a file is 70KB.
In this assignment, we extend the i-node to support double indirect and therefore the system can handle file size up to 8MB.

Also, XV6 only supports a hard link mechanism, the basic Unix system also provides a symbolic link mechanism. This version was extended to support symbolic links and hard links.
