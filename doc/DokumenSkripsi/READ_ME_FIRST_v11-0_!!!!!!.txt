
                   TEMPLATE TUGAS AKHIR / SKRIPSI FTIS UNPAR 
			   versi: 11.0 (08-10-2016)

===============================================================================
				0. SELAMAT DATANG
===============================================================================
Silahkan (berjuang untuk) menggunakan Template Skripsi/tugas akhir FTIS UNPAR yang dibuat oleh Lionov.
Pertanyaan terkait template dapat diajukan melalui email ke lionov@unpar.ac.id / lionov@gmail.com 
atau datang langsung ke ruang 4.21, BuysBallotGebouw, Universiteit Utrecht, Princetonplein 5 3584CC Utrecht, Belanda.
PERTANYAAN TERKAIT LATEX DAPAT DIAJUKAN KEPADA PEMBIMBING MASING-MASING ATAU MENCARI TAHU SENDIRI JAWABANNYA MELALUI INTERNET.
Penggunaan oleh mahasiswa non FTIS UNPAR, harap memberitahu terlebih dahulu ke alamat email di atas.


===============================================================================
				1. VERSI
===============================================================================

Mulai versi 11.0 ini, penomoran versi mengikuti pola X.Y
- Perubahan pada bagian X menandakan bahwa ada perubahan fundamental pada template skripsi
dan seluruh mahasiswa diwajibkan menggunakan versi terbaru tersebut
- Perubahan pada bagian Y menandakan bahwa ada perubahan pada data dosen atau pada contoh skripsi, 
sehingga mahasiswa yang pembimbing/penguji atau kaprodinya tidak berubah tidak perlu menggunakan versi tersebut.

Contoh: Setelah versi 11.0, kemungkinan versi berikutnya adalah:
- 12.0 -> ada perubahan pada skripsi.tex/data.tex, semua mahasiswa wajib menggunakan versi ini
- 11.1 -> ada perubahan pada dosen.tex atau pada contoh skripsi, periksa perubahan dosen,
jika pembimbing/penguji/kaprodi ada yang berubah, dianjurkan menggunakan dosen.tex yang baru.
Catatan: data dosen hanya akan diperbaharui sebelum semester dimulai, jika ada perubahan dosen
di tengah semester, mohon memperbaharui sendiri data di dosen.tex 

Versi: 11.0 (08-10-2016)
terdiri dari : 
- skripsi.tex (v.10) (02-10-2016): sebelumnya bernama main.tex
- data.tex (v.8) (02-10-2016)
- dosen.tex (v.6) (19-08-2016)
- referensi.bib (v.2) (03-10-2016): sebelumnya bernama pustaka.tex
- bab/lampiran (v.2) (08-10-2016)

Catatan Penting pada versi 11 (detail di masing2 file):
0. Perbaikan pada "Daftar Isi" tidak di tengah halaman !!!
1. Perubahan nama main.tex menjadi skripsi.tex
2. Perubahan data dosen (MHS T. INFORMATIKA WAJIB MELIHAT!)
3. Perubahan style bibliography dari "ieeetr" menjadi "compj" !!
4. Petunjuk singkat pembuatan daftar referensi yang lebih "serius" (dari biasanya) 
5. Perbaikan READ_ME_FIRST_vXX_!!!!!!.txt
6. Catatan perubahan versi sebelumnya dari setiap file dipindahakan seluruhnya ke dalam file ini :D
7. Perubahan pengaturan versi
8. Perubahan spacing: \onespacing utnuk buku final dan \onehalfspacing untuk buku sidang

Catatan khusus:
Perubahan nama dari main.tex ke skripsi.tex dan melakukan kompilasi dari skripsi.tex semestinya tidak akan menimbulkan masalah.
Jika ternyata terjadi masalah terkait project di tools pengolah LaTeX anda, ubah nama skripsi.tex menjadi main.tex
dan gunakan main.tex yang baru sebagai file utama anda.


===============================================================================
				2. PERHATIAN !!!
===============================================================================
- Teks yang tertulis di template ini adalah CONTOH, sekali lagi: HANYA CONTOH !!!!!, jadi jangan mengikuti cara penulisan atau
  cara penempatan lampiran (mis: B untuk source code program). Tanyakan kepada pembimbing masing-masing
