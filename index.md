---
layout: default
---

<section id="features"></section>
  
## Apa itu SLEMP?

### Penjelasan Singkat
Simple, Linux, Engine-X (Nginx), MySQL/MariaDB, PHP-FPM. Panel web sederhana untuk Centos, Fedora, Debian, Ubuntu, Linux Mint, Raspberry, Deepin serta Distro-distro keluarga RPM dan DEB. Berisi perangkat lunak untuk kebutuhan server web yang dipasang dan dikonfigurasikan dari kode sumbernya (bukan paket bawaan distro). 

### Fitur-Fitur
* Nginx (1.12 - 1.16)
* MySQL (5.5 - 5.7) / MariaDB (10.0-10.3)
* PHP-FPM (5.6-7.3)
* PHPMyAdmin
* Informasi Sistem (Server)
* Site Manager
* SSL
* File Manager
* Database Manager
* Monitor CPU, Jaringan, Baca tulis Disk, Memory (RAM)
* Firewall dan pencatatan keamanan
* Crontab Manager
* Replika Database (Master-Slave)
* Sinkronisasi File (Rsync Lokal atau Remote)
* Backup ke Google Drive

<section id="install"></section>
  
## Bagaimana cara pasang SLEMP?
### Persyaratan sistem
Memori: 128M atau lebih, disarankan 512M atau lebih
Disk: Setidaknya 4GB ruang disk kosong
Lainnya: Pastikan itu adalah sistem operasi yang bersih, tidak ada Apache / Nginx / PHP / MySQL / MariaDB yang diinstal sebelumnya.

### Perintah Pemasangan

#### Centos / Fedora (.RPM Base)

```ruby
sudo curl -o install.sh https://basoro.id/slemp.sh && sudo bash install.sh
````
#### Debian / Ubuntu / Linux Mint / Raspberry (.DEB Base)

```ruby
sudo wget -O install.sh https://basoro.id/slemp.sh && sudo bash install.sh
````

<section id="screenshot"></section>

## Tangkapan layar SLEMP

### Dashboard

![Branching](https://guides.github.com/activities/hello-world/branching.png)

