# Instalasi Ubuntu Server dan Konfigurasi SSH Server

## Deskripsi
Repository ini berisi langkah-langkah instalasi Ubuntu Server pada VirtualBox serta konfigurasi SSH Server menggunakan aplikasi PuTTY.

---

# A. Persiapan Software

## 1. Download Ubuntu Server
- Ketik "Ubuntu Server download" pada pencarian Google/Chrome.
- Download Ubuntu Server versi 26.04 LTS.

## 2. Download PuTTY
- Cari aplikasi PuTTY di Google.
- Download versi PuTTY sesuai spesifikasi komputer.

---

# B. Pembuatan Virtual Machine

## 3. Membuat Virtual Machine di VirtualBox
- Buka VirtualBox.
- Klik New.
- Masukkan nama virtual machine Ubuntu Server.

## 4. Setting Processor dan Base Memory
- Atur processor sesuai kebutuhan.
- Atur Base Memory/RAM sesuai spesifikasi komputer.

## 5. Tampilan Virtual Machine
- Pastikan virtual machine berhasil dibuat.

## 6. Pengaturan Network
- Klik kanan virtual machine.
- Pilih Settings.
- Atur Adapter 1 dan Adapter 2 pada menu Network.

---

# C. Instalasi Ubuntu Server

## 7. Memulai Instalasi
- Pilih Try or Install Ubuntu Server lalu tekan Enter.

## 8. Tampilan Awal Instalasi
- Tunggu sampai tampilan instalasi muncul.

## 9. Memilih Bahasa
- Pilih Bahasa Indonesia (opsional).
- Tekan Enter.

## 10. Konfigurasi Network
- Tunggu hingga IP Address muncul.
- Klik Done/Enter.

## 11. Melanjutkan Instalasi
- Klik Done/Enter pada konfigurasi berikutnya.

## 12. Proses Instalasi
- Tunggu hingga seluruh proses instalasi selesai.
- Klik Done/Enter.

## 13. Konfigurasi Tambahan
- Klik Done/Next pada tampilan konfigurasi.

## 14. Continue Instalasi
- Klik Continue/Enter.

## 15. Membuat User Ubuntu
- Masukkan:
  - Name
  - Username
  - Password
- Klik Done/Enter.

## 16. Instalasi SSH Server
- Pilih Install OpenSSH Server.
- Klik Done lalu Enter.

## 17. Reboot Ubuntu Server
- Tunggu sampai muncul tulisan Reboot Now.
- Tekan Enter.

## 18. Login Ubuntu Server
- Login menggunakan username dan password yang telah dibuat.

---

# D. Konfigurasi SSH dan Network

## 19. Menjalankan Perintah Dasar

Ketik perintah berikut:

```bash
ls
ssh
```

## 20. Mengecek IP Address

Ketik:

```bash
ifconfig
```

Jika muncul perintah install net-tools, install menggunakan:

```bash
sudo apt install net-tools
```

Kemudian tekan Enter.

## 21. Membersihkan Terminal

Ketik:

```bash
clear
```

## 22. Melihat IP Address
Ketik kembali:

```bash
ifconfig
```

Lihat IP Address pada baris ketiga, contoh:

```bash
192.168.43.2
```

Instalasi Ubuntu dan SSH Server selesai.

---

# E. Instalasi PuTTY

## 23. Install PuTTY
- Klik dua kali file installer PuTTY.
- Klik Next.

## 24. Menentukan Lokasi Penyimpanan
- Pilih lokasi penyimpanan.
- Klik Next.

## 25. Install PuTTY Files
- Pilih Install PuTTY Files.
- Klik Install.

## 26. Selesai Instalasi
- Klik Finish.

---

# F. Konfigurasi PuTTY

## 27. Membuka PuTTY
- Buka aplikasi PuTTY melalui menu Windows.

## 28. Input IP Address
- Masukkan Host Name/IP Address sesuai Ubuntu Server.

Contoh:

```bash
192.168.43.2
```

- Klik Open.

## 29. Login PuTTY
- Masukkan username Ubuntu.
- Masukkan password Ubuntu.
- Tekan Enter.

## 30. SSH Berhasil
- Jika berhasil, maka IP Address pada Ubuntu dan PuTTY akan sama.

---

# G. Cara Melihat IP Address di Windows

## 31. Membuka CMD
- Tekan Windows + R.
- Ketik cmd lalu Enter.

## 32. Mengecek IP Address
Ketik:

```bash
ipconfig
```

Maka IP Address Windows akan muncul pada Command Prompt.

---

# Kesimpulan
Praktikum ini berhasil melakukan instalasi Ubuntu Server pada VirtualBox, konfigurasi SSH Server, serta remote server menggunakan aplikasi PuTTY.