- File skripsi.tex SANGAT dianjurkan untuk TIDAK DIUBAH, kecuali anda tahu persis apa yang anda lakukan.
  File tersebut adalah file tex utama yang harus anda compile menggunakan pdflatex, agar menghasilkan dokumen pdf yang sesuai.
  Isi dari file skripsi.tex adalah: 
  - perintah-perintah khusus yg digunakan di template ini
  - berisi seluruh halaman depan dari dokumen skripsi: sampul, lembar pengesahan, lembar pernyataan, abstrak, abstract, 
  lembar persembahan, kata pengantar, daftar isi, daftar gambar dan daftar tabel. 


===============================================================================
				3. CARA PENGGUNAAN
===============================================================================
0. Perhatikan instruksi yang ada di file skripsi.tex, data.tex dan dosen.tex. Instruksi2 tersebut ada di bagian awal file
   Di dalam file referensi.tex, terdapat petunjuk penggunaan, harap diperhatikan dengan seksama. 
1. Masukkan data-data yang dibutuhkan ke dalam file data.tex. Keterangan untuk setiap data ada di dalam file tersebut.
JIKA anda ingin menambahkan perintah sendiri ke dalam template ini, SANGAT DIANJURKAN untuk melakukannya di bagian XV pada
file data.tex, sehingga jika terjadi update ke versi yang lebih baru pada file lain, tidak akan menganggu.
2. Jika perlu, masukkan data dosen yang belum ada ke dalam file dosen.tex atau melakukan perubahan seperlunya 
(pergantian ketua program studi atau ada perubahan gelar akademik) 
3. Tuliskan isi dari setiap bab di dalam file bab (bab1.tex, bab2.tex, dst) yang telah disediakan di dalam direktori "Bab".
   Jangan menghapus atau melakukan perubahan pada nama file dan pastikan file bab yang tidak digunakan tidak berisi apapun.
4. Jika ada file gambar (jpg, bmp, pdf, png, dll) dapat disimpan di direktori "Gambar"
5. Tuliskan isi dari lampiran di dalam file lampiran (lampA.tex, lampB.tex, dst) yang telah disediakan di dalam direktori "Lampiran"
   Jangan menghapus atau melakukan perubahan pada nama file dan pastikan file lampiran yang tidak digunakan tidak berisi apapun.
6. File pdf dapat dihasilkan dengan melakukan kompilasi (menggunakan pdflatex) pada FILE UTAMA: skripsi.tex 
(atau tergantung IDE yang digunakan, pada beberapa kasus, kompilasi dapat dilakukan di file mana saja untuk menghasilkan file PDF)


===============================================================================
				4. CARA MELAKUKAN UPDATE 
===============================================================================
Cara melakukan update apabila ada template dengan versi lebih baru
Perhatikan versi yang anda gunakan dan versi terbaru (versi X.Y). Jika terjadi perubahan di bagian X,
maka wajib menggunakan versi terbaru. Jika perubahan hanya pada bagian Y, hanya perlu memeriksa file dosen.tex.
Perubahan pada file referensi.bib atau contoh di bab/lampiran tidak berpengaruh pada isi dokumen skripsi anda.

Jika akan melakukan update:
1. PASTIKAN anda melakukan back-up untuk semua file yang akan anda perbaharui !!!!!
2. Timpa (overwrite) file versi lama dengan file yang lebih baru:
   	- dosen.tex	: overwrite langsung
   	- skripsi.tex	: jika anda melakukan penambahan/perubahan, simpan perubahan, overwrite dan lakukan perubahan di file yang baru
   	- data.tex  	: jika anda melakukan penambahan/perubahan, simpan perubahan, overwrite dan lakukan perubahan di file yang baru
3. Jalankan lagi pdflatex untuk mendapatkan dokumen pdf yang terbaru


===============================================================================
				5. PERANGKAT LUNAK 
