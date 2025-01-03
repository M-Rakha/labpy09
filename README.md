# LAPORAN LATIHAN STRING

# CODE PROGRAM STRING

## Step 1 :

Kode ini mengimpor library re (regular expression) yang digunakan untuk pencocokan pola pada string. Dalam program ini, library ini digunakan untuk memvalidasi nama.

Selain itu, Method init adalah konstruktor yang dijalankan saat objek kelas dibuat. Di sini, atribut data_mahasiswa diinisialisasi sebagai list kosong untuk menyimpan data mahasiswa.

![gambar](https://github.com/M-Rakha/labpy09/blob/4e22f64f49eb736a4b82b55b0ccab5e2d2e8d7d6/Cuplikan%20layar%202025-01-03%20184453.png)

## Step 2 :

Fungsi ini digunakan untuk memvalidasi data pendaftaran. Parameter name, phone, dan email adalah input pengguna. Sebuah list kosong bernama errors disiapkan untuk menyimpan pesan kesalahan jika ada.

![gambar](https://github.com/M-Rakha/labpy09/blob/3354ebbd78634aaa4d46f2fb3be4c4a3391900d6/Cuplikan%20layar%202025-01-03%20185122.png)

- Validasi Nama : re.match(r'^[A-Za-z\s]+$', name) memeriksa apakah nama hanya berisi huruf (A-Z atau a-z) dan spasi (\s), Jika nama tidak sesuai dengan pola tersebut, pesan kesalahan ditambahkan ke list errors.

![gambar](https://github.com/M-Rakha/labpy09/blob/5f7c307113caeadec3ae06c476fa1d21106f8c40/Cuplikan%20layar%202025-01-03%20185440.png)

- Validasi Nomor Telepon : phone.isdigit() memeriksa apakah input nomor telepon hanya terdiri dari angka, Jika ada karakter lain (seperti huruf atau simbol), pesan kesalahan ditambahkan.

![gambar](https://github.com/M-Rakha/labpy09/blob/3b232cc99b9c976e4c462f579e9d32e5a4ff6f3e/Cuplikan%20layar%202025-01-03%20185835.png)

- Validasi Email : Memeriksa apakah email mengandung simbol (@) dan (.) Jika tidak, pesan kesalahan ditambahkan.

![gambar](https://github.com/M-Rakha/labpy09/blob/b99617dc866bc0bb3d1777502a19fc1552751371/Cuplikan%20layar%202025-01-03%20190103.png)

## Step 3 :

Jika terdapat kesalahan (list errors tidak kosong), setiap pesan kesalahan ditampilkan satu per satu, Jika tidak ada kesalahan, program menampilkan pesan bahwa data pendaftaran valid.

![gambar](https://github.com/M-Rakha/labpy09/blob/5da5d258df6e1dd661e6027622348a803854ddeb/Cuplikan%20layar%202025-01-03%20190324.png)

## Step 4 :

Program meminta pengguna untuk memasukkan:

- Nama lengkap (name)
- Nomor telepon (phone)
- Email (email)

![gambar](https://github.com/M-Rakha/labpy09/blob/851a5e7c8aa868b283b20e73e8f13c88dfbe3036/Cuplikan%20layar%202025-01-03%20190557.png)

## Step 5 :

Input dari pengguna dikirim ke fungsi validate_registration untuk diperiksa validitasnya.





