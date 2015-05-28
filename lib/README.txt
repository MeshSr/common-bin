These libraries are used by ofsoftware13(ofs-sw and ofs-hw)

Please copy all these *.so files(NOT the sub-folders) to the directory "/lib" in the ext4 filesystem

By using the following command:

find yourpath/common-bin/lib -name "lib*" | xargs -i cp {} /media/EXT/lib

NOTE:
"yourpath" is your local path that stores the repo images
"/media/EXT" is the mount point of ext4 partition of your TF/SD card