===============================================================================
Template Skripsi FTIS versi 11.0 ini dibuat dengan:
- Windows 10 Pro 64-bit
- TeX 3.14159265 (MiKTeX 2.9 64-bit)
- pdfTeX 3.14159265-2.6-1.40.16 (MiKTeX 2.9 64-bit)
- TexStudio 2.11.2
- EmEditor Free (64-bit) 15.6.1

===============================================================================
				6. DAFTAR ISI 
===============================================================================
Template ini terdiri dari:
- READ_ME_FIRST_v11-0_!!!!!!.txt
- skripsi.tex
- skripsi.pdf
- dosen.tex
- data.tex
- referensi.bib
- Bab/bab1.tex
- Bab/bab2.tex
- Gambar/logo-unpar.png
- Gambar/ular-jpg.jpg
- Gambar/ular-png.png
- Gambar/ular-pdf.pdf
- Lampiran/lampA.tex
- Lampiran/lampB.tex
- compj.bst (diambil dari computer journal)


===============================================================================
				7. DAFTAR CATATAN PERUBAHAN 
===============================================================================

CATATAN Versi 10 (30-11-2015)
terdiri dari:
- main.tex (v.9) (30-11-2015)
- data.tex (v.7) (30-11-2015)
- dosen.tex (v.5) (30-11-2015)

Perubahan pada:
- main.tex (v.9) (30-11-2015)
	- bagian untuk menambahkan perintah sendiri dipindahkan ke data.tex
	- bagian untuk mengatur kemunculan daftar gambar dan daftar tabel, dipindahkan
	  ke data.tex
	- penambahan bagian untuk mengatur perbedaan pdfTeX, masalah hfill dgn hfil (Trims u/ Pascal)
	- bagian pengesahan diatur agar lebih rapi 
- data.tex (v.7) (30-11-2015)
	- Perubahan nomor bagian karena penyisipan Bagian V
	- Penambahan Bagian V: pengaturan kemunculan daftar gambar dan/atau tabel dipindahkan dari main.tex
	- Penambahan Bagian XV: tempat untuk menambahkan perintah yang dibuat sendiri, dipindahkan dari main.tex
	- Penambahan Bagian 0: perintah bagi yang caption daftar isi tidak bisa ke bagian tengah
- dosen.tex (v.5) (30-11-2015)
 	- Perubahan ketua jurusan matematika menjadi JDL
 	- Perubahan ketua jurusan teknik informatika menjadi MAR
	- Penghapusan dosen (Hariman,Farica,Lukcy,Verli,Wahyu)
	- Penambahan dosen (Risti, Bagoes, Reinard, Haryanto)
	- Perbaikan gelar (Ferry, Rusli, Fla, Kian Ming, Wono, Gede, Pascal)
	- Penggunaan thin-space untuk spasi pada nama, agar tidak terpotong

Catatan penting:
1. Perubahan main.tex ke versi 9, data.tex ke versi 7 dan dosen.tex ke versi 5 
2. update data dosen dan sedapatnya membuat mahasiswa tidak melakukan perubahan di main.tex
_______________________________________________________________________________
===============================================================================

CATATAN Versi 9 (31-05-2015)
terdiri dari:
- main.tex (v.8) (31-05-2015)
- data.tex (v.6) (13-04-2015)
- dosen.tex (v.4)

Perubahan pada:
- main.tex (v.8) (31-05-2015)
	- penambahan default data untuk beberapa keterangan dan digunakan sebagai template dengan tanda << & >> . 
	  Data yang diubah defaultnya adalah: nama skripsi, nama prodi, beserta bahasa inggrisnya.
   	- Keywords dan kata kunci di abstrak ditambahkan noindent + perbaikan lainnya
   	- Perbaikan untuk halaman tidak kosong tanpa nomor halaman romawi
- data.tex (v.6) (13-04-2015)
 	- Perubahan untuk data-data ``template" menjadi lebih generik dan menggunakan tanda << dan >>

Catatan penting:
1. Perubahan main.tex ke versi 8 dan data.tex ke versi 6 untuk mengakomodasi kebutuhan akreditasi, 
dimana template sebaiknya tidak merujuk kepada pekerjaan seseorang tetapi dibuat lebih generik
_______________________________________________________________________________
===============================================================================

