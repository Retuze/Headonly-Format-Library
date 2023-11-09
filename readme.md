# Headonly Format Library

## 介绍

Headonly Format 库是一个轻量级的、head-only 的 C++ 格式库，使用 C++11 标准实现。它提供了一种简单而灵活的方式来处理文本和数字的格式化输出。

## 功能

* 格式化输出：使用简单的语法和占位符，可以将文本和数字按照指定的格式进行输出。

## 用途

Headonly Format 库适用于以下用途：

* 在仅支持c++11的编译器上使用format

## 示例用法

以下是一个简单的示例，演示了如何使用 Headonly Format 库进行格式化输出：


```cpp
#include "format.h"
int main()
{
    std::string str = util::format("Hello, my name is {0}, and I am {1} years old","Limin",16);
    std::string str1 = util::format("float{0:.3f}", 3.100985);
    std::cout<<str<<std::endl;
    std::cout<<str1<<std::endl;
}
```
