
Template Tugas Akhir/Skripsi FTIS 

versi terbaru : v9 (31-05-2015)
terdiri dari : main.tex versi 8, data.tex versi 6 dan dosen.tex versi 4

Silahkan (berjuang untuk) menggunakan template skripsi/tugas akhir FTIS yang dibuat oleh lionov.
Pertanyaan terkait template dapat diajukan melalui email ke lionov@unpar.ac.id/lionov@gmail.com atau datang langsung ke ruang 9110.
PERTANYAAN TERKAIT LATEX DAPAT DIAJUKAN KEPADA PEMBIMBING MASING-MASING ATAU MENCARI TAHU SENDIRI JAWABANNYA MELALUI INTERNET.

Perhatian !! :
- Skripsi yang tertulis di tempalte ini adalah CONTOH, sekali lagi : HANYA CONTOH !!!!!, jadi jangan mengikuti cara penulisan atau
  cara penempatan lampiran (mis: B untuk source code program). Tanyakan kepada pembimbing masing-masing
- File main.tex SANGAT dianjurkan untuk TIDAK DIUBAH, kecuali anda tahu persis apa yang anda lakukan.
  File tersebut adalah file tex utama yang harus anda compile menggunakan pdflatex, agar menghasilkan dokumen pdf yang sesuai.
  Isi dari file main.tex adalah : 
  - perintah-perintah khusus yg digunakan di template ini
  - berisi seluruh halaman depan dari dokumen skripsi: sampul, lembar pengesahan, lembar pernyataan, abstrak, abstract, 
  lembar persembahan, kata pengantar, daftar isi, daftar gambar dan daftar tabel. 
   
Cara menggunakan :
0. Perhatikan instruksi yang ada di file main.tex, data.tex dan dosen.tex. Instruksi2 tersebut ada di awal file
1. Masukkan data-data yang dibutuhkan ke dalam file data.tex. Keterangan untuk setiap data ada di dalam file tersebut.
2. Tuliskan isi dari setiap bab di dalam file bab (bab1.tex, bab2.tex, dst) yang telah disediakan di dalam direktori "Bab".
   Jangan melakukan perubahan pada nama file tersebut dan biarkan bab yang tidak dipakai.
3. Jika ada file gambar (jpg, bmp, pdf, png, dll) dapat disimpan di direktori "Gambar"
4. Tuliskan isi dari lampiran di dalam file lampiran (lampA.tex, lampB.tex, dst) yang telah disediakan di dalam direktori "Lampiran"
5. File pdf dapat dihasilkan dengan melakukan kompilasi (menggunakan pdflatex) pada FILE UTAMA: main.tex

/*==================================================== !!! NEW !!! ======================================================*/
Cara melakukan update apabila ada template dengan versi lebih baru
0. Perhatikan versi dari file dosen.tex, main.tex dan data.tex
1. Apabila ada versi yang lebih baru dari file yang anda gunakan, maka perlu dilakukan update
2. Timpa (overwrite) file versi lama dengan file yang lebih baru :
   - dosen.tex	: overwrite langsung
   - main.tex	: jika anda melakukan penambahan/perubahan, simpan perubahan, overwrite dan lakukan perubahan di file yang baru
   - data.tex  	: jika anda melakukan penambahan/perubahan, simpan perubahan, overwrite dan lakukan perubahan di file yang baru
3. Jalankan lagi pdflatex untuk mendapatkan dokumen yang terbaru
/*==================================================== !!! NEW !!! ======================================================*/

CATATAN versi 9: (13-04-2015)
Perubahan main.tex ke versi 8 dan data.tex ke versi 6 untuk mengakomodasi kebutuhan akreditasi, dimana template sebaiknya
tidak merujuk kepada pekerjaan seseorang tetapi dibuat lebih generik

CATATAN versi 8: (27-05-2014)
Perubahan main.tex ke versi 7

CATATAN versi 7: (01-04-2014)
Perubahan dosen.tex ke versi 4

CATATAN versi 6: (10-11-2013)
Perubahan versi ke angka desimal untuk memudahkan pengguna saat menggunakan template yang paling mutakhir
Perbaikan minor untuk paragraf pada abstrak, penulisan halaman romawi genap, instruksi untuk memasukkan bab dan lampiran
Perbaikan data dosen
Penambahan petunjuk cara memperbaharui template jika ada versi yang lebih baru 

CATATAN versi 5: (25-02-2013)
Perbaikan data dosen dan keterangan dosen di dosen.tex

CATATAN versi 4:
Halaman terakhir pada bab jika tidak ada isinya dan terletak di sebelah kiri, dikosongkan header-nya (usul dari Ibu Erwinna dan Ibu Ivonne)
Data dosen dipisahkan ke file dosen.tex sehingga jika dilakukan perubahan pada data dosen, mahasiswa tidak perlu mengganti file data.tex

CATATAN versi 3:
Perubahan yang cukup signifikan adalah ditambahkannya halaman dengan judul bahasa inggris, 
jadi di dokumen final, di halaman bagian dalam terdapat 2 buah halaman judul, dalam bahasa indonesia dan dalam bahasa inggris.
Untuk menggunakan versi 1.0, yang harus anda lakukan adalah mengubah isi direktori Bab, Gambar dan Lampiran dengan yang sudah anda buat
dan mengisikan kembali data-data di file data.tex dengan data yang sudah anda isikan sebelumnya di file data.tex yang lama

CATATAN versi 1 dan 2
Belum ada READ_ME_FIRST_!!!!!!.txt