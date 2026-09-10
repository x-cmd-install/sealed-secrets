# sealed-secrets

[中文版本](./README.cn.md)

A Kubernetes controller and tool for one-way encrypted Secrets

![sealed-secrets](https://repo.x-cmd.io/sealed-secrets.svg)

## Install

```sh
x install sealed-secrets
```

## Code insight

Total: **16,714** lines of code across **134** files in the top 5 languages.

| Language | Code | Comments | Blanks | Files |
|----------|-----:|---------:|-------:|------:|
| Go | 8,724 | 813 | 1,490 | 63 |
| Yaml | 2,320 | 400 | 31 | 32 |
| Jsonnet | 1,514 | 208 | 189 | 23 |
| Json | 1,405 | 0 | 0 | 9 |
| Sass | 1,202 | 4 | 44 | 7 |

## OpenSSF Scorecard

Overall score: **6.8 / 10**

Lowest-scoring checks:

- **Token-Permissions** (0/10) — detected GitHub workflow tokens with excessive permissions
- **Fuzzing** (0/10) — project is not fuzzed
- **CII-Best-Practices** (0/10) — no effort to earn an OpenSSF best practices badge detected

## Source

- **Upstream**: <https://github.com/bitnami-labs/sealed-secrets>
- **License**: Apache-2.0

## Release

- **Latest**: `helm-v2.20.0` (2026-09-10)
- **Last commit**: 2026-09-10
- **Assets in release**: 19

## Popularity

- **Stars**: 9,286 · **Forks**: 775 · **Open issues**: 607 · **Contributors**: 183

## Totals (cumulative)

- **Releases**: 204 · **Merged PRs**: 1153 · **Open PRs**: 1 · **Closed issues**: 542 · **Open issues**: 65 · **Commits**: 1684

## Recent activity

| Window | Since | Releases | Merged PRs | Open PRs | Closed issues | Open issues | Commits |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-11 | 6 | 0 | 0 | 0 | 0 | 0 |
| last60d | 2026-07-12 | 6 | 0 | 0 | 0 | 0 | 0 |
| 90d | 2026-06-12 | 13 | 0 | 0 | 0 | 0 | 0 |
| last180d | 2026-03-14 | 21 | 0 | 0 | 0 | 0 | 0 |
| 360d | 2025-09-15 | 36 | 0 | 0 | 0 | 0 | 0 |
| last720d | 2024-09-20 | 52 | 0 | 0 | 0 | 0 | 0 |

## Release assets

| Asset | Size | Target |
|-------|-----:|--------|
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

## Improve this data

Install metadata for sealed-secrets lives in the [x-cmd/install](https://github.com/x-cmd/install) index — a curated YAML package list that x-cmd consumes at install time. If `sealed-secrets` is missing, out of date, or installs incorrectly, please open an issue or PR there:

- **Open an issue**: <https://github.com/x-cmd/install/issues/new>
- **Edit the package entry**: <https://github.com/x-cmd/install/edit/main/sealed-secrets.yml> (or whichever path the index uses)

The data on this page (card / loc / scorecard / release) is auto-collected by [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) and is regenerated daily. Improvements to *install behaviour* (which version gets installed, platform-specific quirks, dependencies) belong upstream in the index.

_Snapshot: `data/card/260910.yml` · 2026-09-10T22:33:12Z._
