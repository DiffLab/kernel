### makefiles


#### 0001-init-add-support-for-zstd-compressed-modules.patch
***
This patch adds compression of modules in .zstd format and you need to use [this](https://raw.githubusercontent.com/DiffLab/system/master/mkinitcpio/0001-Add-zstd-module-decompression.patch) patch to use it. You probably use .xz compression by default so don't forget to change this when compiling the kernel. 
Remember also to use the developmental version of [kmod](https://git.kernel.org/pub/scm/utils/kernel/kmod/kmod.git/), because stable does not have adequate solutions.
***
