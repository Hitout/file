workspace->package->go



1. `go run helloworld.go`
2. `go build helloworld.go`生成可执行二进制文件（windows下为exe）
3. 原生支持Unicode，它可以处理全世界任何语言的文本

#### 数组

`var a [3]int`或者`q := [...]int{1, 2, 3}`(`...`表示数组长度根据初始化的个数计算)

#### Slice

- slice的底层引用一个数组对象，由三个部分构成：指针、长度和容量
- `s := []int{}`或者`make([]T, len, cap)`
- 成倍扩容

#### Map

类似于Java语言中的HashMap

`if age, ok := ages["bob"]; !ok { /* ... */ }`