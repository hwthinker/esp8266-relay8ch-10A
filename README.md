# Modul ESP8266 ESP-12f Relay 8 Channel 10A 
![](https://github.com/hwthinker/esp8266-relay8ch-10A/blob/main/picture/1.png)

## Cara download dengan Serial USB biasa
![](https://github.com/hwthinker/esp8266-relay8ch-10A/blob/main/picture/2.png)
- Pasang serial USB TTL dengan ketentuan: 
   - TX Board-> RX USB Serial (Kabel Putih)
   - RX Board-> TX USB Serial (Kabel Hijau)
   - GND Board-> GND USB Serial (Kabel Hitam)
- Pasang jumper IO0 ke ground 
- Pasang Powersupply Ke Device dengan Jumper dalam keadaan terpasang
- Download program dan tunggu sampai selesai
- Lepas Jumper
- Cabut dan pasang Powersupply agar program yang barusan diupload di run device. ( penting❗)
- Ulangi langkah awal bila melakukan download ulang lagi

## Kode Program
- Kode program bisa dicek di link https://github.com/hwthinker/esp8266-relay8ch-10A/blob/main/src/main.cpp 

Warning:❗⚠️
Aktifkan daya untuk menghidupkan alat hanya dengan satu jenis sumber daya, bisa 9VDC atau 5VDC. Jangan menghubungkan beberapa sumber daya secara bersamaan, karena akan menyebabkan kerusakan pada alat.