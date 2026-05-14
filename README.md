<div align="center">

<h1>Filip Andersson</h1>
<h3>Software Developer · DevOps Engineer</h3>

<code>CODE</code> <b>→</b> <code>BUILD</code> <b>→</b> <code>DEPLOY</code> <b>→</b> <code>MONITOR</code>

<br/><br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-filipanderssondev-0a66c2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/filipanderssondev)
[![Email](https://img.shields.io/badge/Email-andersson.filip98%40gmail.com-333?style=flat-square&logo=gmail&logoColor=white)](mailto:andersson.filip98@gmail.com)
![Location](https://img.shields.io/badge/Linköping-Sverige-555?style=flat-square)
![Open to work](https://img.shields.io/badge/Open%20to%20work-✓-2ea44f?style=flat-square)

</div>

-----

## About

I’m a systems developer and DevOps engineer graduating from Chas Academy in June 2026. I recently completed a 6-month internship at **SMHI IT-Produktion** in Norrköping, where I built a complete IT infrastructure from scratch — virtualized nodes on Proxmox VE, container orchestration with Podman, identity management via FreeIPA, and automated provisioning with Ansible.

My thesis project, built for SMHI’s IT security function, is a containerized CLI tool in Python that receives email via SMTP, extracts headers, URLs and attachments, and checks them against threat intelligence databases — runs isolated in Docker or Podman.

I like owning things end to end. From bare metal to running container.

-----

## Stack

**Languages**

![C](https://img.shields.io/badge/C-00599c?style=flat-square&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599c?style=flat-square&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776ab?style=flat-square&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4eaa25?style=flat-square&logo=gnubash&logoColor=white)

**Containers & Orchestration**

![Docker](https://img.shields.io/badge/Docker-2496ed?style=flat-square&logo=docker&logoColor=white)
![Podman](https://img.shields.io/badge/Podman-892ca0?style=flat-square&logo=podman&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326ce5?style=flat-square&logo=kubernetes&logoColor=white)

**Automation & IaC**

![Ansible](https://img.shields.io/badge/Ansible-ee0000?style=flat-square&logo=ansible&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088ff?style=flat-square&logo=githubactions&logoColor=white)
![GitOps](https://img.shields.io/badge/GitOps-f05032?style=flat-square&logo=git&logoColor=white)

**Monitoring & Security**

![Prometheus](https://img.shields.io/badge/Prometheus-e6522c?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-f46800?style=flat-square&logo=grafana&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-fcc624?style=flat-square&logo=linux&logoColor=black)
![FreeIPA](https://img.shields.io/badge/FreeIPA%20%2F%20TLS-333?style=flat-square&logo=letsencrypt&logoColor=white)

**Embedded**

![ESP32](https://img.shields.io/badge/ESP32-000?style=flat-square&logo=espressif&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00878f?style=flat-square&logo=arduino&logoColor=white)

-----

## Projects

### [PostmortemCLI – Email Security Analyzer](https://github.com/Filipanderssondev/PostmortemCLI-email-security-analyzer)

> Thesis project · SMHI IT-säkerhetsfunktionen · 2026

Containerized CLI tool that receives email via a built-in SMTP listener, extracts headers, URLs and attachments, and checks them against threat intelligence sources including Spamhaus, URLhaus, VirusTotal and MalwareBazaar. Stateless by design — the container self-destructs after each session.

`Python` `Docker` `Podman` `aiosmtpd` `dnspython` `GitHub Actions`

-----

### [Container Stack Deployment with Ansible](https://github.com/Filipanderssondev/Container_Stack_Deployment_With_Ansible)

> SMHI IT-Produktion internship · 2025–2026

Automated deployment of a full container stack across virtual machines running Podman, orchestrated from a dedicated control VM via Ansible playbooks. Part of the plab.internal infrastructure project at SMHI.

`Ansible` `Podman` `Linux` `IaC` `Rocky Linux`

-----

### [VM Monitoring Stack](https://github.com/Filipanderssondev/Monitoring_of_virtual_machines)

> SMHI IT-Produktion internship · 2025–2026

Full observability stack for virtual machines — metrics collection via Node Exporter, aggregation with Prometheus, and visualization in Grafana. Built as part of the SMHI infrastructure project.

`Prometheus` `Grafana` `Node Exporter` `Linux` `Ansible`

-----

### [Sentinel – IoT Safety Device](https://github.com/chas-challenge-code-6/hardware-esp32)

> Chas Challenge · Team Code 6 · 🏆 Best Hardware

IoT safety device for high-risk work environments. ESP32 firmware developed in a cross-functional team over 10 weeks. Won the Best Hardware award at Chas Challenge.

`C++` `ESP32` `PlatformIO` `Embedded` `IoT`

-----

### [Security System](https://github.com/Filipanderssondev/course3_projectgroup2_security_system)

> Chas Academy · Course 3 · Group project

Embedded security system built in C/C++ as a group project at Chas Academy.

`C` `C++` `Embedded systems`

-----

## Experience

**IT-administratör, LIA-praktik — SMHI IT-Produktion, Norrköping** *(Nov 2025 – Apr 2026)*
Built a complete virtualized IT environment from scratch on an ASUS NUC running Proxmox VE. Five Rocky Linux VMs managed with Ansible, containerized services via Podman, identity and certificate management with FreeIPA, and a full observability stack with Prometheus, Grafana and Alertmanager.

**Examensarbete — SMHI IT-säkerhetsfunktionen** *(Apr 2026 – Jun 2026)*
Containerized CLI security tool in Python. See PostmortemCLI above.

-----

## Education

**Systemutvecklare C/C++** — Chas Academy *(2024–2026)*

-----

<div align="center">
<sub>Open to work · Linköping, Sverige · andersson.filip98@gmail.com</sub>
</div>