CATATAN Versi 8 (27-05-2014)
terdiri dari:
- main.tex (v.7) (27-05-2014)
- data.tex (v.5) 
- dosen.tex (v.4)

Perubahan pada:
- main.tex (v.7) (27-05-2014)
	- penambahan perintah \raggedbottom untuk menghilangkan area kosong akibat 
	  penempatan gambar yang tidak sempurna

Catatan penting:
1. Perubahan main.tex ke versi 7
_______________________________________________________________________________
===============================================================================

CATATAN Versi 7 (01-03-2014)
terdiri dari:
- main.tex (v.6)
- data.tex (v.5) 
- dosen.tex (v.4) (01-03-2014)

Perubahan pada:
- dosen.tex (v.4) (01-03-2014)
 	- Perubahan ketua jurusan teknik informatika menjadi TAB
	- Penambahan dosen jurusan informatika (Lucky)

Catatan penting:
1. Perubahan dosen.tex ke versi 4
_______________________________________________________________________________
===============================================================================

CATATAN Versi 6 (10-11-2013)
terdiri dari:
- main.tex (v.6) (10-11-2013)
- data.tex (v.5) (10-11-2013)
- dosen.tex (v.3) (10-11-2013)

Perubahan pada:
- main.tex (v.6) (10-11-2013)
	- perbaikan pada abstract dengan paragraf lebih dari satu: perbaikan vertical spacing
	- perbaikan pada tampilan bab dan lampiran: tidak perlu menuliskan apapun untuk menampilkan semuanya (di data.tex) 
	  atau -1 jika tidak ada lampiran
	- halaman bernomor genap untuk halaman romawi sudah dimunculkan
	- Kurikulum 2013: perubahan nama buku skripsi 
- data.tex (v.5) (10-11-2013)
 	- Perbaikan pada memasukkan bab: tidak perlu menuliskan apapun untuk memasukkan seluruh bab (bagian V)
 	- Perbaikan pada memasukkan lampiran: tidak perlu menuliskan apapun untuk memasukkan seluruh lampiran 
	  atau -1 jika tidak memasukkan apapun
- dosen.tex (v.3) (10-11-2013)
 	- Perubahan ketua jurusan teknik informatika menjadi MAR
	- Penambahan dosen jurusan informatika (Joanna, Wahyu)
	- Penghapusan dosen informatika (Lucky, Dharu)

Catatan penting:
1. Perubahan versi ke angka desimal untuk memudahkan pengguna saat menggunakan template yang paling mutakhir
2. Perbaikan minor untuk paragraf pada abstrak, penulisan halaman romawi genap, instruksi untuk memasukkan bab dan lampiran
3. Perbaikan data dosen
4. Penambahan petunjuk cara memperbaharui template jika ada versi yang lebih baru 
_______________________________________________________________________________
===============================================================================

CATATAN Versi 5 (25-02-2013)
terdiri dari:
- main.tex (v.5) (25-02-2013)
- data.tex (v.4) 
- dosen.tex (v.2) (25-02-2013)

Perubahan pada:
- main.tex (v.5) (25-02-2013)
	- perbaikan minor (layout)
- dosen.tex (v.2) (25-02-2013)
 	- Tambahan catatan untuk mhs T. Inf. terkait dosen yg tidak bisa menjadi pemb.
 	- Update data gelar untuk Taufik (MAT)
 	- Penambahan baru (Farica-Fisika, Husnul-T.Informatika)
 	- Dosen keluar atau tidak menjadi pembimbing lagi (Nisa, Ghifary)

Catatan penting:
1. Perbaikan data dosen dan keterangan dosen di dosen.tex
_______________________________________________________________________________
===============================================================================

CATATAN Versi 4 (21-10-2012)
terdiri dari:
- main.tex (v.4) (21-10-2012)
- data.tex (v.4) (21-10-2012)
- dosen.tex (v.1) (21-10-2012)

Perubahan pada:
- main.tex (v.4) (21-10-2012)
	- halaman terakhir setiap bab tidak ada headernya jika kosong
- data.tex (v.4) (21-10-2012)
	- Data dosen dipindah ke dosen.tex agar jika ada perubahan/update data dosen, mahasiswa tidak perlu mengubah data.tex
	- Perubahan pada keterangan dosen
