# MYTestTinySTL
这是仿照SGI STL以及侯捷STL源码解析的STL库

## 支持

* 操作系统
  * linux
  * windows
  * osx
* 编译器
  * g++ 5.4 或以上
  * clang++ 3.5 或以上
  * msvc 14.0 或以上

## 需要
  * 使用 cmake 2.8 来构建项目（**可选**）

## 运行

如果你想要运行测试，请先阅读 [这个](https://github.com/Alinshans/MyTinySTL/blob/master/Test/README.md) 。

  * gcc/clang on linux/osx
  1. 克隆仓库
```bash
$ git clone git@github.com:Alinshans/MyTinySTL.git
$ cd MyTinySTL
```
  2. 构建并运行
```bash
$ mkdir build && cd build
$ cmake ..
$ make
$ cd ../bin && ./stltest
```

  * msvc on windows
  1. 克隆仓库或 [Download ZIP](https://github.com/Alinshans/MyTinySTL/archive/master.zip)
  2. 使用 `vs2015`（或 `vs2017`）打开 `MSVC/MyTinySTL_VS2015.sln`，配置成 `Release` 模式，（Ctrl + F5）开始执行。
  
## 文档
  见 [Wiki](https://github.com/Alinshans/MyTinySTL/wiki)。

## 测试
  见 [Test](https://github.com/Alinshans/MyTinySTL/tree/master/Test)。

---

SGI-STL V3.3 源代码的学习
SGI-STL V3.3(源代码)

STL 标准头文件(无扩展名)，例如 vector，deque，list...
C++ Standard 定案前，HP 规范的 STL 头文件(扩展名 .h)
SGI STL 内部私用文件(SGI STL 真正实现于此)
The Annotated STL Sources V3.3(学习源代码的注释)

容器 (container) ：序列式容器 (sequence container) 和 关联式容器 (associattive container)
算法 (algorithm)
迭代器 (iterator)
仿函数或函数对象 (functor / function object)
配接器(adapter)
配置器(allocator)
SGI-STL Test(代码测试)

Code Test
GCC 编译器
SGI STL 被归纳到 GNU C++ 标准程序库中，例如 gcc 使用 4.8.4 版本，STL源码 在 Linux 系统的位置是：/usr/include/c++/4.8.4/bits。
