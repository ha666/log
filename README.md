# log

#### 介绍
log

#### 引用包
```go
import (
	"gitee.com/ha666/log"
)
```

#### 写入控制台
```go
log.Init(&log.Config{
	Host:       host,
	Stdout:     true,
	IgnorePath: []string{`/\S+/v2-9[0-9\-]*/`},
})
```

#### 写入文件
```go
log.Init(&log.Config{
	Host:       host,
	Dir:        "/Users/ha666/test/v2-9/lass",
	IgnorePath: []string{`/\S+/v2-9[0-9\-]*/`},
})
```

#### 写日志
```go
log.Info("ajsdlf")
log.Info("ajsdf:%s", "abc")
log.Error("sajdf:%d", 234)
```
####
