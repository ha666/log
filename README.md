# log

#### 介绍
log

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
