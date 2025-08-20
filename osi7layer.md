# Rangkuman OSI 7 Layer

Model **OSI (Open Systems Interconnection)** terdiri dari 7 lapisan yang menjelaskan bagaimana data dikirimkan dari satu komputer ke komputer lain dalam jaringan.  
Setiap lapisan punya fungsi masing-masing agar komunikasi bisa berjalan lancar.

---

## 📌 Tabel Ringkasan OSI 7 Layer

| No | Lapisan (Layer)   | Fungsi Utama                                                                 | Contoh Implementasi         |
|----|------------------|------------------------------------------------------------------------------|-----------------------------|
| 7  | Application      | Memberikan layanan jaringan langsung ke aplikasi pengguna.                   | HTTP, FTP, SMTP, DNS        |
| 6  | Presentation     | Translasi format data, enkripsi, kompresi.                                   | SSL/TLS, JPEG, MP3          |
| 5  | Session          | Mengelola sesi komunikasi, membuat, menjaga, mengakhiri koneksi.             | NetBIOS, RPC                |
| 4  | Transport        | Menjamin data sampai dengan benar, urut, tanpa error.                        | TCP, UDP                    |
| 3  | Network          | Routing & pengalamatan logis, data berbentuk paket.                          | Router, IP, ICMP            |
| 2  | Data Link        | Mengemas data jadi frame, deteksi error, menggunakan MAC Address.             | Switch, Ethernet            |
| 1  | Physical         | Lapisan paling bawah, mentransmisikan bit (0/1) melalui media fisik.         | Kabel, Wi-Fi, Gelombang     |

---

## 📌 Diagram OSI 7 Layer

![Diagram OSI 7 Layer]img/osi.png
