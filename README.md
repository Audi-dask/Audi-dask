<h1 align="center">Audi-dask</h1>

<p align="center">
  <strong>Infrastructure · Backend · Networking · AI-assisted Engineering</strong>
</p>

<p align="center">构建能在真实生产环境中运行的低依赖工具、内部平台与自动化系统。</p>

<p align="center">
  <a href="https://github.com/Audi-dask"><img src="https://img.shields.io/badge/GitHub-Audi--dask-181717?style=flat-square&logo=github" alt="GitHub"></a>
  <a href="https://github.com/tailscale/tailcat/pull/62"><img src="https://img.shields.io/badge/tailcat-PR%20%2362%20merged-2ea44f?style=flat-square&logo=github" alt="tailcat PR 62 merged"></a>
  <a href="https://github.com/tailscale/tailcat/pull/75"><img src="https://img.shields.io/badge/tailcat-PR%20%2375%20open-8957e5?style=flat-square&logo=github" alt="tailcat PR 75 open"></a>
</p>

<p align="center">
  <a href="#open-source">Open Source</a> ·
  <a href="#selected-projects">Projects</a> ·
  <a href="#toolbox">Toolbox</a>
</p>

---

## Snapshot

| Focus | What I build |
|---|---|
| **Infrastructure** | Kubernetes、多云平台、可观测性与自托管服务 |
| **Backend** | Go 网络工具、数据库平台、数据同步与审计系统 |
| **Security** | WAF / CC 防护、网关限流、线上安全事件响应 |
| **AI Engineering** | AIOps、Skill Registry、本地模型与开发工作流 |

---

## Open Source

### Tailscale / tailcat

参与开发 [tailscale/tailcat](https://github.com/tailscale/tailcat)，一个通过 Tailscale 数据平面工作的 netcat 风格网络工具。

| 状态 | 贡献 | 结果 |
|---|---|---|
| ✅ Merged | [PR #62 — add forward subcommand](https://github.com/tailscale/tailcat/pull/62) | 本地 TCP 转发、多端口映射、绑定地址；包含单元、CLI 与端到端测试 |
| 🚧 Open | [PR #75 — exit-node targets](https://github.com/tailscale/tailcat/pull/75) | 支持通过 Exit Node 转发到任意可达的 `IP:port` 目标 |

---

## Selected Projects

| Project | Description | Stack |
|---|---|---|
| [Overseer](https://github.com/Audi-dask/Overseer) | 企业自托管 AI Code Review Agent，自动分析 GitLab MR 与 Push 并回填评审结果。 | Go · GitLab · LLM |
| [NextMeta](https://github.com/Audi-dask/NextMeta) | MySQL 审核平台，支持动态规则配置、静态分析和角色权限管理。 | Go · React · MySQL |
| [tailcat-forward](https://github.com/Audi-dask/tailcat-forward) | 基于官方 [tailcat](https://github.com/tailscale/tailcat) Fork 的功能验证仓库：在上游尚未支持 TCP 转发时实现并验证该能力，相关成果随后通过 [PR #62](https://github.com/tailscale/tailcat/pull/62) 进入上游，并继续推进 [PR #75](https://github.com/tailscale/tailcat/pull/75)。 | Go · TCP · Tailscale |
| Ledger | 透明 Redis 审计代理，支持命令级日志与凭据抽象。 | Go · Redis RESP |
| RiverSync | MySQL CDC 同步工具，支持全量初始化与 Binlog 增量复制。 | Go · MySQL Binlog |
| Monitoring Agent | 单二进制监控代理，整合 exporters 与 promtail。 | Go · Prometheus · Loki |
| Pagelite | 面向私有化部署的自托管静态网站源站平台。 | Go · MinIO · Nginx |

---

## Toolbox

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)

<details>
<summary>More tools</summary>

MySQL · Redis · AWS · Grafana · Loki · MinIO · Tailscale / Headscale · Teleport · Ollama · PyTorch · Swift / SwiftUI

</details>

## Currently Exploring

- PostgreSQL compatibility for [NextMeta](https://github.com/Audi-dask/NextMeta)
- AI-assisted engineering workflows with explicit behavior rules and reusable skill registries
- Local AI tools, desktop automation, and Apple Silicon model inference

<p align="center">
  <strong>Open to discussions around infrastructure tooling, backend systems, networking, and self-hosted AI.</strong>
</p>
