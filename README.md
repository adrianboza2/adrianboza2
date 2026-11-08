<div align="center">

<img src="assets/banner.svg" alt="Adrián Boza Suárez — Cloud · DevSecOps · Cloud Security" width="100%">

<a href="https://www.linkedin.com/in/adri%C3%A1n-boza-su%C3%A1rez-51623a184/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
<img src="https://img.shields.io/badge/Madrid-open_to_junior_roles-3fb950?style=for-the-badge" alt="Madrid · open to junior roles">

<sub>🇬🇧 English · <a href="README.es.md">🇪🇸 Español</a></sub>

</div>

I come from **network operations**: rotating shifts in a 24x7 NOC, troubleshooting Cisco and Huawei routers across a nationwide WAN. Now I build the layer on top of that — **cloud, automation and security** — and I like to understand how things break before I trust them.

## ⚡ Right now

| 🎓 Master's in Cloud Security & DevSecOps | ☁️ AWS Security course (CTIC) | 🛠️ Homelab |
|---|---|---|
| Tajamar Tech, 700 h · Oct 2026 – May 2027<br>Azure infrastructure, IaC, GitHub Actions | 140 h · Nov – Dec 2026<br>Path to **AWS Security Specialty (SCS-C03)** | A VPS running my own automation agent 24/7:<br>cron jobs, MCP servers, health checks |

## 🚀 Featured projects

<table>
<tr>
<td width="50%" valign="top">

### ☸️ [Self-healing Kubernetes lab](https://github.com/adrianboza2/proyecto-intermodular-asir)
<a href="https://github.com/adrianboza2/proyecto-intermodular-asir"><img src="assets/k8s-self-healing.svg" alt="kubectl replay: a pod is deleted and recreated" width="100%"></a>

Nginx with 2 replicas, probes, Prometheus + Grafana and a **default-deny** set of NetworkPolicies. Kill a pod: traffic never stops.

`Kubernetes` `Docker` `Prometheus` `Grafana` `NetworkPolicy`

</td>
<td width="50%" valign="top">

### 🌩️ [Severe-weather alert monitor](https://github.com/adrianboza2/script-aemet-python)
<a href="https://github.com/adrianboza2/script-aemet-python"><img src="assets/aemet-alert.jpg" alt="Desktop pop-up: alert escalated to orange" width="100%"></a>

Built during my internship for a **real ops need**: watches Spain's official weather-warning feed and alerts the team when a warning appears, escalates or clears.

`Python` `RSS` `SMTP` `cron` `Windows/Linux`

</td>
</tr>
</table>

<details>
<summary><b>🔒 Private work — happy to walk you through it</b></summary>
<br>

| Project | What it does |
|---|---|
| **jobscout** | Local-first job search pipeline: collects public listings, deduplicates them in SQLite, scores each one against a structured profile with an LLM and builds an HTML dashboard. Runs on its own every 72 h from my VPS. Built AI-assisted: I own the scope, design and review. |
| **24/7 agent on a VPS** | Ubuntu server with scheduled jobs (link inbox, auto-tagging, weekly digest), a health check every 15 min, nightly git backups and an MCP server published over Tailscale with GitHub OAuth. |
| **On-prem lab (Master's)** | Debian routers with Kea DHCP, nftables NAT and static routing across several subnets; Windows Server 2025 domain with AD DS, OUs, NTFS permissions and GPOs; Windows 11 clients joined to the domain. |

</details>

## 🧰 Toolbox

<p align="center">
  <img src="https://skillicons.dev/icons?i=linux,ubuntu,debian,bash,powershell,python,docker,kubernetes,prometheus,grafana,azure,aws,git,github&perline=14" alt="Linux, Ubuntu, Debian, Bash, PowerShell, Python, Docker, Kubernetes, Prometheus, Grafana, Azure, AWS, Git, GitHub">
</p>

<sub>Also in production at work: Cisco & Huawei routing/switching (VLANs, STP, BGP diagnostics), Cisco CUCM, device hardening, MDM/MFA rollouts.</sub>

## 🗺️ Learning path

```text
✅ ASIR (Network & Systems Administration)      2024 – 2026
✅ Network operations (NOC, 24x7)               2026
🔄 Azure infrastructure · AZ-900                 now
🔄 AWS Security · SCS-C03                        now
⏳ Terraform · GitHub Actions · DevSecOps        spring 2027
```
