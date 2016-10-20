## Latar Belakang Masalah :
1. Cara menambah SSH Key pada github.
2. Cara membuat repository baru pada github.
3. Cara Pull dan Push menggunakan git bash.

## Cara Menambah SSH Key Pada Github
1. Pertama-tama Login dulu menggunakan akun github masing-masing.
2. Kemudian pilih gambar profil anda, lalu pilih Settings.
3. Kemudian pada personal settings nya, pilih SSH and GPG keys. Lalu pada SSH keys pilih generating SSH keys.
4. Kemudian pilih generating a new SSH key and adding it to the ssh-agent.
5. Kemudian jalankan gitbash, dan pastekan ssh-keygen -t rsa -b 4096 -C "your_email@example.com" pada git bash dan ubah sesuai email anda.
6. Kemudian enter, lalu masukkan passphrase, lalu ulangi lagi passphrasenya.
7. Kemudian tuliskan cat ~/.ssh/id_rsa.pub pada git bash, lalu copykan key ssh yang ada pada gitbash, pastekan pada key ssh baru yang akan dibuat pada github dan jangan lupa isi titlenya juga.
8. Setelah itu klik tombol Add SSH key, maka proses penambahan SSH key pada github sudah selesai.

## Cara Membuat Repository Baru Pada Github
1. Pertama-tama pastikan sudah login menggunakan akun github masing-masing, pilih tanda plus disamping gambar profil, lalu pilih New repository.
2. Kemudian pilih ownernya dan isikan nama repository yang akan dibuat, lalu isi description (bisa dikosongkan), lalu pilih public (jika ingin semua orang bisa melihat repository anda), lalu ceklis Initialize this repository with a README, lalu add juga gitignore dan license nya.
3. Setelah itu klik tombol Create repository, maka proses pembuatan repository baru pada github sudah selesai.

## Cara Pull dan Push Menggunakan Git Bash
1. Pertama-tama buat folder kerja anda terlebih dahulu, lalu didalamnya klik kanan pilih Git Bash Here.
2. Kemudian tulis git init pada git bash untuk menginisialisasi.
3. Kemudian tulis git remote add origin dan lanjutkan dengan memasukkan link clone https github repository anda, misalkan : git remote add origin https://github.com/bayurahmadazhari/kapita-selekta.git
4. Kemudian tulis git pull origin master untuk mengambil data yang ada pada github untuk dimasukkan kedalam folder kerja kita.
5. Kemudian tambahkan folder atau file yang ingin ditambahkan ke dalam folder kerja anda.
6. Kemudian tulis git status untuk melihat folder atau file apa saja yang belum ditambahkan ke dalam github.
7. Kemudian tulis git add serta menulis nama folder atau file yang akan ditambahkan ke github, misalkan : git add doc/kuliah/pertemuan1.md
8. Kemudian tulis git commit -m “komentar anda” untuk perintah commit.
9. Setelah itu tulis git push origin master untuk mendorong data yang telah diperbaharui ke github lagi, maka proses pull dan push menggunakan git bash telah selesai.

## Kesimpulan
Jadi, dengan tutorial ini kita bisa mengetahui cara menambah SSH key pada github, cara membuat repository baru pada github, dan cara pull dan push menggunkan git bash.

## Saran
Diharapkan memperhatikan setiap langkah tutorial ini, jika tidak ingin error saat proses percobaannya.

Link Github : https://github.com/bayurahmadazhari/kapita-selekta

Nama : Bayu Rahmad Azhari

NPM : 1144125

Kelas : 3C

Prodi : D4 Teknik Informatika

Kampus : Politeknik Pos Indonesia

Link Matakuliah : http://kampus.awangga.net/assignments/kapitaselekta2016

Referensi : http://kampus.awangga.net/classroom-news/standarpenggunaangit

Scan Plagiarisme :
* https://drive.google.com/open?id=0B5FSMUsdCMU4UDdncnpzVXVpV28
* https://drive.google.com/open?id=0B5FSMUsdCMU4OWhFRWd2MnRKSVE
