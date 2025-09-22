Image Point Processing Scripts 🖼️
Koleksi skrip Python sederhana untuk melakukan operasi point processing dasar pada gambar. Setiap skrip dirancang untuk berjalan secara mandiri di lingkungan Google Colab.

Deskripsi
Proyek ini berisi beberapa skrip individual di mana setiap skrip menerapkan satu jenis transformasi piksel pada gambar yang diunggah oleh pengguna. Tujuannya adalah untuk mendemonstrasikan efek dari berbagai operasi matematika dasar pada data citra digital.

Setiap skrip akan:

Meminta pengguna untuk mengunggah sebuah file gambar.

Memproses gambar tersebut sesuai dengan fungsinya.

Menampilkan gambar hasil olahan.

Fitur dan Efek yang Tersedia ✨
Berikut adalah daftar efek point processing yang telah diimplementasikan:

Original: Menampilkan gambar asli tanpa perubahan.

Darken: Mengurangi intensitas kecerahan setiap piksel secara merata.

Lighten: Menambah intensitas kecerahan setiap piksel secara merata.

Invert: Membalikkan nilai warna setiap piksel untuk menciptakan efek negatif film.

Lower Contrast: Mengurangi rentang antara area gelap dan terang (linear).

Raise Contrast: Meningkatkan rentang antara area gelap dan terang (linear).

Nonlinear Lower Contrast: Mengurangi kontras menggunakan koreksi gamma (gamma>1.0).

Nonlinear Raise Contrast: Meningkatkan kontras menggunakan koreksi gamma (gamma<1.0).

Cara Penggunaan 🚀
Setiap skrip di repositori ini dapat dijalankan secara terpisah.

Pilih Efek: Tentukan efek mana yang ingin Anda coba.

Buka Google Colab: Kunjungi colab.research.google.com dan buat notebook baru.

Salin Kode: Salin seluruh kode dari skrip yang Anda pilih (misalnya, kode untuk efek Darken).

Tempel & Jalankan: Tempelkan kode tersebut ke dalam sebuah sel di Google Colab, lalu jalankan sel dengan menekan tombol Play (▶️) atau Ctrl+Enter.

Unggah Gambar: Saat diminta, klik tombol Choose Files dan pilih sebuah gambar dari komputer Anda.

Lihat Hasil: Hasil gambar yang telah diproses akan ditampilkan di output sel.

Teknologi yang Digunakan 🛠️
Python 3

Google Colab

NumPy: Untuk operasi numerik pada array piksel.

Matplotlib: Untuk menampilkan gambar.

Pillow (PIL): Untuk membaca data gambar yang diunggah.
