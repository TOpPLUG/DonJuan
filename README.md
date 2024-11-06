# 1.

<img src="https://img.shields.io/badge/Update%20_&_%20Upgrade-green">

```html
apt-get update && apt-get upgrade -y && update-grub && sleep 2 && reboot
```

### 3.

- Install Semua Layanan VPN /Install All VPN Service

```html
rm -f setup.sh && apt update && apt upgrade -y && update-grub && sleep 2 && apt-get update -y && apt-get upgrade && sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl unzip && wget https://raw.githubusercontent.com/TOpPLUG/vps-admin/main/setup.sh && chmod +x setup.sh && sed -i -e 's/\r$//' setup.sh && screen -S setup ./setup.sh
```

### 4. DONE / SELESAI

- • jika tidak bisa login di vps ,gunakan port ssh
- • 22, 2253

### 5. MENU, INFO ,UPDATE ,FIX

- untuk menampilkan menu

```html
menu
```

- Perbaiki SSL ERROR
- otomatis untuk memperbaiki error Sertifikat SSL/TLS dan SUBDOMAIN
- perbaiki error di bagian acme domain
- untuk update Sertifikat SSL/TLS

```html
slhost && certv2ray
```

- lalu restart