- dosen.tex (v.1) (21-10-2012)
 	- Data dosen dipindah dari data.tex agar jika ada perubahan/update data dosen mahasiswa tidak perlu mengubah data.tex
 	- Beberapa dosen Informatika yang tidak boleh menjadi pembimbing digantikan OSS
 	- Update data gelar untuk Maria (MAT)
 	- Penambahan baru (Flaviana-Fisika, Elok-Fisika)
 	- Dosen keluar atau tidak menjadi pembimbing lagi (Monika, David)

Catatan penting:
1. Halaman terakhir pada bab jika tidak ada isinya dan terletak di sebelah kiri, dikosongkan header-nya (usul dari Erwinna dan Ivonne)
2. Data dosen dipisahkan ke file dosen.tex sehingga jika dilakukan perubahan pada data dosen, mahasiswa tidak perlu mengganti file data.tex
_______________________________________________________________________________
===============================================================================

CATATAN Versi 3 (06-08-2012)
terdiri dari:
- main.tex (v.3) (06-08-2012)
- setup.tex: hilang, digabung dengan main.tex
- data.tex (v.3) (06-08-2012)
- depan.tex: hilang, digabung dengan main.tex

Perubahan pada:
- main.tex (v.3) (06-08-2012)
 	- penggabungan main.tex, depan.tex dan setup.tex menjadi main.tex
 	- menambahkan keterangan di lampiran untuk kode program 
 	- ukuran font dapat diubah langsung di tiap lampiran
- data.tex (v.3) (06-08-2012)
	- Perubahan pada beberapa keterangan 

Catatan penting:
1. Perubahan yang cukup signifikan adalah ditambahkannya halaman dengan judul bahasa inggris, 
jadi di dokumen final, di halaman bagian dalam terdapat 2 buah halaman judul, dalam bahasa indonesia dan dalam bahasa inggris.
2. Untuk menggunakan versi 1.0, yang harus anda lakukan adalah mengubah isi direktori Bab, Gambar dan Lampiran dengan yang sudah anda buat
dan mengisikan kembali data-data di file data.tex dengan data yang sudah anda isikan sebelumnya di file data.tex yang lama
3. Penyediaan READ_ME_FIRST_vXX_!!!!!!
_______________________________________________________________________________
===============================================================================

CATATAN Versi 2 (09-07-2012)
- main.tex (v.2) (08-07-2012)
- setup.tex (v.2) (08-07-2012)
- data.tex (v.2) (09-07-2012)
- depan.tex (v.2) (09-07-2012)

Perubahan pada:
- main.tex (v.2) (08-07-2012)
 	- "Daftar Referensi" tidak perlu diubah secara manual (tidak perlu mengubah file bahasai.ldf)
 	- Bahasa Indonesia dari abstract adalah abstrak (secara otomatis), bukan ringkasan
 	- Spasi pada buku dokumen final adalah onehalfspacing
- setup.tex (v.2) (08-07-2012)
	- Menambahkan perintah untuk judulINA dan judulENG
	- Menghapus \usepackage{microtype}, yang pada beberapa kasus menjadi masalah
- data.tex (v.2) (09-07-2012)
	- Menambahkan data judul dalam bahasa inggris
	- Membuat bagian khusus untuk judul (bagian VIII)
	- Perbaikan pada gelar dosen
- depan.tex (v.2) (09-07-2012) 
	- Menambahkan halaman depan dalam bahasa inggris
_______________________________________________________________________________
===============================================================================

CATATAN Versi 1 (08-11-2011)
- main.tex (v.1) (08-11-2011)
- setup.tex (v.1) (08-11-2011)
- data.tex (v.1) (08-11-2011)
- depan.tex (v.1) (08-11-2011)

Catatan penting:
1. Pertama kali dirilis tanggal 08-11-2011, setelah berjuang karena melihat tata tulis yang "amburadul". 
2. Belum ada READ_ME_FIRST_!!!!!!.txt
_______________________________________________________________________________
===============================================================================

Copyright \textcopyright [Lionov] [09-10-2016]. All rights reserved
