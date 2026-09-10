# sealed-secrets

[English version](./README.md)

A Kubernetes controller and tool for one-way encrypted Secrets

![sealed-secrets](https://repo.x-cmd.io/sealed-secrets.svg?lang=zh)

## 安装

```sh
x install sealed-secrets
```

## 代码洞察

合计: **16,714** 行代码（覆盖前 5 种语言、共 **134** 个文件）。

| 语言 | 代码 | 注释 | 空行 | 文件数 |
|------|-----:|-----:|-----:|------:|
| Go | 8,724 | 813 | 1,490 | 63 |
| Yaml | 2,320 | 400 | 31 | 32 |
| Jsonnet | 1,514 | 208 | 189 | 23 |
| Json | 1,405 | 0 | 0 | 9 |
| Sass | 1,202 | 4 | 44 | 7 |

## OpenSSF Scorecard 评分

总评分: **6.8 / 10**

评分最低的几项:

- **Token-Permissions** (0/10) — detected GitHub workflow tokens with excessive permissions
- **Fuzzing** (0/10) — project is not fuzzed
- **CII-Best-Practices** (0/10) — no effort to earn an OpenSSF best practices badge detected

## 源代码

- **上游仓库**: <https://github.com/bitnami-labs/sealed-secrets>
- **许可证**: Apache-2.0

## 发布

- **最新版本**: `helm-v2.20.0` (2026-09-10)
- **最近提交**: 2026-09-10
- **Release 含资产**: 19 个

## 流行度

- **Star**: 9,286 · **Fork**: 775 · **开放 issue**: 607 · **贡献者**: 183

## 累计统计

- **发布数**: 204 · **已合并 PR**: 1153 · **开放 PR**: 1 · **已关闭 issue**: 542 · **开放 issue**: 65 · **提交数**: 1684

## 最近活动

| 时间窗口 | 起始 | 发布 | 已合并 PR | 开放 PR | 已关闭 issue | 开放 issue | 提交 |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-11 | 6 | 0 | 0 | 0 | 0 | 0 |
| last60d | 2026-07-12 | 6 | 0 | 0 | 0 | 0 | 0 |
| 90d | 2026-06-12 | 13 | 0 | 0 | 0 | 0 | 0 |
| last180d | 2026-03-14 | 21 | 0 | 0 | 0 | 0 | 0 |
| 360d | 2025-09-15 | 36 | 0 | 0 | 0 | 0 | 0 |
| last720d | 2024-09-20 | 52 | 0 | 0 | 0 | 0 | 0 |

## Release 资产

| 资产 | 大小 | 目标平台 |
|------|-----:|----------|
| [controller-norbac.yaml](https://github.com/bitnami-labs/sealed-secrets/releases/download/v0.40.0/controller-norbac.yaml) | 8.5 KiB | `other` |
| [controller.yaml](https://github.com/bitnami-labs/sealed-secrets/releases/download/v0.40.0/controller.yaml) | 11.2 KiB | `other` |
| [cosign.pub](https://github.com/bitnami-labs/sealed-secrets/releases/download/v0.40.0/cosign.pub) | 178 B | `other` |
| [kubeseal-0.40.0-darwin-amd64.tar.gz](https://github.com/bitnami-labs/sealed-secrets/releases/download/v0.40.0/kubeseal-0.40.0-darwin-amd64.tar.gz) | 24.1 MiB | `native/darwin/x64` |
| [kubeseal-0.40.0-darwin-amd64.tar.gz.sig](https://github.com/bitnami-labs/sealed-secrets/releases/download/v0.40.0/kubeseal-0.40.0-darwin-amd64.tar.gz.sig) | 96 B | `native/darwin/x64` |
| [kubeseal-0.40.0-darwin-arm64.tar.gz](https://github.com/bitnami-labs/sealed-secrets/releases/download/v0.40.0/kubeseal-0.40.0-darwin-arm64.tar.gz) | 22.4 MiB | `native/darwin/arm64` |
| [kubeseal-0.40.0-darwin-arm64.tar.gz.sig](https://github.com/bitnami-labs/sealed-secrets/releases/download/v0.40.0/kubeseal-0.40.0-darwin-arm64.tar.gz.sig) | 96 B | `native/darwin/arm64` |
| [kubeseal-0.40.0-linux-amd64.tar.gz](https://github.com/bitnami-labs/sealed-secrets/releases/download/v0.40.0/kubeseal-0.40.0-linux-amd64.tar.gz) | 22.7 MiB | `native/linux/x64` |
| [kubeseal-0.40.0-linux-amd64.tar.gz.sig](https://github.com/bitnami-labs/sealed-secrets/releases/download/v0.40.0/kubeseal-0.40.0-linux-amd64.tar.gz.sig) | 96 B | `native/linux/x64` |
| [kubeseal-0.40.0-linux-arm.tar.gz](https://github.com/bitnami-labs/sealed-secrets/releases/download/v0.40.0/kubeseal-0.40.0-linux-arm.tar.gz) | 21.3 MiB | `native/linux/arm` |
| [kubeseal-0.40.0-linux-arm.tar.gz.sig](https://github.com/bitnami-labs/sealed-secrets/releases/download/v0.40.0/kubeseal-0.40.0-linux-arm.tar.gz.sig) | 96 B | `native/linux/arm` |
| [kubeseal-0.40.0-linux-arm64.tar.gz](https://github.com/bitnami-labs/sealed-secrets/releases/download/v0.40.0/kubeseal-0.40.0-linux-arm64.tar.gz) | 20.6 MiB | `native/linux/arm64` |
| [kubeseal-0.40.0-linux-arm64.tar.gz.sig](https://github.com/bitnami-labs/sealed-secrets/releases/download/v0.40.0/kubeseal-0.40.0-linux-arm64.tar.gz.sig) | 96 B | `native/linux/arm64` |
| [kubeseal-0.40.0-linux-ppc64le.tar.gz](https://github.com/bitnami-labs/sealed-secrets/releases/download/v0.40.0/kubeseal-0.40.0-linux-ppc64le.tar.gz) | 20.7 MiB | `native/unknown` |
| [kubeseal-0.40.0-linux-ppc64le.tar.gz.sig](https://github.com/bitnami-labs/sealed-secrets/releases/download/v0.40.0/kubeseal-0.40.0-linux-ppc64le.tar.gz.sig) | 96 B | `other` |
| [kubeseal-0.40.0-windows-amd64.tar.gz](https://github.com/bitnami-labs/sealed-secrets/releases/download/v0.40.0/kubeseal-0.40.0-windows-amd64.tar.gz) | 23.1 MiB | `native/win/x64` |
| [kubeseal-0.40.0-windows-amd64.tar.gz.sig](https://github.com/bitnami-labs/sealed-secrets/releases/download/v0.40.0/kubeseal-0.40.0-windows-amd64.tar.gz.sig) | 96 B | `native/win/x64` |
| [sealed-secrets_0.40.0_checksums.txt](https://github.com/bitnami-labs/sealed-secrets/releases/download/v0.40.0/sealed-secrets_0.40.0_checksums.txt) | 711 B | `other` |
| [sealed-secrets_0.40.0_checksums.txt.sig](https://github.com/bitnami-labs/sealed-secrets/releases/download/v0.40.0/sealed-secrets_0.40.0_checksums.txt.sig) | 96 B | `other` |

## 改进这些数据

sealed-secrets 的安装元数据由 [x-cmd/install](https://github.com/x-cmd/install) 索引维护——这是一份由 x-cmd 在安装时读取的精选 YAML 包列表。如果 `sealed-secrets` 缺失、过期，或安装行为有问题，欢迎在该 repo 提 issue 或 PR：

- **提交 issue**: <https://github.com/x-cmd/install/issues/new>
- **编辑包条目**: <https://github.com/x-cmd/install/edit/main/sealed-secrets.yml>（或索引实际使用的路径）

本页面的数据（card / loc / scorecard / release）由 [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) 自动采集，每日重新生成。**安装行为**（版本选择、平台差异、依赖处理）的改进应提交到上游索引。

_数据快照: `data/card/260910.yml` · 2026-09-10T22:33:13Z._
