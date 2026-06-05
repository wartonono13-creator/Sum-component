# Sum-component (Actuator Components)

[![GitHub license](https://shields.io)](https://github.com)
[![GitHub stars](https://shields.io)](https://github.com)

`Sum-component` adalah sebuah repositori pustaka (library) dan komponen siap pakai untuk mengendalikan berbagai macam perangkat **aktuator** dalam proyek IoT (Internet of Things), robotika, dan sistem tertanam (embedded systems). 

Komponen ini dirancang untuk mempermudah integrasi mikrokontroler (seperti Arduino, ESP32, atau Raspberry Pi) dengan perangkat fisik yang menghasilkan gerakan, suara, atau perubahan fisik lainnya.

---

## 🚀 Fitur Utama (Daftar Aktuator)

Repositori ini menyediakan modul kode, skematik, dan pustaka untuk aktuator berikut:
* **Motor Driver**: Kontrol kecepatan dan arah untuk Motor DC, Servo, dan Stepper (e.g., L298N, SG90, Nema 17).
* **Relay Module**: Sakelar elektronik untuk mengontrol perangkat bertegangan tinggi (AC/DC).
* **Solenoid Valve / Lock**: Kontrol katup aliran air dan pengunci pintu elektronik.
* **Buzzer & Audio**: Penghasil suara peringatan menggunakan Piezo Buzzer (Aktif/Pasif).
* **Indikator Visual**: Driver untuk LED Strip, RGB LED, dan display berbasis aktuasi cahaya.

---

## 🛠️ Prasyarat & Instalasi

### Kebutuhan Perangkat Lunak
* IDE (Arduino IDE / VS Code dengan PlatformIO)
* Bahasa pemrograman: C++ / Python (MicroPython)

### Cara Penggunaan
1. Kloning repositori ini ke komputer Anda:
   ```bash
   git clone https://github.com
   ```
2. Buka folder komponen aktuator yang Anda butuhkan (misal: `/components/servo-motor`).
3. Jalankan file contoh (`example.ino` atau `main.py`) ke mikrokontroler Anda.

---

## 📐 Contoh Skema Koneksi (Wiring)

Berikut adalah contoh dasar koneksi aktuator Servo ke Mikrokontroler:


| Aktuator (Servo) | Mikrokontroler (e.g., ESP32) |
| ---------------- | ---------------------------- |
| Kabel Merah (VCC)| 5V                           |
| Kabel Cokelat(GND)| GND                          |
| Kabel Oranye(PWM)| GPIO 18                      |

---

## 🤝 Kontribusi

Kontribusi sangat terbuka untuk menambahkan jenis aktuator baru!
1. Fork repositori ini.
2. Buat branch fitur baru (`git checkout -b fitur/aktuator-baru`).
3. Commit perubahan Anda (`git commit -m 'Menambahkan driver aktuator X'`).
4. Push ke branch tersebut (`git push origin fitur/aktuator-baru`).
5. Buat Pull Request.

---

## 📄 Lisensi

Proyek ini dilisensikan di bawah Lisensi MIT - lihat file [LICENSE](LICENSE) untuk detailnya.
