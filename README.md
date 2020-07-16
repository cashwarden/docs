# Cashwarden API Docs

Cashwarden application and API documentation.


## 开发

修改 `main.go`，然后在 Linux 环境执行下面命令:

```sh
go build -o docs-cli-linux-amd64 main.go
```

## 使用

### 方式一

先按照 Golang 环境，然后：

```sh
go get gopkg.in/yaml.v2
go run main.go
```

### 方式二

适合 Linux 环境，直接运行：

```sh
chmod +x docs-cli-linux-amd64
./docs-cli-linux-amd64
```