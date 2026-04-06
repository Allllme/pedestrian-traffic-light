# Pedestrian Traffic Light — Arduino UNO

Simulasi sistem lampu penyebrang jalan menggunakan
Arduino UNO dan Tinkercad.

## Deskripsi
Sistem ini memodifikasi traffic light 4 simpang
dengan menambahkan 2 lampu pedestrian dan tombol
interrupt untuk pejalan kaki.

## Komponen
| Pin | Komponen     | Fungsi             |
|-----|--------------|--------------------|
| 13  | LED Merah    | Lampu kendaraan    |
| 12  | LED Kuning   | Fase transisi      |
| 11  | LED Hijau    | Lampu kendaraan    |
| 10  | LED Merah    | Lampu pedestrian   |
|  9  | LED Hijau    | Lampu pedestrian   |
|  2  | Push Button  | Interrupt sisi 2   |

## Cara Kerja
1. Kondisi awal: lampu kendaraan **hijau**, pedestrian **merah**
2. Tombol ditekan → lampu kendaraan **merah**, pedestrian **hijau** (3 detik)
3. Lampu kuning **berkedip** 3x sebagai transisi
4. Kembali ke kondisi awal

## Simulasi
Dibuat menggunakan [Tinkercad](https://www.tinkercad.com/things/4cwDQSQ1Xp9-pedestrian-traffic-light?sharecode=b6-AOKwL_aHeE0PRRJqsj6ZzXeSOJjKxU8faOhq8Owk)
