<h1 align="center">Hi 👋, I'm Jerome Jay Olavere</h1>
<h3 align="center">Web Developer · Network Engineer · Cybersecurity Analyst — Quezon City, Philippines 🇵🇭</h3>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=18&pause=1000&color=36BCF7&center=true&vCenter=true&width=600&lines=Building+web+apps+with+PHP+%2B+MySQL;MikroTik+RouterOS+%7C+PCC+Load+Balancing+%7C+Failover;Firewalls%2C+VLANs+%26+network+hardening;Self-hosting+everything+in+my+home-lab+%F0%9F%A7%AA" alt="Typing SVG" />
</p>

<p align="center">
  <a href="mailto:jeromejay.olavere@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://www.youtube.com/c/networmtv"><img src="https://img.shields.io/badge/YouTube-NetwormTV-FF0000?style=for-the-badge&logo=youtube&logoColor=white" /></a>
  <a href="https://dev.to/dev.netx34"><img src="https://img.shields.io/badge/dev.to-0A0A0A?style=for-the-badge&logo=devdotto&logoColor=white" /></a>
  <a href="https://stackoverflow.com/users/net4k"><img src="https://img.shields.io/badge/Stack_Overflow-FE7A16?style=for-the-badge&logo=stackoverflow&logoColor=white" /></a>
  <a href="https://fb.com/j.romeolavere"><img src="https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white" /></a>
</p>

---

## 🧑‍💻 About Me

- 🌐 **Web Developer** — I build business systems (HRIS, reservation and tracking systems) with PHP, CodeIgniter and MySQL
- 🛜 **Network Engineer** — MikroTik RouterOS v6/v7: multi-WAN PCC load balancing, policy-based routing, Netwatch failover, VLANs
- 🛡️ **Cybersecurity Analyst** — firewall design, network hardening, log monitoring and securing self-hosted services
- 🧪 **Home-lab tinkerer** — I test configs in my own lab before they go anywhere near production
- 🦀 Currently learning **Rust** to build networking tools
- 💬 Ask me about **Network Firewalls · MikroTik · Web App Development · Self-hosting**

---

## 🧪 My Home-Lab

> My home-lab is where I practice network engineering and security hands-on: routing, firewalling, self-hosting and monitoring.

```mermaid
flowchart LR
    ISP1([ISP 1]) --> MT
    ISP2([ISP 2]) --> MT
    MT[MikroTik Router<br/>PCC Load Balance + Failover<br/>Firewall / NAT] --> SW[Managed Switch<br/>VLANs]
    SW --> SRV[Linux Server<br/>Docker]
    SW --> LAN[Home / Work LAN]
    SW --> IOT[IoT / Guest VLAN<br/>isolated]
    SRV --> NPM[Nginx Proxy Manager<br/>reverse proxy + SSL]
    NPM --> APPS[Self-hosted apps<br/>web projects · dashboards]
```

| Area | What I run / practice |
|------|-----------------------|
| 🛜 **Routing** | MikroTik RouterOS v7 · dual-WAN PCC load balancing · policy-based routing (pin devices/games to a WAN) · Netwatch failover |
| 🔥 **Security** | Stateful firewall rules · port-scan & brute-force protection · VLAN isolation for IoT and guests · VPN (WireGuard) for remote access |
| 🐳 **Self-hosting** | Docker + Portainer stacks on Linux · Nginx Proxy Manager (NPMplus) with Let's Encrypt SSL · macvlan LAN networking · PostgreSQL · hosting my own web projects |
| 📊 **Monitoring** | Bandwidth and uptime monitoring · router logs · alerts when a WAN goes down |
| ⚙️ **Automation** | RouterOS scripting · Bash/Python helper scripts · [`mikrogen7-server`](https://github.com/JeromeJayOlavere/mikrogen7-server) (Rust) |

---

## 🚀 Featured Projects

| Project | Description | Stack |
|---------|-------------|-------|
| [**mikrogen7-server**](https://github.com/JeromeJayOlavere/mikrogen7-server) | Self-hosted backend for the RouterOS Forge desktop app: team accounts, synced generator configs, an end-to-end-encrypted router credential vault and a deploy audit log. Runs on Portainer behind Nginx Proxy Manager with Let's Encrypt | ![Rust](https://img.shields.io/badge/Rust-000000?logo=rust&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white) |
| [**hris-system**](https://github.com/JeromeJayOlavere/hris-system) | HR Information System with admin/user dashboards and performance modules (IPCR, OPCR, SPMS) plus OJT records | ![PHP](https://img.shields.io/badge/PHP-777BB4?logo=php&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white) |
| [**MarlferPortfolio**](https://github.com/JeromeJayOlavere/MarlferPortfolio) | Responsive portfolio site, shipped as a hardened Nginx container (non-root, read-only filesystem, health checks) with Docker CI | ![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white) ![Nginx](https://img.shields.io/badge/Nginx-009639?logo=nginx&logoColor=white) |

---

## 🛠️ Skills & Tools

**Web Development**

<p>
  <img src="https://skillicons.dev/icons?i=php,codeigniter,mysql,html,css,js,bootstrap,python,rust&perline=9" />
</p>

**Networking & Security**

<p>
  <img src="https://img.shields.io/badge/MikroTik-293239?style=for-the-badge&logo=mikrotik&logoColor=white" />
  <img src="https://img.shields.io/badge/RouterOS_v7-293239?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Firewall-B22222?style=for-the-badge&logo=fortinet&logoColor=white" />
  <img src="https://img.shields.io/badge/WireGuard-88171A?style=for-the-badge&logo=wireguard&logoColor=white" />
  <img src="https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white" />
  <img src="https://img.shields.io/badge/Nmap-4682B4?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Kali_Linux-557C94?style=for-the-badge&logo=kalilinux&logoColor=white" />
</p>

**Infrastructure & Tools**

<p>
  <img src="https://skillicons.dev/icons?i=linux,ubuntu,docker,nginx,bash,git,github,vscode,ps,androidstudio&perline=10" />
</p>

---

## 📊 GitHub Stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=JeromeJayOlavere&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=JeromeJayOlavere&layout=compact&theme=tokyonight&hide_border=true" />
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=JeromeJayOlavere&color=36BCF7&style=flat-square&label=Profile+Views" />
</p>

---

<p align="center"><i>“Secure the network, ship the app.”</i> 🛡️💻</p>
