# assembly

> assembly & 汇编

## C language `.c`

> C

## C Plus Plus `.cpp`

> C ++

## C Sharp `.cs`

> C#

https://www.w3schools.com/cs/

## Objective C `.oc`

> OC

https://www.runoob.com/ios/ios-objective-c.html

***

## 汇编语言

https://www.bilibili.com/video/av28132657

http://c.biancheng.net/view/3294.html

https://zhuanlan.zhihu.com/p/23618489


```sh
# 环境安装
$ brew install gcc nasm gcc-multilib -y
# $ sudo apt-get install gcc nasm vim gcc-multilib -y

# 重装 nasm
$ brew reinstall nasm

$ nasm -v
# NASM version 2.14.02 compiled on Dec 27 2018

$ gcc -v
# Configured with: --prefix=/Library/Developer/CommandLineTools/usr --with-gxx-include-dir=/Library/Developer/CommandLineTools/SDKs/MacOSX10.14.sdk/usr/include/c++/4.2.1
# Apple LLVM version 10.0.1 (clang-1001.0.46.4)
# Target: x86_64-apple-darwin18.7.0
# Thread model: posix
# InstalledDir: /Library/Developer/CommandLineTools/usr/bin

$ which nasm
# /usr/bin/nasm

$ which gcc
# /usr/bin/gcc

```

```sh
# 编译
# abc.asm => abc.o
$ nasm -f elf abc.asm -o abc.o
# abc.o => abc
$ gcc -m32 abc.o -o abc

# 查看编译后的文件
$ ls -al
# abc abc.o abc.asm

# 运行
$ ./abc ; echo $?

```
