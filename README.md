# MehdiCloud – Mon Cloud Personnel Sécurisé avec Raspberry Pi 4 & Nextcloud

This project is a self-hosted personal cloud solution, built on a Raspberry Pi 4 using Nextcloud, secured with Fail2Ban, UFW, and (soon) HTTPS via Let’s Encrypt.

---

## Objectifs du projet

- Host a personal Nextcloud instance on a Raspberry Pi 4.
- Secure server access using firewall, SSH, and Fail2Ban.
- Enable local access (HTTP) and prepare for future HTTPS with Let’s Encrypt.
- Learn self-hosting with Linux and networking tools.

---

## Technologies & Tools

| Composant     | Version / Détail           |
|---------------|----------------------------|
| Raspberry Pi  | Pi 4 Model B (4 Go RAM)    |
| OS            | Raspberry Pi OS Lite       |
| Serveur Web   | NGINX                      |
| Cloud         | Nextcloud 28+              |
| Base de Données | MariaDB                  |
| Pare-feu      | UFW                        |
| Anti-bruteforce | Fail2Ban                 |
| Accès distant | SSH via CMD Windows        |

---

## Project Structure
```
MehdiCloud/
├── scripts/
│   ├── nextcloud_install.sh
│   ├── ufw_fail2ban_setup.sh
│   └── mariadb_config.sh
├── Comment utiliser/
│   ├── 1-Rapport Général.pdf
│   ├── 2-Utilisation de Raspberry Pi Imager.pdf
│   ├── 3-Étapes de mise en place.pdf
│   └── 4-Lancement de Nextcloud.pdf
└── README.md 
```
