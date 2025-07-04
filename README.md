# 🚀 Proyek Sensor IR dan Servo dengan ESP8266

Sistem ini menggunakan **ESP8266**, dua **sensor inframerah (IR)**, dan dua **servo motor** untuk mendeteksi objek dan menggerakkan servo secara otomatis. Cocok untuk proyek otomatisasi kecil seperti pintu otomatis, penyortiran barang, atau sistem deteksi gerakan.

---

## 🔧 Fitur

- Deteksi objek menggunakan sensor IR
- Gerakan servo otomatis berdasarkan deteksi
- Feedback real-time melalui Serial Monitor
- Respons cepat & efisien

---

## 🧰 Komponen yang Dibutuhkan

| Komponen            | Jumlah |
|---------------------|--------|
| ESP8266 (NodeMCU)   | 1      |
| Sensor IR           | 2      |
| Servo Motor (SG90/MG90) | 2  |
| Kabel Jumper        | Beberapa |
| Breadboard (opsional)| 1     |
| Power Supply Eksternal (disarankan untuk servo) | 1 |

---

## 🔌 Skema Koneksi

| Komponen       | Pin ESP8266 |
|----------------|-------------|
| Sensor IR 1 OUT| D1 (GPIO5)  |
| Sensor IR 2 OUT| D2 (GPIO4)  |
| Servo 1 Signal | D5 (GPIO14) |
| Servo 2 Signal | D6 (GPIO12) |

> ⚠️ **Catatan:** Gunakan catu daya eksternal untuk servo agar menghindari gangguan atau restart pada ESP8266.

---

