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


编译运行了。来一堆命令先：

$ nasm -f elf first.asm -o first.o
$ gcc -m32 first.o -o first
这下，程序就编译好了，像这样：

$ ls
first  first.asm  first.o
好了我们运行一下：

$ ./first ; echo $?
