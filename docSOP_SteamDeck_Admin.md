# Steam Deck Desktop Mode – Administrative Workstation SOP

## 1. Purpose
This Standard Operating Procedure (SOP) defines the process for configuring a Steam Deck in Desktop Mode as an administrative workstation. The goal is to enable reliable server management, RDP/SSH access, GitHub workflows, website maintenance, and general sysadmin tasks.

## 2. Scope
This SOP applies to any Steam Deck used for:
- Proxmox administration
- Linux/Windows server management
- GitHub repository maintenance
- Website updates
- Remote access and development workflows

## 3. Responsibilities
- **Admin/User:** Follow this SOP to configure and maintain the workstation.
- **IT/Support (optional):** Provide credentials, network access, and security guidance.

---

## 4. Prerequisites

### Hardware
- Steam Deck (any model)
- USB‑C dock or hub (recommended)
- Keyboard and mouse (optional but helpful)
- Wi‑Fi or Ethernet connection

### Accounts & Access
- Steam account logged in
- GitHub account
- SSH/RDP credentials for servers
- Access to Proxmox or other hypervisors (if applicable)

---

## 5. Enter Desktop Mode
1. Press the **Steam** button  
2. Select **Power**  
3. Choose **Switch to Desktop**  
4. Wait for KDE Plasma to load

---

## 6. System Updates

### Update SteamOS packages
```bash
sudo pacman -Syu
