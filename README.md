# docker/docker-install

本仓库只为学习 Docker 官方安装脚本，不做安装使用

---

脚本在线地址在 `get.docker.com` 和 `test.docker.com`!

此安装脚本的目的是为了方便快速地安装最新的Docker-CE版本在支持的Linux发行版。
我们不建议依赖这个脚本来部署到生产系统。
更多关于在支持的发行版上安装的更详细说明，
请参见[安装说明](https://docs.docker.com/engine/install/)。

本仓库由Docker公司全权维护。

## 使用方法

使用 `https://get.docker.com`:

```shell
curl -fsSL https://get.docker.com -o get-docker.sh
sh get-docker.sh
```

使用 `https://test.docker.com`:

```shell
curl -fsSL https://test.docker.com -o test-docker.sh
sh test-docker.sh
```

从本仓库安装：

```shell
sh install.sh
```

## 测试

为了验证安装脚本是否在支持的操作系统中工作，请运行：

```shell
make shellcheck
```

make shellcheck 用于在 Makefile 构建系统中运行 shellcheck 工具。这个工具用于对 Shell 脚本进行静态分析，以发现可能的问题和错误。

## 法律

*由我们的法律顾问提供给你。欲了解更多情况、请参阅本程序包中的[NOTICE](NOTICE)文件*。

Docker的使用和转让可能会受到美国和其他政府的某些限制。
使用和转让Docker可能会受到美国和其他政府的某些限制。

你有责任确保你的使用和/或转让不会违反适用的法律。

欲了解更多信息，请参见https://www.bis.doc.gov

## 报告安全问题

维护者认真对待安全问题。如果你发现一个安全问题、
请立即提请他们注意!

请不要公开问题，而是将您的报告私下发送给
[security@docker.com](mailto:security@docker.com)。

我们非常感谢你的安全报告，我们会公开感谢你。
我们也喜欢送礼物--如果你喜欢Docker的礼品，请务必让我们知道。
让我们知道。我们目前不提供付费的安全赏金计划，但不排除在未来
但不排除将来会有这种做法。

## 许可

docker/docker-install采用Apache许可证2.0版进行许可。
参见[LICENSE](LICENSE)获取完整的许可证文本。
