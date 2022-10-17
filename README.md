Hallo perkenalkan nama saya Hilmy syaddad ramzy nurfauzan, saya akan menjelaskan Cara penginstalan GIT
Pertama kalian harus mendownload Aplikasi Git, buka website resminya Git di git-scm.com .
![Screenshot (3)](https://user-images.githubusercontent.com/115677769/196092612-ea0f5959-be60-40c4-a36f-48839137a7a5.png)
 Download lah sesuai dengan bit (32 bit atau 64 bit)laptop anda agar support. Setelah selesai download klik instal

Lalu klik next simpan file lokasi instal di C:\ProgramFiles\Git(sesuai keinginan anda) , lalu di next saja semua sampai ke step install, TUNGGU SAMPAI SELESAI.

image

Setelah melakukan penginstalan, buka git cmd untuk mengetahui apakah sudah bisa melakukan proses atau belum jika muncul git version berarti sudah siap melakukan proses. Untuk mengetahui versinya ketikan perintah git --version. Saya memakai versi 2.38.0.windows.1
![Screenshot (4)](https://user-images.githubusercontent.com/115677769/196093761-3c7e9b63-b771-4aaa-ba9e-7c79d4703cbb.png)


Cara membuat akun git
Disini anda harus membuat akun git terlebih dahulu untuk membuat repository server bukalah link tersebut http://github.com
Screenshot (16)

Pada langka selanjutnya anda boleh langsung diskip saja.

Membuat repositori baru
Ini adalah tampilan pertama setelah kalian selesai membuat akun git

![Screenshot (5)](https://user-images.githubusercontent.com/115677769/196094460-26626750-fb0a-47ef-81c3-7d5056dceeb9.png)


Langkah selanjutnya nanti anda akan dialihkan ke tab baru untuk membuat repositori baru, isi susuai inspirasi anda setelah selesai klik buat repositori.
![Screenshot (6)](https://user-images.githubusercontent.com/115677769/196094856-ac70760b-dd32-4748-b40d-ffefeacd576f.png)


Lalu nanti di tab baru ada url, url ini akan digunakan untuk remote GitHub.
![Screenshot (7)](https://user-images.githubusercontent.com/115677769/196095070-ec20d3ef-a1cd-4367-9443-ff43ced856e6.png)


Membuat Reposiory Local
Lalu kita buka file explorer pilih dilocal disk e (atau dmana saja sesuai keinginan anda), lalu klik kanan pilih Git Bash here . Screenshot (20)

Lalu kita akan menambahkan Config Global Repository pakai user name dan user email yang tadi sudah dibuat, dengan perintah : $ git config --global user.email “nama_user” $ git config --global user.name “nama_user”

![Screenshot (8)](https://user-images.githubusercontent.com/115677769/196095598-f09af533-3f52-4229-b74e-d892f2a50b3b.png)


Buatlah direktori baru dengan menggunakan perintah " mkdir lab_pemrograman1 " LALU " cd lab_pemrograman1 ![Screenshot (9)](https://user-images.githubusercontent.com/115677769/196095781-abbfcf60-51eb-40fa-9334-2adf53058204.png)
 ".

Cara penggunaan git dengan perintah daasar git init fungsi perintahnya untuk membuat repository local
Lalu jalankan perintah git init untuk membuat membuat file kosong berformat GIT. File ini fungsinya untuk menyimpan semua perubahan pada working directory dan file ini terbentuknya hidden.

![Screenshot (10)](https://user-images.githubusercontent.com/115677769/196095947-c63b8f6d-6615-4c7d-9fab-4854bd28b2b1.png)


Lalu buat 1 file baru bernama README.md, dengan memasukan perintah _echo “#latihan1” >> README.md. Lalu untuk melihat file ketik perintah “ls

![Screenshot (11)](https://user-images.githubusercontent.com/115677769/196096197-1b6b353f-fc99-4a3d-b009-7991b5fb7c55.png)


Cara penggunaan git dengan perintah dasar git add fungsi perintahnya untuk menambahkan file baru, atau perubahan pada file pada staging sebelum proses commit
Untuk menambahkan file yang baru saja dibuat tersebut gunakan perintah git add. Dengan perintah $ git add README.md. Kalau ingin melihat infonya ketik perintah git status. ![Screenshot (12)](https://user-images.githubusercontent.com/115677769/196096386-6d53cd35-0f2a-44a2-9e89-644ad4cf5011.png)


Untuk menyimpan perubahan yang ada kedalam database gunakan perintah git commit -m “komentar commit" 67557721-cadd1e80-f73f-11e9-8f44-dc52f8676eb3

File berhasil tersimpan
Langkah berikutnya kita kembali ke website GitHub untuk melihat repositori yang sudah dibuat. Nah di Quick Setup nanti ada url github kita, url tersebut untuk perintah_ “git remote add origin [url] “ DAN PERINTAH GIT CLONE “ git clone [ url ] “_
Cara penggunaan git dengan perintah dasar git remote add origin [url], perintah untuk menambahkan remote server/reopsitory server pada local repositry (working directory)
Sudah mengetahui url githubnya lalu ketik perintah git remote add origin [url],urlnya diganti dengan url github anda ![Screenshot (1)](https://user-images.githubusercontent.com/115677769/196096726-241bfd33-6d91-4e0b-9915-6a2bce0b7aa7.png)

Cara penggunaan git dengan perintah dasar git push -u origin master, perintah untuk mengirim perubahan pada repository local menuju server repository
Untuk mengirim perubahan pada local repository ke server gunakan perintah “git push -u origin master”. Ingat pada langkah ini kita harus memasukan usernam dan pasword gethub.
Cara penggunaan git dengan perintah dasar git clone [url], perintah untuk membuat working directory yang diambil dari repositry sever.
Kalau ingin melakukan cloning, gunakan perintah git clone [url], urlnya diganti dengan url github anda. Jika ingin masuk kedirektorti gunakan perintah “cd [nama direktori anda]”, dan jika ingin melihat semua isi direektori gunakan perintah “ls -1" git_push

Selesai Jika ingin melihat hasilnya cek di laman gethub arahkan ke repositorinya

FILE README.md tersebut masih kosong jikalau anda ingin mengisi kekosongan file tersebut silahkan klik saja icon pensil yang berada di kanan atas.
