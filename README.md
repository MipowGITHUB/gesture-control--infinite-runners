# gesture-control--infinite-runners

Proyek ini menggunakan **MediaPipe** dan **OpenCV** untuk mendeteksi gerakan tangan pengguna dan mengontrol permainan Subway Surfers menggunakan **PyAutoGUI**. Dengan mendeteksi gesture tangan, pemain dapat mengendalikan karakter dalam game seperti **melompat**, **berbelok kiri/kanan**, dan **merunduk**.

## Fitur
- **Telapan Tangan Terbuka (5 jari terbuka)**: Karakter **melompat** (UP).
- **Telapak Tangan Tertutup (semua jari tertutup)**: Karakter **merunduk** (DOWN).
- **Jempol diangkat (1 ibu jari terbuka)**: Karakter bergerak ke **kiri** (LEFT).
- **Kelingking diangkat (1 kelingking terbuka)**: Karakter bergerak ke **kanan** (RIGHT).

## Teknologi yang Digunakan
- **OpenCV**: Untuk memproses video dan menangkap gambar dari kamera.
- **MediaPipe**: Untuk mendeteksi landmark tangan dan posisi jari.
- **PyAutoGUI**: Untuk mengirimkan perintah keyboard berdasarkan gerakan tangan.

## Persyaratan
Sebelum menjalankan proyek ini, pastikan kamu telah menginstal paket-paket berikut:
- Python 3.x
- OpenCV
- MediaPipe
- PyAutoGUI

### Instalasi
1. Clone repositori ini:
   ```bash
   git clone https://github.com/username/gesture-control-subway-surfers.git
   cd gesture-control-subway-surfers
