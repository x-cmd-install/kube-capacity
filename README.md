# kube-capacity

[中文版本](./README.cn.md)

A simple CLI that provides an overview of the resource requests, limits, and utilization in a Kubernetes cluster

![kube-capacity](https://repo.x-cmd.io/kube-capacity.svg)

## Install

```sh
x install kube-capacity
```

## Code insight

Total: **2,200** lines of code across **18** files in the top 5 languages.

| Language | Code | Comments | Blanks | Files |
|----------|-----:|---------:|-------:|------:|
| Go | 2,179 | 225 | 291 | 16 |
| Makefile | 21 | 3 | 6 | 1 |
| Markdown | 0 | 177 | 49 | 1 |

## OpenSSF Scorecard

Overall score: **4.1 / 10**

Lowest-scoring checks:

- **Maintained** (0/10) — 0 commit(s) and 0 issue activity found in the last 90 days -- score normalized to 0
- **Token-Permissions** (0/10) — detected GitHub workflow tokens with excessive permissions
- **Pinned-Dependencies** (0/10) — dependency not pinned by hash detected -- score normalized to 0

## Source

- **Upstream**: <https://github.com/robscott/kube-capacity>
- **License**: Apache-2.0

## Release

- **Latest**: `v0.8.0` (2024-02-21)
- **Last commit**: 2025-08-18
- **Assets in release**: 9

## Popularity

- **Stars**: 2,667 · **Forks**: 133 · **Open issues**: 77 · **Contributors**: 26

## Totals (cumulative)

- **Releases**: 31 · **Merged PRs**: 73 · **Open PRs**: 14 · **Closed issues**: 40 · **Open issues**: 37 · **Commits**: 134

## Recent activity

| Window | Since | Releases | Merged PRs | Open PRs | Closed issues | Open issues | Commits |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-11 | 0 | 0 | 1 | 0 | 0 | 0 |
| last60d | 2026-07-12 | 0 | 0 | 1 | 0 | 0 | 0 |
| 90d | 2026-06-12 | 0 | 0 | 1 | 0 | 0 | 0 |
| last180d | 2026-03-14 | 0 | 0 | 4 | 1 | 0 | 0 |
| 360d | 2025-09-15 | 0 | 0 | 8 | 1 | 3 | 0 |
| last720d | 2024-09-20 | 0 | 13 | 14 | 1 | 9 | 24 |

## Release assets

| Asset | Size | Target |
|-------|-----:|--------|
| [checksums.txt](https://github.com/robscott/kube-capacity/releases/download/v0.8.0/checksums.txt) | 848 B | `other` |
| [kube-capacity_v0.8.0_darwin_arm64.tar.gz](https://github.com/robscott/kube-capacity/releases/download/v0.8.0/kube-capacity_v0.8.0_darwin_arm64.tar.gz) | 10.8 MiB | `native/darwin/arm64` |
| [kube-capacity_v0.8.0_darwin_x86_64.tar.gz](https://github.com/robscott/kube-capacity/releases/download/v0.8.0/kube-capacity_v0.8.0_darwin_x86_64.tar.gz) | 11.3 MiB | `native/darwin/x64` |
| [kube-capacity_v0.8.0_linux_arm64.tar.gz](https://github.com/robscott/kube-capacity/releases/download/v0.8.0/kube-capacity_v0.8.0_linux_arm64.tar.gz) | 9.7 MiB | `native/linux/arm64` |
| [kube-capacity_v0.8.0_linux_i386.tar.gz](https://github.com/robscott/kube-capacity/releases/download/v0.8.0/kube-capacity_v0.8.0_linux_i386.tar.gz) | 9.9 MiB | `native/linux/x86` |
| [kube-capacity_v0.8.0_linux_x86_64.tar.gz](https://github.com/robscott/kube-capacity/releases/download/v0.8.0/kube-capacity_v0.8.0_linux_x86_64.tar.gz) | 10.8 MiB | `native/linux/x64` |
| [kube-capacity_v0.8.0_windows_arm64.zip](https://github.com/robscott/kube-capacity/releases/download/v0.8.0/kube-capacity_v0.8.0_windows_arm64.zip) | 9.7 MiB | `native/win/arm64` |
| [kube-capacity_v0.8.0_windows_i386.zip](https://github.com/robscott/kube-capacity/releases/download/v0.8.0/kube-capacity_v0.8.0_windows_i386.zip) | 10.5 MiB | `native/win/x64` |
| [kube-capacity_v0.8.0_windows_x86_64.zip](https://github.com/robscott/kube-capacity/releases/download/v0.8.0/kube-capacity_v0.8.0_windows_x86_64.zip) | 11.1 MiB | `native/win/x64` |

## Distribution status

Reported by **9** distros on [repology.org](https://repology.org/project/kube-capacity). **7** are ✅ on the latest upstream release, **2** are ⚠️ on an older version.

| Distro | Version | Status |
|--------|---------|--------|
| Nix unstable | `0.8.0` | ✅ latest |

## Improve this data

Install metadata for kube-capacity lives in the [x-cmd/install](https://github.com/x-cmd/install) index — a curated YAML package list that x-cmd consumes at install time. If `kube-capacity` is missing, out of date, or installs incorrectly, please open an issue or PR there:

- **Open an issue**: <https://github.com/x-cmd/install/issues/new>
- **Edit the package entry**: <https://github.com/x-cmd/install/edit/main/kube-capacity.yml> (or whichever path the index uses)

The data on this page (card / loc / scorecard / release) is auto-collected by [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) and is regenerated daily. Improvements to *install behaviour* (which version gets installed, platform-specific quirks, dependencies) belong upstream in the index.

_Snapshot: `data/card/260910.yml` · 2026-09-10T22:46:20Z._
