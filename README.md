# Aleo Exporter

`aleo_exporter` 是一个用 Go 编写的 Prometheus Exporter，用于监控 Aleo 节点日志中的关键指标。

## 特性

- 实时解析 Aleo 日志
- 暴露 Prometheus 指标
- 轻量高效

## 安装

```bash
git clone https://github.com/beck-8/aleo_exporter
cd aleo_exporter
go build
```

## 使用

```bash
./aleo_exporter --log.path /path/to/aleo.log --web.listen-address ":8080"
```

## 配置

- `--log.path`：指定 Aleo 日志文件路径
- `--web.listen-address`：指定 Exporter 的监听地址

## 贡献

欢迎提交 Issue 和 Pull Request。
