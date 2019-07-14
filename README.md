# acrux-patchset
================

Linux kernel v5.1 patches including additional features:

- Genpatches Base and Extra v5.2-1 (Gentoo linux-patches [infopage](http://dev.gentoo.org/~mpagano/genpatches/) or [repository](https://gitweb.gentoo.org/proj/linux-patches.git))
- Additional CPU optimization options (kernel_gcc_patch [repository](https://github.com/graysky2/kernel_gcc_patch))
- Support for ZSTD compression of kernel and initramfs ([website](http://facebook.github.io/zstd/) or [repository](https://github.com/facebook/zstd))
- Silence AMD PowerPlay debug messages
- BTRFS: don't compress if NODATASUM or NODATACOW set ([patch](https://patchwork.kernel.org/patch/11024843/))

These patches can be applied directly on top of the vanilla Linux kernel version [5.2.1](https://cdn.kernel.org/pub/linux/kernel/v5.x/linux-5.2.1.tar.xz).
