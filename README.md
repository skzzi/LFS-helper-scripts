# LFS-helper-scripts

While building LFS-12.1 I spent a lot of time mounting and umounting
partitions and virtual filesystems, and well as entering chroot.  It
became tedious so I taught myself just enough shell scripting to come
up with these three scripts.

mount-LFS   : Use this to mount you LFS partition(s) and the virtual
              filesystems.

chroot-LFS  : Use this to quickly chroot into your LFS build environment.

unmount-LFS : Use this to unmount the virtual filesystems and your
              LFS partition(s).


A more in depth description with warnings and such is forthcoming.
