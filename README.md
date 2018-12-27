# python
* 1.运行python命令:
> python
* 2.退出Python交互式环境
> exit()
* 3.使用文本编辑器 运行Hello World
> print('hello, world)
> > 能不能像.exe文件那样直接运行.py文件呢？在Windows上是不行的，但是，在Mac和Linux上是可以的，方法是在.py文件的第一行加上一个特殊的注释：<br>#!/usr/bin/env python3 print('hello, world') <br> 然后，通过命令给hello.py以执行权限：<br>$ chmod a+x hello.py <br>./hello.py 
* 4.输出
> print()在括号中加上字符串，就可以向屏幕上输出指定的文字
> > 比如输出'hello, world'，用代码实现如下：<br>print('hello, world')
<br> print()函数也可以接受多个字符串，用逗号“,”隔开，就可以连成一串输出：
<br> print('The quick brown fox', 'jumps over', 'the lazy dog')
<br> The quick brown fox jumps over the lazy dog
<br> print()会依次打印每个字符串，遇到逗号“,”会输出一个空格，因此，输出的字符串是这样拼起来的.
