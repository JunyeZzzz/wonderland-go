# wonderland-go

`wonderland-go` 是一个 Go 项目，目前处于初始化阶段。功能说明、安装步骤和使用示例会在首批代码提交后补充。

## 当前状态

仓库尚未包含 Go 源码或 `go.mod`，因此暂时没有可运行的程序或公开 API。

## 获取代码

```bash
git clone https://github.com/JunyeZzzz/wonderland-go.git
cd wonderland-go
```

## 开发约定

添加 Go 代码时，请使用 `github.com/JunyeZzzz/wonderland-go` 作为模块路径，并在 `go.mod` 中声明所需的 Go 版本。提交前建议运行：

```bash
go fmt ./...
go mod tidy
go test ./...
go vet ./...
```

这些命令需要在模块和源代码添加后运行。新增功能应同时提供必要的测试和使用说明。

## 参与贡献

欢迎通过 Issue 讨论问题或建议，也欢迎提交 Pull Request。请在变更说明中写明目的、主要改动和验证方式。

## 许可证

当前仓库尚未添加许可证。代码复用和分发条件将在许可证文件添加后明确。
