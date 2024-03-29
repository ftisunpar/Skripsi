
        TEMPLATE SKRIPSI / TUGAS AKHIR FTIS UNPAR 
            http://tiny.cc/templateSkripsiFTIS
			   versi: 13.1 (01-09-2021)

===============================================================================
				0. SELAMAT DATANG
===============================================================================
Silahkan (berjuang untuk) menggunakan Template Skripsi/Tugas Akhir FTIS UNPAR 
yang dibuat oleh Lionov.

Pertanyaan terkait template dapat diajukan melalui email ke lionov@unpar.ac.id 
atau ke lionov@gmail.com 
atau datang langsung ke ruang 9123 Gedung 9 UNPAR Ciumbuleuit 94 Bandung 

PERTANYAAN TERKAIT LATEX DAPAT DIAJUKAN KEPADA PEMBIMBING MASING-MASING 
ATAU MENCARI TAHU SENDIRI JAWABANNYA MELALUI INTERNET.

Penggunaan oleh mahasiswi/a non FTIS UNPAR, harap memberitahu terlebih dahulu 
ke alamat email di atas.

Penggunaan www.overleaf.com:
Overleaf adalah online LaTeX editor berbasis web, sehingga anda dapat
menggunakannya tanpa perlu melakukan instalasi LaTeX (dan editornya) di
komputer/laptop anda.
A) Jika anda ingin menggunakan overleaf, buat akun di overleaf kemudian login. 
Kunjungi lagi halaman ini dan klik tanda panah ke atas di sebelah "Menu" (kiri
atas). Template akan masuk ke dalam akun anda. Copy template agar dapat 
digunakan untuk membuat skripsi.
B) Jika anda lebih suka cara konvensional (download template dan menggunakannya
di komputer/laptop, klik "Menu" (kiri atas) dan pilih "Source" di bagian
"Download"

===============================================================================
				1. VERSI
===============================================================================

Versi: 13.1 (01-09-2021)
terdiri dari : 
- READ_ME_FIRST_v13-1_!!!!!!.txt
- skripsi.tex (v.13) (24-07-2020)
- data.tex (v.11) (24-07-2020)
- dosen.tex (v.10) (01-09-2021)*
- referensi.bib (v.2) (03-10-2016)
- ttd.jpg
- Logo-UNPAR.png
- beberapa file .tex (versi dapat dilihat di masing-masing file) dan gambar 
lainnya sebagai contoh dan petunjuk 

*: yang berubah dari versi 13.0

Mulai versi 11.0, penomoran versi mengikuti pola X.Y
- Perubahan pada bagian X (mayor): ada perubahan signifikan pada template 
  skripsi dan seluruh mahasiswi/a diwajibkan menggunakan versi terbaru.
- Perubahan pada bagian Y (minor): ada perubahan minor pada data dosen, pada 
  contoh skripsi atau ada perubahan yang tidak penting lainnya. Oleh sebab itu 
  mahasiswi/a tidak wajib menggunakan versi tersebut.
 
Catatan: data dosen hanya akan diperbaharui sebelum semester dimulai, jika ada 
perubahan data dosen di tengah semester, mohon memperbaharui sendiri data dosen
di file dosen.tex 


===============================================================================
				2. PERHATIAN !!!
===============================================================================
- Teks yang tertulis di template ini adalah CONTOH, sekali lagi: HANYA CONTOH,
  jadi jangan mengikuti cara penulisan atau cara penempatan lampiran 
  (mis: B untuk source code program). Tanyakan kepada pembimbing masing-masing
- File skripsi.tex SANGAT dianjurkan untuk TIDAK DIUBAH, kecuali anda tahu 
  persis apa yang anda lakukan.
  File tersebut adalah file tex utama yang harus anda compile menggunakan 
  pdflatex, agar menghasilkan dokumen pdf yang sesuai.
  Isi dari file skripsi.tex adalah: 
  - perintah-perintah khusus yg digunakan di template ini
  - berisi seluruh halaman depan dari dokumen skripsi: sampul, 
    lembar pengesahan, lembar pernyataan, abstrak, abstract, 
    lembar persembahan, kata pengantar, daftar isi, daftar gambar dan
    daftar tabel. 


===============================================================================
				3. CARA PENGGUNAAN
===============================================================================
0. Perhatikan instruksi yang ada di file skripsi.tex, data.tex dan dosen.tex. 
   Instruksi2 tersebut ada di bagian awal masing - masing file.
   Di dalam file referensi.bib, terdapat petunjuk penggunaan, harap diperhatikan 
   dengan seksama. 
1. Masukkan data-data yang dibutuhkan ke dalam file data.tex. Keterangan untuk
   setiap data ada di dalam file tersebut.
   JIKA anda ingin menambahkan perintah sendiri ke dalam template ini, 
   SANGAT DIANJURKAN untuk melakukannya di bagian XV pada file data.tex, 
   sehingga tidak akan mengganggu jika terjadi update ke versi yang lebih baru
   pada file lain.
2. Jika perlu, masukkan data dosen yang belum ada ke dalam file dosen.tex atau
   lakukan perubahan seperlunya jika terjadi pergantian ketua program studi 
   atau ada perubahan gelar akademik dosen. 
3. Tuliskan isi dari setiap bab di dalam file bab (bab1.tex, bab2.tex, dst) 
   yang telah disediakan di dalam direktori "Bab".
   Jangan menghapus atau melakukan perubahan pada nama file dan pastikan file
   bab yang tidak digunakan tidak berisi apapun.
4. Jika ada file gambar (jpg, bmp, pdf, png, dll) dapat disimpan di direktori 
   "Gambar"
5. Tuliskan isi dari lampiran di dalam file lampiran (lampA.tex, lampB.tex,..)
   yang telah disediakan di dalam direktori "Lampiran"
   Jangan menghapus atau melakukan perubahan pada nama file dan pastikan file
   lampiran yang tidak digunakan tidak berisi apapun.
6. File pdf dapat dihasilkan dengan melakukan kompilasi (menggunakan pdflatex)
   pada FILE UTAMA: skripsi.tex (atau tergantung IDE yang digunakan, pada 
   beberapa kasus, kompilasi dapat dilakukan di file mana saja untuk 
   menghasilkan file PDF)

===============================================================================
				4. CARA MELAKUKAN UPDATE & TANDA TANGAN DIGITAL
===============================================================================
Cara melakukan update apabila ada template dengan versi lebih baru :
- Perhatikan versi yang anda gunakan dan versi terbaru (versi X.Y).  
- Jika terjadi perubahan di bagian X, maka wajib menggunakan versi terbaru. 
- Jika perubahan hanya pada bagian Y, disesuaikan dengan kebutuhan masing2.
Perubahan di file bab/lampiran tidak berpengaruh pada isi dokumen skripsi anda.

Cara melakukan update dari versi 12.1 ke 13.0
A. Cara 1
    1. Hapus file compj.bst di folder skripsi anda (yang lama)
    2. Copy folder .sty (baru) ke folder skripsi anda (yang lama)
    3. Overwrite file dosen.tex dan skripsi.tex dengan file yang baru
    4. Copy file ttd.jpg (ada di folder Gambar yg baru) ke dalam folder Gambar 
       anda (yang lama)
    5. Tambahkan perintah \kode{no} di data.tex Bagian V (lihat data.tex yang 
       baru) atau \kode{yes} jika anda ingin membuat daftar kode program
       Tambahkan perintah \notasi{no} di data.tex Bagian V (lihat data.tex yang 
       baru) atau \notasi{yes} jika anda ingin membuat daftar notasi
    6. Tambahkan perintah \ttd{gambar} di bagian bawah data.tex anda
       atau \ttd{digital} jika anda ingin membuat tanda tangan digital. Lihat 
       Bagian XIV di data.tex yg baru agar lebih jelas mengenai tanda tangan
    7. Selesai dan coba di-compile lagi dengan pdflatex
B. Cara 2
    1. Siapkan direktori baru untuk skripsi anda (atau project baru di overleaf)
    2. Copy seluruh file di folder Bab, Gambar, dan Lampiran (yang lama) ke 
       masing-masing folder di skripsi yang baru
    3. Lakukan perubahan di data.tex yang baru, sesuai dengan informasi yang 
       sudah diisi di data.tex yang lama. Perhatikan Bagian V dan XIV, bagian
       baru di data.tex yang baru. Bagian XIV dan XV di data.tex lama menjadi
       Bagian XV dan XVI di data.tex baru

Tambahan: 
Cara melakukan update dari versi 13.0 (tgl 22-07-2020) ke 13.0 (tgl 22-07-2020)
1. Overwrite file skripsi.tex dengan file skripsi.tex yang baru (perhatikan 
tanggal di baris 18)
2. tambahkan perintah ``\ttddosen{yes}'' atau ``\ttddosen{no}'' di file data.tex 

---------------------------------------------------------------------------------
CARA TANDA TANGAN MANUAL DENGAN MENGGUNAKAN FILE BERISI GAMBAR TANDA TANGAN:
lihat di Bagian XIV pada file data.tex

CARA TANDA TANGAN DIGITAL DENGAN ADOBE ACROBAT READER DC
Persiapan:
    1. Siapkan gambar tanda tangan anda, berformat PDF (BUKAN JPG/PNG/GIF/dlsb)
    2. Install program Adobe Acrobat Reader DC (free) disarankan yang terbaru
Cara membuat:
    1. Buka Adobe Acrobat Reader DC
    2. Pilih Edit->Preferences (atau Ctrl-K)
    3. Dari Categories, pilih Signatures
    4. Di sebelah kanan muncul Digital Signatures, klik tombol "More" di bagian
       Identities & Trust certificates
    5. Pilih "Digital IDs" di sebelah kiri dan Klik "Add Digital ID" (gambar kartu 
       dengan tanda plus)
    6. Pilih "A New Digital ID I want to create now" (klik Next)
    7. Pilih "New PKCS#12 digital ID Files" (klik Next)
    8. Isi Nama dan email address, ubah country menjadi Indonesia, ubah "Use
       digital ID for" menjadi Digital Signatures (saja) (klik Next)
       Email address sebaiknya yang non-unpar (karena akan hilang setelah lulus)
    9. Masukkan password dan confirm password (klik Next)
    10.Kembali ke langkah 4, sekarang klik tombol "More" di bagian Creation &
       Appearance
    11.Di bagian Appearances, klik "New"
    12.Isi title (misalnya dengan nama anda)
    13.Di bagian Configure Graphic, pilih Imported Graphic, klik File dan pilih
       file pdf bergambar tanda tangan anda yang telah disiapkan sebelumnya
    14.Di bagian configure text, kosongkan seluruhnya
    15.Perhatikan di bagian preview, hanya ada gambar tanda tangan anda saja!
    16.Selsai, klik OK
Cara menggunakan:
    1. Pilih command \ttd{digital} di data.tex
    2. Compile skripsi anda menjadi file pdf
    3. Buka file pdf dengan Adobe Acrobat Reader DC
    4. Di halaman "Pernyataan" terdapat kotak berwarna biru muda, klik kotak tsb
    5. Pilih Digital ID anda dan klik Continue
    6. Pilih Appearance yang telah anda buat dan perhatikan bahwa hanya boleh 
       ada gambar tanda tangan anda tanpa adanya tulisan lain
    7. _JANGAN_ men-check pilihan "Lock document after signing"!!!! (kalau ada)
    8. Reason: pilih "I am the author of this document"
    9. Isi Location, kota tempat anda membuat ini dan contact info dengan email
    10.Isi password dan klik Sign
    11.Simpan file skripsi dgn nama Skripsi-<npm>, mis:Skripsi-1997730020.pdf
    12.File pdf tsb siap dikirim ke pembimbing

===============================================================================
				5. PERANGKAT LUNAK 
===============================================================================
Template Skripsi FTIS versi 13.0 ini dibuat menggunakan:
www.overleaf.com

Template Skripsi FTIS versi seblumnya (<12.0) dibuat menggunakan:
- Windows 10 Pro 64-bit
- TeX 3.14159265 (MiKTeX 2.9 64-bit)
- pdfTeX 3.14159265-2.6-1.40.16 (MiKTeX 2.9 64-bit)
- TexStudio 2.12.0
- EmEditor Free (64-bit) 15.6.1


===============================================================================
				6. DAFTAR ISI 
===============================================================================
Template ini terdiri dari:
- READ_ME_FIRST_v13-0_!!!!!!.txt
- skripsi.tex
- skripsi.pdf
- dosen.tex
- data.tex
- referensi.bib
- .sty/compj.bst (diambil dari computer journal dan dimodifikasi seperlunya)
- .sty/digsig.sty (http://home.htp-tel.de/lottermose2/tex/dist/digsig.sty)
- Bab/bab1.tex
- Bab/bab2.tex
- Gambar/Logo-UNPAR.png (official dari website UNPAR)
- Gambar/ttd.jpg (contoh tanda tangan dari Husnul Hakim)
- Gambar/ular-jpg.jpg
- Gambar/ular-png.png
- Gambar/ular-pdf.pdf
- Lampiran/lampA.tex
- Lampiran/lampB.tex
- Lampiran/MyCode.java


===============================================================================
				7. DAFTAR CATATAN PERUBAHAN 
===============================================================================

CATATAN Versi: 13.1 (01-09-2021)
terdiri dari : 
- READ_ME_FIRST_v13-1_!!!!!!.txt
- skripsi.tex (v.13) (24-07-2020)
- data.tex (v.11) (24-07-2020)
- dosen.tex (v.10) (01-09-2021)*
- referensi.bib (v.2) (03-10-2016)
- ttd.jpg
- Logo-UNPAR.png
- beberapa file .tex (versi dapat dilihat di masing-masing file) dan gambar 
lainnya sebagai contoh dan petunjuk 

*: yang berubah dari versi 13.0


Perubahan pada:
- dosen.tex (v.10) (01-09-2021)*
    - MAT: gelar OWN, tambah JOH, RRF, Hapus IVM
    - FIS: gelar ELK
	- IF : gelar KAL, tambah IGN, MVC

_______________________________________________________________________________
===============================================================================

CATATAN Versi 13.0 (24-07-2020)
terdiri dari : 
- skripsi.tex (v.13) (24-07-2020)*
- data.tex (v.11) (24-07-2020)*
- dosen.tex (v.9) (24-07-2020)*
- referensi.bib (v.2) (03-10-2016)
*: yang berubah dari versi 12.1

Perubahan pada:
- skripsi.tex (v.13) (24-07-2020)*
    - penambahan opsi digital signature untuk para dosen
    - penambahan tiga opsi tanda tangan untuk mahasiswa
    - dapat menangani format npm baru (per angkatan 2018)
    - penambahan daftar listings (kode program)
    - penambahan gambar kotak untuk kode program
    - pemindahan file compj.bst dan digsig.sty ke folder .sty
    - format kode program di bab dan penambahan kotak untuk kode program
    - penambahan daftar notasi

- data.tex (v.11) (24-07-2020)*
	- Penambahan enumitem dan nosep untuk semua list, untuk menghemat kertas
    - Bagian V: penambahan opsi Daftar Kode Program dan Daftar Notasi
    - Bagian XIV: menjadi Bagian XVI
    - Bagian XV: menjadi Bagian XVII
    - Bagian XIV yang baru: pilihan jenis tanda tangan mahasiswa
    - Bagian XV yang baru: pilihan munculnya tanda tangan digital untuk
      dosen/pejabat

- dosen.tex (v.9) (24-07-2020)*
    - MAT: gelar FAR,IVM,BNY,MRA,FEL,WSB,FJP; tambah DAS,APW
 	- FIS: gelar JVS,RUS; nama HRY
 	- IF : hapus TAB; gelar LNV; pembimbing HUH,PAS
    - Mengganti semua \, dengan ~

_______________________________________________________________________________
===============================================================================

CATATAN Versi 12.1 (19-01-2019)
terdiri dari : 
- skripsi.tex (v.12) (27-01-2017)
- data.tex (v.10) (22-01-2017)
- dosen.tex (v.8) (19-01-2019)*
- referensi.bib (v.2) (03-10-2016)
*: yang berubah dari versi 12.0

Perubahan pada:
- dosen.tex (v.8) (19-01-2019)*
    - MAT: ganti kaprodi; gelar MRA,ERW; tambah FEL
    - FIS: ganti kaprodi; hapus BNY,FEY; gelar JVS,KMG, 
    - IF : hapus NIS,ABS,CLF; gelar RDL; tambah RCP,KDH,KAL

_______________________________________________________________________________
===============================================================================

CATATAN Versi 12.0 (28-01-2017)
terdiri dari : 
- skripsi.tex (v.12) (27-01-2017)*
- data.tex (v.10) (22-01-2017)*
- dosen.tex (v.7) (28-01-2017)*
- referensi.bib (v.2) (03-10-2016)
*: yang berubah dari versi 11.1

Perubahan pada:
- skripsi.tex (v.12) (27-01-2017)*
	- Penulisan ulang sebagian besar isi file untuk konsistensi
	- Penghapusan pdf title dan pdf subject bahasa inggris
 	- Penggunaan package microtype untuk mencegah underfull
	- Penggunaan package emptypage untuk \cleardoublepage
	- Memperbaharui headrule untuk dua garis horizontal di header halaman
	- Daftar Gambar dan Daftar Tabel dimulai dari halaman ganjil
	- Perubahan cara include bab dan lampiran, harus diisi manual
	- Perbaikan textwidth di halaman pengesahan
	- Margin untuk buku sidang dan buku final disamakan
	- Penulisan default value menggunakan warna merah dan \small
	- Perubahan menjadi "kaprodiXXX"
	- Penghapusan command-command dan package yang tidak dibutuhkan
	- Perubahan listing untuk kode program (font Bera Mono dan warna)
	- Perbaikan pada tata letak di lembar pernyataan
	- Deklarasi kaprodi dipindah dari dosen.tex
	- Perubahan file logo unpar
	- Perbaikan metadata pada file PDF
- data.tex (v.10) (22-01-2017)*
	- Penambahan overfullrule untuk memeriksa warning
  	- perubahan mode buku menjadi 4: bimbingan, sidang(1), sidang akhir dan 
     	  buku final
	- perbaikan perintah pada beberapa bagian
  	- perubahan pengisian tulisan "daftar isi" yang error
  	- penghilangan lipsum dari file ini
- dosen.tex (v.7) (28-01-2017)*
	- kaprodi (sebelumnya kajur) dan dideklarasikan di skripsi.tex
	- memisahkan kaprodi per prodi
	- menghapus dummy
 	- perubahan gelar untuk BNY
_______________________________________________________________________________
===============================================================================

CATATAN Versi 11.1 (20-11-2016)
terdiri dari : 
- skripsi.tex (v.11) (20-11-2016)*
- data.tex (v.9) (20-11-2016)*
- dosen.tex (v.6) (19-08-2016)
- referensi.bib (v.2) (03-10-2016)
*: yang berubah dari versi 11.0

Perubahan pada:
- skripsi.tex (v.11) (20-11-2016)
	- Perbaikan pada penulisan nomor romawi di daftar isi yang menyebabkan 
	  overfull
	- Pengembalian penggunaan lipsum, karena kantlipsum kurang kompatibel
	- Perbaikan bug jika pembimbing hanya 1 orang

- data.tex (v.9) (20-11-2016)
	- Penggunaan lipsum menggantikan kantlipsum
_______________________________________________________________________________
===============================================================================

CATATAN Versi 11 (08-10-2016)
terdiri dari : 
- skripsi.tex (v.10) (02-10-2016): sebelumnya bernama main.tex
- data.tex (v.8) (02-10-2016)
- dosen.tex (v.6) (19-08-2016)
- referensi.bib (v.2) (03-10-2016): sebelumnya bernama pustaka.tex

Perubahan pada:
- skripsi.tex (v.10) (02-10-2016): sebelumnya bernama main.tex
	- Perubahan nama file dari main.tex menjadi skripsi.tex
	- Perubahan style bibliography dari "ieeetr" menjadi "compj" yang 
	  digunakan di jurnal "The Computer Journal" yg diterbitkan oleh 
	  Oxford University Press/British Computer Society
	- Penempatan gambar otomatis di folder "Gambar", jadi tidak perlu 
	  menuliskan nama folder lagi 
	  (\includegraphics{Gambar/tes} --> \includegraphics{tes})
	- Perubahan font menjadi latin modern yg sdh banyak digunakan di 
	  jurnaljurnal internasional
   	- Perbaikan kecil: jeda antara ttd pembimbing dan penguji
	- Pembimbing Tunggal --> Pembimbing (karena sdh jelas tunggal) 
	- Penggunaan kantlipsum sebagai pengganti lipsum
	- \onespacing otomatis untuk buku skripsi final, untuk buku sidang 
	  tetap \onehalfspacing
	- Perbaikan hfill dan hfil yang masih menjadi masalah, bagian itu 
	  dipindahkan ke dekat deklarasi Daftar Isi
- data.tex (v.8) (02-10-2016)
	- Perubahan keterangan pada spacing: Otomatis spasi 1 untuk buku 
	  skripsi final dan 1.5 untuk buku sidang
	- penghapusan mode sidang_akhir, sidang == sidang_akhir
	- Penggunaan kantlipsum
- dosen.tex (v.6) (19-08-2016)
 	- Penambahan dosen (Farica, Claudio).
	- Penghapusan dosen (Oerip)
 	- Perubahan singkatan untuk dosen Informatika sesuai ketentuan prodi
	- Perbaikan "catatan untuk mhs teknik informatika"
- referensi.bib (v.2) (03-10-2016): sebelumnya bernama pustaka.tex
	- Penjelasan umum dan 12 jenis penulisan referensi
- bab/lampiran (v.2) (08-10-2016)
	- pengisian secara serius pertama kalinya
_______________________________________________________________________________
===============================================================================

CATATAN Versi 10 (30-11-2015)
terdiri dari:
- main.tex (v.9) (30-11-2015)
- data.tex (v.7) (30-11-2015)
- dosen.tex (v.5) (30-11-2015)

Perubahan pada:
- main.tex (v.9) (30-11-2015)
	- bagian untuk menambahkan perintah sendiri dipindahkan ke data.tex
	- bagian untuk mengatur kemunculan daftar gambar dan daftar tabel, 
	  dipindahkan ke data.tex
	- penambahan bagian untuk mengatur perbedaan pdfTeX, masalah hfill 
	  dgn hfil (Trims u/ Pascal)
	- bagian pengesahan diatur agar lebih rapi 
- data.tex (v.7) (30-11-2015)
	- Perubahan nomor bagian karena penyisipan Bagian V
	- Penambahan Bagian V: pengaturan kemunculan daftar gambar dan/atau 
	  tabel dipindahkan dari main.tex
	- Penambahan Bagian XV: tempat untuk menambahkan perintah yang dibuat
	  sendiri, dipindahkan dari main.tex
	- Penambahan Bagian 0: perintah bagi yang caption daftar isi tidak 
	  bisa ke bagian tengah
- dosen.tex (v.5) (30-11-2015)
 	- Perubahan ketua jurusan matematika menjadi JDL
 	- Perubahan ketua jurusan teknik informatika menjadi MAR
	- Penghapusan dosen (Hariman,Farica,Lukcy,Verli,Wahyu)
	- Penambahan dosen (Risti, Bagoes, Reinard, Haryanto)
	- Perbaikan gelar (Ferry, Rusli, Fla, Kian Ming, Wono, Gede, Pascal)
	- Penggunaan thin-space untuk spasi pada nama, agar tidak terpotong

Catatan penting:
1. Perubahan main.tex ke versi 9, data.tex ke versi 7 dan dosen.tex ke versi 5 
2. update data dosen dan sedapatnya membuat mahasiswa tidak melakukan perubahan
   di main.tex
_______________________________________________________________________________
===============================================================================

CATATAN Versi 9 (31-05-2015)
terdiri dari:
- main.tex (v.8) (31-05-2015)
- data.tex (v.6) (13-04-2015)
- dosen.tex (v.4)

Perubahan pada:
- main.tex (v.8) (31-05-2015)
	- penambahan default data untuk beberapa keterangan dan digunakan 
	  sebagai template dengan tanda << & >> . 
	  Data yang diubah defaultnya adalah: nama skripsi, nama prodi, beserta
 	  bahasa inggrisnya.
   	- Keywords dan kata kunci di abstrak ditambahkan noindent + perbaikan 
	  lainnya
   	- Perbaikan untuk halaman tidak kosong tanpa nomor halaman romawi
- data.tex (v.6) (13-04-2015)
 	- Perubahan untuk data-data ``template" menjadi lebih generik dan 
	  menggunakan tanda << dan >>

Catatan penting:
1. Perubahan main.tex ke versi 8 dan data.tex ke versi 6 untuk mengakomodasi 
kebutuhan akreditasi, dimana template sebaiknya tidak merujuk kepada pekerjaan
seseorang tetapi dibuat lebih generik
_______________________________________________________________________________
===============================================================================

CATATAN Versi 8 (27-05-2014)
terdiri dari:
- main.tex (v.7) (27-05-2014)
- data.tex (v.5) 
- dosen.tex (v.4)

Perubahan pada:
- main.tex (v.7) (27-05-2014)
	- penambahan perintah \raggedbottom untuk menghilangkan area kosong 
	  akibat penempatan gambar yang tidak sempurna

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
	- perbaikan pada abstract dengan paragraf lebih dari satu: perbaikan 
	  vertical spacing
	- perbaikan pada tampilan bab dan lampiran: tidak perlu menuliskan 
	  apapun untuk menampilkan semuanya (di data.tex) atau -1 jika 
	  tidak ada lampiran
	- halaman bernomor genap untuk halaman romawi sudah dimunculkan
	- Kurikulum 2013: perubahan nama buku skripsi 
- data.tex (v.5) (10-11-2013)
 	- Perbaikan pada memasukkan bab: tidak perlu menuliskan apapun untuk 
	  memasukkan seluruh bab (bagian V)
 	- Perbaikan pada memasukkan lampiran: tidak perlu menuliskan apapun 
	  untuk memasukkan seluruh lampiran atau -1 jika tidak memasukkan 
	  apapun
- dosen.tex (v.3) (10-11-2013)
 	- Perubahan ketua jurusan teknik informatika menjadi MAR
	- Penambahan dosen jurusan informatika (Joanna, Wahyu)
	- Penghapusan dosen informatika (Lucky, Dharu)

Catatan penting:
1. Perubahan versi ke angka desimal untuk memudahkan pengguna saat menggunakan 
   template yang paling mutakhir
2. Perbaikan minor untuk paragraf pada abstrak, penulisan halaman romawi genap,
   instruksi untuk memasukkan bab dan lampiran
3. Perbaikan data dosen
4. Penambahan petunjuk cara memperbaharui template jika ada versi yang lebih 
   baru
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
 	- Tambahan catatan untuk mhs T. Inf. terkait dosen yg tidak bisa 
	  menjadi pemb.
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
	- Data dosen dipindah ke dosen.tex agar jika ada perubahan/update 
	  data dosen, mahasiswa tidak perlu mengubah data.tex
	- Perubahan pada keterangan dosen
- dosen.tex (v.1) (21-10-2012)
 	- Data dosen dipindah dari data.tex agar jika ada perubahan/update 
	  data dosen mahasiswa tidak perlu mengubah data.tex
 	- Beberapa dosen Informatika yang tidak boleh menjadi pembimbing 
	  digantikan OSS
 	- Update data gelar untuk Maria (MAT)
 	- Penambahan baru (Flaviana-Fisika, Elok-Fisika)
 	- Dosen keluar atau tidak menjadi pembimbing lagi (Monika, David)

Catatan penting:
1. Halaman terakhir pada bab jika tidak ada isinya dan terletak di sebelah kiri,
dikosongkan header-nya (usul dari Erwinna dan Ivonne)
2. Data dosen dipisahkan ke file dosen.tex sehingga jika dilakukan perubahan
pada data dosen, mahasiswa tidak perlu mengganti file data.tex
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
1. Perubahan yang cukup signifikan adalah ditambahkannya halaman dengan judul
bahasa inggris, jadi di dokumen final, di halaman bagian dalam terdapat 2 buah
halaman judul, dalam bahasa indonesia dan dalam bahasa inggris.
2. Untuk menggunakan versi 1.0, yang harus anda lakukan adalah mengubah isi 
direktori Bab, Gambar dan Lampiran dengan yang sudah anda buat dan mengisikan 
kembali data-data di file data.tex dengan data yang sudah anda isikan 
sebelumnya di file data.tex yang lama
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
 	- "Daftar Referensi" tidak perlu diubah secara manual (tidak perlu 
	  mengubah file bahasai.ldf)
 	- Bahasa Indonesia dari abstract adalah abstrak (secara otomatis), 
	  bukan ringkasan
 	- Spasi pada buku dokumen final adalah onehalfspacing
- setup.tex (v.2) (08-07-2012)
	- Menambahkan perintah untuk judulINA dan judulENG
	- Menghapus \usepackage{microtype}, yang pada beberapa kasus menjadi
	  masalah
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
1. Pertama kali dirilis tanggal 08-11-2011, setelah berjuang karena melihat 
   tata tulis yang "amburadul". 
2. Belum ada READ_ME_FIRST_!!!!!!.txt
_______________________________________________________________________________
===============================================================================

Copyright \textcopyright 2011-2021 [Lionov W.]. All rights reserved.