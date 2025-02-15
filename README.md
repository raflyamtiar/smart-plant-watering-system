# Smart Plant Watering System - LEAFY

![Rangkaian IoT](Rangkaian%20IoT%20-%20Leafy_001.png)

## 📌 Pendahuluan

**Sistem Penyiraman Tanaman Otomatis** adalah sistem irigasi berbasis IoT yang dirancang untuk membantu pengguna dalam mengelola penyiraman tanaman secara efisien. Dengan menggunakan **NodeMCU ESP8266** dan **sensor kelembapan tanah**, sistem ini mendeteksi kondisi tanah secara real-time dan mengontrol penyiraman secara otomatis. Integrasi dengan **platform Blynk** memungkinkan pengguna untuk memantau dan mengontrol sistem dari jarak jauh melalui aplikasi seluler.

## 🌱 Fitur

- **Penyiraman Otomatis:** Sistem mengaktifkan pompa saat kelembapan tanah rendah dan berhenti saat mencapai tingkat yang ideal.
- **Pemantauan & Kontrol Jarak Jauh:** Pengguna dapat memeriksa kelembapan tanah, suhu, dan kelembapan udara melalui **aplikasi Blynk**.
- **Penyimpanan Data Real-Time:** Data sensor disimpan di **Firebase** untuk analisis dan pemantauan.
- **Kontrol Manual:** Pengguna dapat menyalakan pompa secara manual melalui aplikasi seluler.
- **Tampilan LCD:** Menyediakan pemantauan langsung tanpa harus membuka aplikasi.

## 📷 Diagram Sistem

### Diagram Blok

![Diagram Blok](diagram%20blok.png)

### Rangkaian IoT

![Rangkaian IoT](Rangkaian%20IoT%20-%20Leafy_001.png)

### Flowchart Sistem

![Flowchart](Flowchart%20Sistem.png)

### Diagram Jaringan

![Diagram Jaringan](Diagram%20Jaringan.png)

## 🔧 Komponen & Bahan

- **NodeMCU ESP8266** (Mikrokontroler)
- **Sensor Kelembapan Tanah** (Mendeteksi kadar kelembapan tanah)
- **DHT11** (Sensor suhu & kelembapan udara)
- **Mini DC Water Pump** (Pompa air otomatis)
- **Relay Module** (Mengontrol operasi pompa air)
- **LCD 16x2 I2C** (Menampilkan status real-time)
- **Breadboard & Kabel Jumper** (Koneksi rangkaian)
- **Baterai & Catu Daya** (Sumber daya sistem)
- **Arduino IDE** (Pemrograman & firmware)
- **Flutter & Firebase** (Pengembangan aplikasi seluler & database)

## 🚀 Cara Kerja

1. **Sensor kelembapan tanah mendeteksi kondisi tanah**.
2. **Aktivasi pompa:**
   - Jika kelembapan **di bawah 20%**, pompa menyala.
   - Jika kelembapan **di atas 40%**, pompa mati.
3. **Data ditampilkan** pada LCD dan dikirim ke Firebase.
4. **Pengguna memantau & mengontrol** sistem melalui aplikasi Blynk.

## 📊 Kondisi Ideal untuk Tanaman Hias

- **Kelembapan Tanah:** 21% - 40% (Najikh et al., 2018)
- **Suhu:** 27°C - 30°C (Siang), 21°C - 24°C (Malam) (AcuRite Team, 2022)
- **Kelembapan Udara:** 60% - 80% (AcuRite Team, 2022)

## 📈 Pengembangan di Masa Depan

- **Sistem Notifikasi:** Memberikan peringatan saat kelembapan tanah mencapai batas kritis.
- **Integrasi Energi Surya:** Meningkatkan efisiensi energi dengan panel surya.
- **Sensor Tambahan:** Menambahkan **sensor pH tanah** dan **sensor cahaya** untuk pemantauan lebih lanjut.
- **Peningkatan Keamanan:** Implementasi keamanan lebih baik pada Firebase untuk melindungi data pengguna.
- **Pengujian Lapangan:** Uji coba dalam skala lebih besar seperti lahan pertanian atau greenhouse.

## 📜 Kesimpulan

**Sistem Penyiraman Tanaman Otomatis** ini berhasil mengotomatiskan irigasi dengan memanfaatkan **teknologi IoT**. Dengan mengintegrasikan **NodeMCU ESP8266, Firebase, dan Flutter**, sistem ini memberikan solusi pertanian cerdas yang efisien dan dapat dikontrol dari jarak jauh.

---

🔗 **Dikembangkan sebagai bagian dari proyek penelitian IoT.**
