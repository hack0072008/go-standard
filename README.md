# go-standard 
![Go](testdata/img/go.png)

Go标准库所有使用方法例子，请注意这不是Go的中文版标准库

欢迎各位Gopher补充一些高级用法以及组合用法，在对应的包下创建extend文件夹，在extend文件夹下创建一个自己的example文件夹(必须包含example.go用于示例模拟调用, doc.go用于示例说明)，感谢！

## 安装
```
go get github.com/zc2638/gosl
```
启动服务
```
gosl web
```

## Go Module代理
设置环境变量(推荐)
```
GOPROXY=https://proxy.golang.org
```
或
```
GOPROXY=https://goproxy.io
```

## 简介

- [**archive**](https://github.com/zc2638/go-standard/tree/master/src/archive) &emsp;&emsp;&emsp;&emsp; tar/zip压缩操作
- [**bufio**](https://github.com/zc2638/go-standard/tree/master/src/bufio) &emsp;&emsp;&emsp;&emsp;&emsp; 有缓冲的I/O
- [**bytes**](https://github.com/zc2638/go-standard/tree/master/src/bytes) &emsp;&emsp;&emsp;&emsp;&emsp; 操作[]byte字节片
- [**compress**](https://github.com/zc2638/go-standard/tree/master/src/compress) &emsp;&emsp;&emsp; bzip2/flate/gzip/lzw/zlib压缩操作
- [**container**](https://github.com/zc2638/go-standard/tree/master/src/container) &emsp;&emsp;&emsp;&ensp;堆操作/双向链表/环形链表
- [**context**](https://github.com/zc2638/go-standard/tree/master/src/context) &emsp;&emsp;&emsp;&emsp;&nbsp;上下文类型
- [**crypto**](https://github.com/zc2638/go-standard/tree/master/src/crypto) &emsp;&emsp;&emsp;&emsp;&emsp;常用的密码（算法）
- [**database/sql**](https://github.com/zc2638/go-standard/tree/master/src/database/sql) &emsp;&emsp;数据库接口
- [**encoding**](https://github.com/zc2638/go-standard/tree/master/src/encoding) &emsp;&emsp;&emsp;&emsp;数据编码
- [**errors**](https://github.com/zc2638/go-standard/tree/master/src/errors) &emsp;&emsp;&emsp;&emsp;&emsp; 创建错误函数
- [**expvar**](https://github.com/zc2638/go-standard/tree/master/src/expvar) &emsp;&emsp;&emsp;&emsp;&emsp;公共变量
- [**flag**](https://github.com/zc2638/go-standard/tree/master/src/flag) &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&ensp;命令行参数解析
- [**fmt**](https://github.com/zc2638/go-standard/tree/master/src/fmt) &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&ensp; 格式化I/O
- [**go**](https://github.com/zc2638/go-standard/tree/master/src/go) &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;GO常用命令
- [**hash**](https://github.com/zc2638/go-standard/tree/master/src/hash) &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;提供hash函数的接口
- [**html**](https://github.com/zc2638/go-standard/tree/master/src/html) &emsp;&emsp;&emsp;&emsp;&emsp;&emsp; 转义和解转义HTML文本
- [**image**](https://github.com/zc2638/go-standard/tree/master/src/image) &emsp;&emsp;&emsp;&emsp;&emsp;&ensp;实现了基本的2D图片库
- [**index/suffixarray**](https://github.com/zc2638/go-standard/tree/master/src/index/suffixarray) &ensp;使用内存后缀数组以对数时间实现子字符串搜索
- [**io**](https://github.com/zc2638/go-standard/tree/master/io) &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&ensp; I/O操作
- [**log**](https://github.com/zc2638/go-standard/tree/master/src/log) &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;简单的日志服务
- [**math**](https://github.com/zc2638/go-standard/tree/master/src/math) &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;基本的数学常数和数学函数
- [**mime**](https://github.com/zc2638/go-standard/tree/master/src/mime) &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;实现了MIME的部分规定
- [**net**](https://github.com/zc2638/go-standard/tree/master/src/net) &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;提供了可移植的网络I/O接口，包括TCP/IP、UDP、域名解析和Unix域socket
- [**os**](https://github.com/zc2638/go-standard/tree/master/src/os) &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp; 操作系统函数
- [**path**](https://github.com/zc2638/go-standard/tree/master/src/path) &emsp;&emsp;&emsp;&emsp;&emsp;&emsp; 对斜杠分隔的路径的实用操作
- [**plugin**](https://github.com/zc2638/go-standard/tree/master/src/plugin) &emsp;&emsp;&emsp;&emsp;&emsp; 插件生成和加载
- [**reflect**](https://github.com/zc2638/go-standard/tree/master/src/reflect) &emsp;&emsp;&emsp;&emsp;&emsp; 反射操作任意类型对象
- [**regexp**](https://github.com/zc2638/go-standard/tree/master/src/regexp) &emsp;&emsp;&emsp;&emsp;&emsp;正则表达式
- [**rutime**](https://github.com/zc2638/go-standard/tree/master/src/runtime) &emsp;&emsp;&emsp;&emsp;&emsp;&nbsp;提供和go运行时环境的互操作，如控制go程的函数
- [**sort**](https://github.com/zc2638/go-standard/tree/master/src/sort) &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&ensp;排序切片和用户自定义数据集
- [**strconv**](https://github.com/zc2638/go-standard/tree/master/src/strconv) &emsp;&emsp;&emsp;&emsp;&ensp; 基本数据类型和其字符串类型的相互转换
- [**strings**](https://github.com/zc2638/go-standard/tree/master/src/strings) &emsp;&emsp;&emsp;&emsp;&emsp;操作字符串
- [**sync**](https://github.com/zc2638/go-standard/tree/master/src/sync) &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;提供了基本的同步基元，如互斥锁
- [**text**](https://github.com/zc2638/go-standard/tree/master/src/text) &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&ensp;文本操作
- [**time**](https://github.com/zc2638/go-standard/tree/master/src/time) &emsp;&emsp;&emsp;&emsp;&emsp;&emsp; 时间操作
- [**unicode**](https://github.com/zc2638/go-standard/tree/master/src/unicode) &emsp;&emsp;&emsp;&emsp;&ensp;unicode操作
- [**unsafe**](https://github.com/zc2638/go-standard/tree/master/src/unsafe) &emsp;&emsp;&emsp;&emsp;&emsp;提供了一些跳过go语言类型安全限制的操作

### 参考

- [**中文版标准库文档**](https://studygolang.com/pkgdoc) | [**中文版标准库文档2**](http://www.php.cn/manual/view/35126.html)
- [**中文版标准库文档(Dash版)**](https://github.com/taigacute/GoDoc-CN)
- [**Mastering Go(玩转Go中文译本)**](https://github.com/hantmac/Mastering_Go_ZH_CN)
