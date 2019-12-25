# 简单示例

## Go编译器安装

Go语言支持多个操作系统，可以从https://studygolang.com/dl官方网站上下载对应系统的二进制文件安装。

## 环境配置

* GOROOT

    Go编译器的安装路径，该路径下包含Go编译器和一些有用的工具
* GOPATH
    
    该路径是自定义的，用于存放自己开发的工程项目
    

### HelloWorld

```go
package main

import "fmt"

func main() {
	fmt.Println("Hello, 世界")
}
```
