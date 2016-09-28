unrarstream
=====

Adds a new option to wait for the next volume to appear. This is usefull when downloading a large rar archive that has been splitted into multiple parts.

If the next volume got found, the file size gets checked in the given interval until it doesn't change anymore.  
The default interval is 5 seconds.

command line option:  
-vap\<interval\> Wait for each volume to appear, check interval in seconds

This version preallocate drive space for extracted files in Unix. Without this modification media players are not able to play the partically extracted files.

Please have a look at the license.txt file for the UnRAR license.  
The modifications made in this repository are free to use without any restrictions.
