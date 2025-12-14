gmake LLVM=1 menuconfig

gmake LLVM=1 -j8


gmake ARCH=arm64 LLVM=1 HOSTCFLAGS="-Imac/ -I $(brew --prefix libelf)/include" -j8 Image

[Building Linux kernel on macOS natively](https://seiya.me/blog/building-linux-on-macos-natively)

use gmake not make

gmake LLVM=1 menuconfig

you can reference this blog to complie linux in mac

https://seiya.me/blog/building-linux-on-macos-natively
