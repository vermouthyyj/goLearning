# Notes

## 快速开发入门

### 目录结构

goproject >> src >> gocode >> project01 >> main package

- `package.main` 文件所在的包是 main，在 go 中，每个文件都必须归属于一个包
- `import “fmt”` 包名 fmt，引入该包后，就可以使用 fmt 包的函数，比如，fmt.Println
- `func main() {}` func 是一个关键词，表示一个函数，main 是函数名，是一个主函数，即程序的入口
- `fmt.Println()` 调用 fmt 包的的函数

### Golang 执行流程分析

1. `go build` 生成可执行文件
2. 运行可执行文件
   (执行速度快)
   or
   对源代码直接执行`go run` 源码

#### 两个运行方式的区别

1. 可执行.exe 文件，拷贝到没有 go 开发环境的机器上，仍然可以运行，可执行文件很大因为包含程序运行依赖的库文件
2. go run 源代码需要 go 开发环境
