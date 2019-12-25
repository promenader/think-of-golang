# 第一章 入门

本章节从Go语言最基本的安装、配置开始介绍，并且详细分析了一个代码示例，希望帮助读者能快速了解Go语言。

## 1.1 Go编译器安装

Go语言支持多个操作系统，可以从https://studygolang.com/dl官方网站上下载对应系统的二进制文件安装。

## 1.2 环境配置

* GOROOT

    Go编译器的安装路径，该路径下包含Go编译器和一些有用的工具
* GOPATH
    
    该路径是自定义的，用于存放自己开发的工程项目
    

### 1.3 入门示例

让我们从helloworld开始


```go
package main

import "fmt"

func main() {
	fmt.Println("Hello, 世界")
}
```

首先创建一个hello.go的文件(Golang的源文件默认以.go结尾)，