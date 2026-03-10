# 🔐 Alexis Sosa

### Técnico en Ciberseguridad | Seguridad & Operaciones de Infraestructura
#### 🇦🇷 Argentina

---

![Banner](https://raw.githubusercontent.com/Alexso9410/Alexso9410/main/imagenes/bannerlinkgit.jpg)

---

## 👨‍💻 Sobre mí

Soy Técnico Superior en Seguridad Informática, apasionado por la ciberseguridad con foco en la intersección entre **infraestructura, seguridad y automatización**. Me interesa entender los sistemas desde adentro: cómo se construyen, cómo se aseguran y cómo se defienden.

Mantengo un homelab con servicios reales de seguridad corriendo en producción, y participo activamente en CTFs junto a un equipo de 5 integrantes en plataformas como **HackTheBox**, **TryHackMe** y **CyberDefenders**. Tengo un writeup oficial publicado y aceptado por CyberDefenders como guía de la plataforma.

orientación y aspiraciones:

- 🏗️ **Seguridad en infraestructura / SysAdmin / DevSecOps** — operar entornos reales, asegurarlos y automatizarlos
- 🤖 **IA aplicada y agentes autónomos** — construcción de soluciones con LLMs, automatización inteligente e integración en flujos de seguridad
- 🔍 **OSINT & Threat Intelligence** — inteligencia de fuentes abiertas, análisis de amenazas e investigación digital

---

## 🛠️ Stack Tecnológico

### 🔒 Seguridad & Monitoreo
![Wazuh](https://img.shields.io/badge/Wazuh-SIEM-00D4FF?style=flat-square&logoColor=white)
![Suricata](https://img.shields.io/badge/Suricata-IDS%2FIPS-FF6B00?style=flat-square)
![Elastic SIEM](https://img.shields.io/badge/Elastic-SIEM-005571?style=flat-square&logo=elastic&logoColor=white)
![Zabbix](https://img.shields.io/badge/Zabbix-Monitoring-DC382D?style=flat-square&logoColor=white)
![Nessus](https://img.shields.io/badge/Nessus-Vulnerability%20Scanner-00A8E8?style=flat-square)
![Sysmon](https://img.shields.io/badge/Sysmon-Endpoint%20Monitoring-0078D4?style=flat-square)

### 🕵️ Auditoría Web & OSINT
![Burp Suite](https://img.shields.io/badge/Burp%20Suite-Web%20Security-FF6B6B?style=flat-square)
![Nmap](https://img.shields.io/badge/Nmap-Network%20Scanning-FF6B6B?style=flat-square)
![OWASP](https://img.shields.io/badge/OWASP%20Top%2010-000000?style=flat-square&logo=owasp&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white)
![Shodan](https://img.shields.io/badge/Shodan-OSINT-AA0000?style=flat-square)

### ☁️ Infraestructura & Virtualización
![Proxmox](https://img.shields.io/badge/Proxmox-VE-E57000?style=flat-square&logo=proxmox&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![LXC](https://img.shields.io/badge/LXC-Containers-00A8E8?style=flat-square)
![OPNsense](https://img.shields.io/badge/OPNsense-Firewall-D94F00?style=flat-square)
![VMware](https://img.shields.io/badge/VMware-607078?style=flat-square&logo=vmware&logoColor=white)
![GNS3](https://img.shields.io/badge/GNS3-Network%20Simulation-00A8E8?style=flat-square)

### 🤖 IA & Automatización
![Ollama](https://img.shields.io/badge/Ollama-Local%20LLM-000000?style=flat-square)
![LiteLLM](https://img.shields.io/badge/LiteLLM-LLM%20Gateway-6C63FF?style=flat-square)
![n8n](https://img.shields.io/badge/n8n-Automation-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)

### 💻 Lenguajes & Scripting
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

## 🏗️ Homelab — Infraestructura Personal

Mi laboratorio personal es donde más aprendo. Corro **Proxmox VE** como hypervisor sobre hardware dedicado, con una estación de trabajo separada para desarrollo, simulación de redes (GNS3) y virtualización adicional.

### Servicios en producción

| Servicio | Rol |
|----------|-----|
| **Wazuh** | SIEM — correlación de eventos y alertas de seguridad |
| **Suricata** | IDS/IPS — detección de intrusiones en red |
| **Elastic SIEM / ELK / Kibana** | Stack de análisis y visualización de logs |
| **OPNsense** | Firewall perimetral, reglas, VLANs |
| **Tailscale** | VPN mesh zero-config para acceso remoto seguro |
| **Nginx** | Reverse proxy para servicios internos |
| **Docker + LXC** | Contenedores para aislar y desplegar servicios |
| **n8n** | Automatización de workflows e integraciones |
| **OpenMediaVault + Nextcloud** | NAS casero, almacenamiento privado y backups |
| **Immich** | Gestión de fotos autohospedada |
| **AdGuard** | DNS filtering y bloqueo de rastreadores |
| **PostgreSQL + pgvector** | Base de datos con soporte de embeddings vectoriales |

### 🤖 Proyecto personal — Asistente IA multi-agente

Construí un asistente personal sobre este homelab: un bot que se comunica a traves de red social con **arquitectura multi-agente** que integra LLMs locales y cloud mediante un gateway unificado (LiteLLM), memoria semántica con pgvector, orquestación de workflows via n8n, y skills especializadas de OSINT, monitoreo de infraestructura y automatización.

```
red social → Bot (Python / FastAPI)
               ↓
         LiteLLM Gateway → modelos cloud + modelos locales (Ollama)
               ↓
         Router de intents → skills especializadas
               ↓
         PostgreSQL + pgvector  ·  n8n  ·  APIs externas
```

La arquitectura está pensada para crecer: cada skill es un agente independiente que puede invocar herramientas externas, ejecutar escaneos de seguridad o conversar con contexto persistente.

> Un proyecto donde convergen seguridad, infraestructura e IA aplicada.

---

## 🎯 Intereses & Dirección

```
🏗️  Seguridad en Infraestructura    →   hardening, monitoreo, operaciones seguras
⚙️  DevSecOps / SysAdmin            →   automatización, CI/CD seguro, gestión de servicios
🤖  IA Aplicada & Agentes           →   LLMs, automatización inteligente, soluciones con IA
🔍  OSINT & Threat Intelligence     →   inteligencia de fuentes abiertas, análisis de amenazas
```

---

## 🏆 CTF & Plataformas

| Plataforma | Estado |
|------------|--------|
| 🎯 **HackTheBox** | Activo |
| 🎯 **TryHackMe** | Activo |
| 🎯 **CyberDefenders** | Activo — [perfil: ales04](https://cyberdefenders.org/p/ales04) |
| 🎯 **The Hacker Labs** | Activo |

### 📝 Writeup oficial publicado

**Yara Trap Lab — CyberDefenders**
Writeup elaborado junto al equipo CTF, aceptado y publicado como guía oficial de la plataforma. Cubre análisis de reglas YARA, detección de malware y forense aplicado.

📖 [Leer en Medium →](https://medium.com/@IgnoranzaSolare) *(ene. 2026)*

---

## 💼 Experiencia

- 🏛️ **Fuerza de Seguridad Pública** — actualidad
- 🛡️ **Heimdall Agency** — Pasante en ciberseguridad
- 🔧 **ArgOS** — Voluntario Tool Tester - actualidad

---

## 📊 GitHub Stats

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=Alexso9410&show_icons=true&theme=dark&hide_border=true&bg_color=0D1117&title_color=00D4FF&icon_color=00D4FF&text_color=FFFFFF)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Alexso9410&layout=compact&theme=dark&hide_border=true&bg_color=0D1117&title_color=00D4FF&text_color=FFFFFF)

![GitHub Streak](https://github-readme-streak-stats.demolab.com/?user=Alexso9410&theme=dark&hide_border=true&background=0D1117&ring=00D4FF&fire=00D4FF&currStreakLabel=00D4FF)

---

## 💬 Contacto

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/alexis-sosa-52412623b/)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Alexso9410)
[![ProtonMail](https://img.shields.io/badge/ProtonMail-8B89CC?style=for-the-badge&logo=protonmail&logoColor=white)](mailto:alesosasec@proton.me)
[![CyberDefenders](https://img.shields.io/badge/CyberDefenders-FFB000?style=for-the-badge&logoColor=black)](https://cyberdefenders.org/p/ales04)

---

### 🛡️ *"Build. Break. Defend. Automate."*

[![Visitor Count](https://visitor-badge.laobi.icu/badge?page_id=Alexso9410.Alexso9410&left_color=00D4FF&right_color=7C3AED)](https://github.com/Alexso9410)
