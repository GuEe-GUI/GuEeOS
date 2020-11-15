# GuEeOS

<img src="https://img.shields.io/badge/build-passing-brightgreen.svg" alt="Build Status"/>&nbsp;<img src="https://img.shields.io/badge/license-GPL%203.0-blue.svg" alt="License"/>&nbsp;<img src="https://img.shields.io/badge/version-0.0.1-blue.svg" alt="Version"/>&nbsp;[![GuEeOS](https://badgen.net/github/stars/guee-gui/GuEeOS)](https://github.com/GuEe-GUI/GuEeOS/)

__A 64-bit Operating System. It's open source, just do it!__

__E-mail: geeesgui@gmail.com / 2991707448@qq.com__

## Build Tools
* C/CPP elf Tools `>4.6`
    * x86-64
        * Windows Tools: you can get a releases by `lordmilko` [i686-elf-tools](https://github.com/lordmilko/i686-elf-tools/releases)
        * Unix/Linux Tools: install `x86_64-elf-gcc` in your terminal.
    * arm64
        * Windows Tools: [arm-elf-gcc](https://developer.arm.com/tools-and-software/open-source-software/developer-tools/gnu-toolchain/gnu-a/downloads)
        * Unix/Linux Tools: install `arm-elf-gcc` in your terminal.
    * riscv64
        * Windows/Unix/Linux Tools: [riscv-gnu-toolchain](https://github.com/riscv/riscv-gnu-toolchain), compile it by yourself

* Assembly Tools:
    * Nasm
        You can get it from [here](https://nasm.us/)
    * AT&T
        You can get it in `C/CPP elf Tools`

* Package Tools
    * genisoimage
        * Windows Tools: I compile it in CygWin for [Windows](https://github.com/GuEe-GUI/GuEe-Dev-Tools/tree/main/genisoimage);
        * Unix/Linux Tools: Install `genisoimage` in your terminal.
    * mkfs.dos
        * Windows Tools: With no all features, It's just simulate command for [Windows](https://github.com/GuEe-GUI/GuEe-Dev-Tools/blob/main/mkfs.msdos.exe);
        * Unix/Linux Tools: Install `mkfs` in your terminal.
    * mtools
        * Windows Tools: I compile it in CygWin for [Windows](https://github.com/GuEe-GUI/GuEe-Dev-Tools/tree/main/mtools);
        * Unix/Linux Tools: Install `mkfs` in your terminal.
    * grub
        * Windows Tools: You can get Release from [here](https://github.com/GuEe-GUI/GuEe-Dev-Tools/tree/main/grub);
        * Unix/Linux Tools: By this [document](https://www.gnu.org/software/grub/manual/grub/grub.html)

* Virtual Machine
    * [Qemu](https://www.qemu.org/) (Default in GuEeOS Dev)
    * [VirtualBox](https://www.virtualbox.org/)
    * [Bochs](http://bochs.sourceforge.net/)
    * [VMware](https://www.vmware.com/)

**Tip**: You can Dev in `CygWin` for Windows, and install these tools like Unix/Linux;

```C
#include <stdio.h>

int main(int argc, char **argv) {
    printf("Hello World!");
    return 0;
}
```

#### 前人栽树，后人乘凉。感谢前人的贡献能帮助到我们，也希望我能继续帮助到后续来者。
#### The predecessors planted trees, and the descendants took the cold. Thanks to the contributions of the predecessors can help us, and I hope that I can continue to help followers.
