# smart-trash-bin-iot
Smart Trash Bin berbasis IoT dengan sistem pengunci otomatis menggunakan ESP32
# Smart Trash Bin IoT

## 📌 Deskripsi Proyek
Smart Trash Bin IoT merupakan sistem tempat sampah pintar berbasis Internet of Things (IoT) yang dirancang untuk memonitor kapasitas sampah secara realtime menggunakan sensor ultrasonik dan mikrokontroler ESP32.

Sistem ini dilengkapi dengan fitur pengunci otomatis menggunakan servo motor ketika kapasitas tempat sampah telah penuh. Informasi kapasitas dan status tempat sampah ditampilkan pada LCD dan dashboard monitoring berbasis IoT.

---

# 🎯 Tujuan Proyek
- Monitoring kapasitas tempat sampah secara realtime
- Mengurangi sampah meluap
- Membantu petugas kebersihan
- Membuat sistem tempat sampah otomatis dan modern

---

# ⚙️ Fitur Utama
✅ Monitoring kapasitas realtime  
✅ LCD display status tempat sampah  
✅ Dashboard monitoring IoT  
✅ Sistem pengunci otomatis saat penuh  
✅ Tombol unlock manual untuk petugas  
✅ Alarm buzzer saat kapasitas penuh  

---

# 🧰 Komponen yang Digunakan

| Komponen | Fungsi |
|---|---|
| ESP32 DevKit | Mikrokontroler utama |
| HC-SR04 | Sensor ultrasonik |
| LCD 16x2 I2C | Menampilkan status |
| Servo SG90 | Sistem pengunci |
| Push Button | Tombol unlock |
| Buzzer | Alarm kapasitas penuh |

---

# 🔄 Cara Kerja Sistem
1. Sensor ultrasonik membaca kapasitas sampah.
2. ESP32 menghitung persentase kapasitas.
3. Data ditampilkan pada LCD dan dashboard IoT.
4. Jika kapasitas lebih dari 80%:
   - servo mengunci tempat sampah,
   - buzzer aktif,
   - status FULL ditampilkan.
5. Petugas dapat membuka kunci menggunakan push button.

---

