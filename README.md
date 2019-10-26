#Latihan 1
TUTORIAL PENGGUNAAN GIT
Instalasi GIT
•	Download GIT,buka website resminya GIT (git-scm.com).
•	Lalu unduh GIT sesuai dengan arsitektur komputer kita.Kalau menggunakan 64 bit,download yang 64 bit.Begitupun yang menggunakan 32 bit.
•	Selamat, GIT sudah terinstal di Windows.Untuk mencobanya,silahkan buka CMD atau PowerShell,kemudian ketuk perintah
![image](https://user-images.githubusercontent.com/56968412/67612508-5e106580-f7cd-11e9-932d-2b475d031812.png)
Menambahkan Global Config
•	Pada saat pertama kali menggunakan GIT,perlu dilakukan konfigurasi user,name dan user,email.
•	Konfigurasi ini bisa dilakukan untuk global repository atau individual repository.
•	Apabila belum dilakukan konfigurasi,akan mengakibatkan terjadi kegagalan saat menjalankan perintah git commit.
•	Config Global Repository
![image](https://user-images.githubusercontent.com/56968412/67612521-87c98c80-f7cd-11e9-88fc-5ed345cab656.png)
Membuat Repository Lokal
•	Buka direktory aktif,misal: d:\labs_pemrograman1 (Buka menggunakan Windows Explorer).
•	Klik kanan pada direktory aktif tersebut,dan pilih menu Git Bash,sehingga muncul git bash commad.

•	Buat direktory project praktikum pertama dengan nama latihan1
![image](https://user-images.githubusercontent.com/56968412/67612541-bf383900-f7cd-11e9-98cc-5750f68a4d8f.png)
•	Sehingga terbentuk satu direktory baru dibawahnya,selanjutnya masuk kedalam direktory tersebut dengan perintah cd(change directory).
•	Direktory aktif menjadi: d:\labs_pemrograman1\latihan1.
•	Jalankan perintah git init, untuk membuat repository local.
•	Repository baru berhasil di inisialisasi, dengan terbentuknya satu direktori hidden dengan nama .git 
•	Pada direktori tersebut, semua perubahan pada working directory akan disimpan.
![image](https://user-images.githubusercontent.com/56968412/67612559-d545f980-f7cd-11e9-9eff-2415adaa5e91.png)
•	Untuk membuat file dapat menggunakan text editor, lalu menyimpan filenya pada direktori aktif (repository)
•	disini kita akan coba buat satu file bernama README.md (text file)
•	File README.md berhasil dibuat.
![image](https://user-images.githubusercontent.com/56968412/67612571-eee74100-f7cd-11e9-9d1b-1f645f020102.png)
•	Untuk menambahkan file yang baru saja dibuat tersebut gunakan perintah git add.
•	File README.md berhasil ditambahkan.
![image](https://user-images.githubusercontent.com/56968412/67612582-06bec500-f7ce-11e9-8da0-87fac1b4c3a7.png)
•	Untuk menyimpan perubahan yang ada kedalam database repository local, gunakan perintah git commit -m “komentar commit” 
•	Perubahan berhasil disimpan.
![image](https://user-images.githubusercontent.com/56968412/67612601-19d19500-f7ce-11e9-9eb2-12fdf36c1a3b.png)
Membuat Repository Server
•	Server repository yang akan kita gunakan adalah http://github.com.
•	Anda harus membuat akun terlebih dahulu.
•	Pada halaman github,klik tombol start a project,atau
•	Dari menu (icon+) klik New Repository.
![image](https://user-images.githubusercontent.com/56968412/67612611-34a40980-f7ce-11e9-84e7-667a62564340.png)
Membuat Repository Server
•	Isi nama reporitorynya,misal: latihan 1
•	Lalu klik tombol Create Repositoryz
![image](https://user-images.githubusercontent.com/56968412/67612626-49809d00-f7ce-11e9-9734-164ebafc8a67.png)
•	Remote Repository merupakan repository server yang akan digunakan untuk menyimpan setiap perubahan pada local repository, sehingga dapat diakses oleh banyak user.
•	Untuk menambahkan remote repository server, gunakan perintah git remote add origin [url]
![image](https://user-images.githubusercontent.com/56968412/67612636-5f8e5d80-f7ce-11e9-91ac-ac4653756b87.png)
•	Untuk mengirim perubahan pada local repository ke server gunakan perintah git push.
•	Perintah ini akan meminta memasukkan username dan password pada akun github.com
![image](https://user-images.githubusercontent.com/56968412/67612658-7339c400-f7ce-11e9-9755-c5d7c5da659d.png)
Melihat Hasilnya Pada Server Repository
•	Buka laman github.com,arahkan repositorynya.
•	Maka perubahan akan terlihat pada laman tersebut.
![image](https://user-images.githubusercontent.com/56968412/67612667-8ba9de80-f7ce-11e9-8528-b4602fbd3992.png)
