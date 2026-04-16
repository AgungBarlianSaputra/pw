 1. Dropdown Selector
P (Point)
Dropdown selector adalah komponen antarmuka (UI) yang memungkinkan pengguna memilih satu atau lebih opsi dari daftar yang muncul ketika diklik.
R (Reason)
Komponen ini digunakan untuk:
Menghemat ruang tampilan (tidak semua opsi ditampilkan langsung)
Membantu user memilih dari pilihan yang sudah ditentukan
Menghindari input bebas yang bisa menyebabkan error
E (Example)
Contoh dalam HTML:
<select id="pilihan">
  <option value="1">Satu</option>
  <option value="2">Dua</option>
  <option value="3">Tiga</option>
</select>
Contoh penggunaan:
Pilih jurusan saat daftar kuliah
Pilih kategori produk di e-commerce
P (Point – Penegasan)
Jadi, dropdown selector adalah elemen penting dalam UI untuk mengontrol input pengguna secara terstruktur dan efisien.
2. Event Listener
P (Point)
Event listener adalah mekanisme dalam pemrograman yang digunakan untuk “mendengarkan” dan merespons suatu aksi (event) dari pengguna atau sistem.
R (Reason)
Event listener diperlukan karena:
Aplikasi modern bersifat interaktif
Program harus merespons aksi seperti klik, input, scroll, dll
Tanpa event listener, UI tidak akan responsif
E (Example)
Contoh JavaScript:
document.getElementById("pilihan").addEventListener("change", function() {
    alert("Pilihan berubah!");
});
Penjelasan:
"change" adalah event
Saat dropdown berubah → fungsi dijalankan
Contoh event lain:
click → saat tombol diklik
keyup → saat keyboard ditekan
mouseover → saat kursor diarahkan
P (Point – Penegasan)
Event listener adalah inti dari interaktivitas aplikasi karena memungkinkan sistem merespons aksi pengguna secara real-time.
3. Data Mining
P (Point)
Data mining adalah proses استخراج (penggalian) informasi atau pola penting dari kumpulan data besar menggunakan teknik statistik, machine learning, dan database.
R (Reason)
Data mining digunakan karena:
Data yang besar sulit dianalisis secara manual
Perusahaan butuh insight untuk pengambilan keputusan
Bisa menemukan pola tersembunyi (hidden pattern)
E (Example)
Contoh penerapan:
E-commerce:
→ Menyarankan produk berdasarkan riwayat belanja
Perbankan:
→ Deteksi transaksi mencurigakan (fraud)
Media sosial:
→ Rekomendasi konten sesuai minat user
Contoh sederhana:
Data: pembelian pelanggan
Hasil mining: “Orang yang beli A biasanya beli B”
Teknik yang digunakan:
Clustering (pengelompokan)
Classification (klasifikasi)
Association Rule (aturan keterkaitan)
P (Point – Penegasan)
Data mining membantu mengubah data mentah menjadi informasi bernilai yang bisa digunakan untuk keputusan strategis.
