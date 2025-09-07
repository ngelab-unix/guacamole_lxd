# guacamole_lxd
Installation Guacamole LXC Canonical ( https + domain + cloudflared zerotrust )

# Remote Office Access Lab with Apache Guacamole + Cloudflare Tunnel + Domain

## 🎯 Tujuan
Membangun simulasi remote access kantor menggunakan:
- **Apache Guacamole + TOTP** untuk akses desktop/server via web
- **TOTP + Google Authentifikator** sebagai lapisan keamanan kedua dalam proses autentikasi dua langkah (2FA)
- **Cloudflare Tunnel** untuk publikasi tanpa IP publik
- **Domain** untuk mempermudah mengakses server via web
- **Tomcat** sebagai terminator SSL (opsional)
- **Canonical/LXD** untuk isolasi environment

## 🗂️ Fitur
- Akses remote desktop via web (RDP, SSH, VNC)
- Integrasi domain dengan Cloudflare
- Akses aman tanpa IP publik

## 📊 Diagram Topologi
![Topologi Jaringan](diagrams/network-topology.png)

## 📷 Screenshot
![Login Page](guacamole_images/guacalab.png)

## 📌 Catatan
- Tested on Debian 12 LXD container
- Bisa diadaptasi untuk production dengan server fisik/vm

-------------------------------------------------------------------------------------------------------------
## 👤 Author
Aditya Ramadhani – [LinkedIn](https://linkedin.com/in/username) | [Email](mailto:ramadhaniaditya19@gmail.com)
-------------------------------------------------------------------------------------------------------------
