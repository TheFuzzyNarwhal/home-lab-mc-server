# Minecraft Server Home Lab Infrastructure

## Overview
Engineered a high-performance, containerized Minecraft server environment on a repurposed laptop. This project focuses on infrastructure automation, performance optimization, and secure remote server management.

## Technical Stack
- **OS:** Ubuntu 24.04.4 LTS (Headless)
- **Containerization:** Docker, Docker Compose
- **Server Core:** PaperMC (Migrated from NeoForge)
- **Language/Automation:** Bash, Git
- **Networking:** SSH, RCON

## Key Engineering Achievements
- **Storage Management:** Expanded LVM partitions to reclaim 800GB of usable disk space for server data and backups.
- **Performance Tuning:** Replaced modded environments with PaperMC to eliminate CPU spikes. Implemented Aikar’s JVM flags for advanced garbage collection optimization.
- **Automation:** Containerized the server lifecycle, enabling rapid deployment and environment consistency.
- **System Hardening:** Standardized remote administration via SSH, maintaining a headless Linux environment.

## Current Status
- [x] Base server migration complete.
- [x] Docker integration and persistence.
- [ ] Automated backup scripting (In Progress).
- [ ] Monitoring dashboard integration (Planned).

## Learning Outcomes
Demonstrated proficiency in Linux command-line operations, container orchestration, and server-side performance analysis.
