# guacamole_lxd
Installation Guacamole LXC Canonical ( https + domain + cloudflared zerotrust )

# Remote Office Access Lab with Apache Guacamole + Cloudflare Tunnel + Domain

## 🎯 Tujuan
Membangun simulasi remote access kantor menggunakan:
- **Apache Guacamole + TOTP** untuk akses desktop/server via web
- **Cloudflare Tunnel** untuk publikasi tanpa IP publik
- **Tomcat** sebagai terminator SSL (opsional)
- **Canonical/LXD** untuk isolasi environment

## 🗂️ Fitur
- Akses remote desktop via web (RDP, SSH, VNC)
- Integrasi domain dengan Cloudflare
- Akses aman tanpa IP publik
- Script otomatisasi untuk deployment

## 📊 Diagram Topologi
![Topologi Jaringan](diagrams/network-topology.png)

## 🚀 Cara Deploy
1. Clone repo:
   ```bash
   git clone https://github.com/username/my-project-name.git
   cd my-project-name
   ```
2. Jalankan script setup:
   ```bash
   ./scripts/setup.sh
   ```
3. Akses aplikasi melalui domain:
   ```
   https://guacamole.domain.com
   ```

## 📷 Screenshot
![Login Page](guacamole_images/guaca-lab.png)
## 📌 Catatan
- Tested on Debian 12 LXD container
- Bisa diadaptasi untuk production dengan server fisik/vm

---

## 📚 Teknologi yang Digunakan
- Apache Guacamole
- Cloudflared
- Canonical / LXD
- tomcat9
- Debian 12

## 👤 Author
Aditya Ramadhani – [LinkedIn](https://linkedin.com/in/username) | [Email](mailto:ramadhaniaditya19@gmail.com)
