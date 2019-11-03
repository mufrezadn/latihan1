"# latihan1" 
# Cara penggunaan git
# Apa Itu Git ?
* Git adalah salah satu sistem pengontrol versi(Version Control System) pada proyek perangkat lunak yang diciptakan Linus Torvalds.
* Pengontrol versi bertugas memcatat setiap perubahan pada file proyek yang dikerjakan oleh banyak orang maupun sendiri.
* Git dikenal juga dengan distributed revision control (VCS terdistribusi), artinya penyimpanan database Git tidak hanya berada dalam satu tempat saja.

<img width="514" alt="01" src="https://user-images.githubusercontent.com/57052783/68079476-72dd9200-fda7-11e9-9f90-5c8cade409af.png">

# Instalasi Git
* Download Git, Buka website resminya [git-scm.com.](https://git-scm.com)
* Kemudian unduh Git sesuai dengan arsitektur komputer kita, Kalau menggunakan 64bit, unduh yang 64bit. Begitu juga kalau menggunakan 32bit.

<img width="302" alt="1" src="https://user-images.githubusercontent.com/57052783/68079501-e5e70880-fda7-11e9-8e9c-2b7a8ee4f666.png">

* Selamat, Git sudah terinstal di Windows. Untuk mencobanya, silahkan buka CMD atau PowerShell, kemudian ketik perintah git --version
gitversion

# Menambahkan Global Config
* Pada saat pertama kali menggunakan git, perlu dilakukan konfigurasi user.name dan user.email
* konfigurasi ini bisa dilakukan untuk global repostiry atau individual repository.
* apabila belum dilakukan konfigurasi, akan mengakibatkan terjadi kegagalan saat menjalankan perintah git commit
* Config Global Repository
* gitconfig

<img width="306" alt="2" src="https://user-images.githubusercontent.com/57052783/68079513-29417700-fda8-11e9-9638-9816de21fe19.png">

# Perintah Dasar Git
* git init , perintah untuk membuat repository local.
* git add , perintah untuk menambahkan file baru, atau perubahan pada file pada staging sebelum proses commit.
* git commit , perintah untuk menyimpan perubahan kedalam database git.
* git push -u origin master , perintah untuk mengirim perubahan pada repository local menuju server repository.
* git clone [url], perintah untuk membuat working directory yang diambil dari repositry sever.
* git remote add origin [url] , perintah untuk menambahkan remote server/reopsitory server pada local repositry (working directory)
* git pull , perintah untuk mengambil/mendownload perubahan terbaru dari server repository ke local repository.
# Membuat Reposiory Local

* Buka direktory aktif, misal: d:\labs_pemrograman1 (bukamenggunakan Windows Explorer)
* klik kanan pada direktory aktif tersebut, dan pilih menu Git Bash,sehingga muncul git bash commad
* Buat direktory project praktikum pertama dengan nama latihan1
* Sehingga terbentuk satu direktori baru dibawahnya, selanjutnyamasuk kedalam direktori tersebut dengan perintah cd (changedirectory)
* direktory aktif menjadi: d:\labs_pemrograman1\latihan1

<img width="385" alt="3" src="https://user-images.githubusercontent.com/57052783/68079702-fb116680-fdaa-11e9-8ba1-8951ce65b4c4.png">


# Membuat Reposiory Local
* Jalankan perintah git init, untuk membuat repository local.

* Repository baru berhasil di inisialisasi, dengan terbentuknya satudirektori hidden dengan nama .git
* Pada direktori tersebut, semua perubahan pada working directory akan disimpan.

<img width="385" alt="4" src="https://user-images.githubusercontent.com/57052783/68079731-78d57200-fdab-11e9-8c2c-dd3bcbcf4c6b.png">

# Menambahkan File baru pada repository
* Untuk membuat file dapat menggunakan text editor, lalu menyimpafilenya pada direktori aktif (repository)
* disini kita akan coba buat satu file bernama README.md (text file) $ echo “#Latihan 1” >> README.md
File README.md berhasil dibuat.

<img width="400" alt="5" src="https://user-images.githubusercontent.com/57052783/68079778-53953380-fdac-11e9-9052-523390e7d468.png">

# Menambahkan File baru pada repository
* Untuk menambahkan file yang baru saja dibuat tersebut gunakanperintah git add.
* File README.md berhasil ditambahkan. $ git add README.md

<img width="415" alt="7" src="https://user-images.githubusercontent.com/57052783/68079815-f483ee80-fdac-11e9-90ed-e716588453cc.png">
<img width="435" alt="8" src="https://user-images.githubusercontent.com/57052783/68079830-32811280-fdad-11e9-84ec-7ebe2d17db75.png">


# Commit (Menyimpan perubahan ke database)
* Untuk menyimpan perubahan yang ada kedalam database repository local, gunakan perintah $ git commit -m “komentar commit”
* Perubahan berhasil disimpan

<img width="383" alt="9" src="https://user-images.githubusercontent.com/57052783/68079875-221d6780-fdae-11e9-8b24-97d525364940.png">

# Membuat repository server
* Server reopsitory yang akan kita gunakan adalah [github.com.](https://git.scm.)
* Anda harus membuat akun terlebih dahulu.
* Pada laman github, klik tombol start a project, atau Dari menu (icon +) klik New Repository

<img width="249" alt="10" src="https://user-images.githubusercontent.com/57052783/68079942-5b0a0c00-fdaf-11e9-88d5-3b64904f55c1.png">

# Membuat repository server
* Isi nama repositorynya, misal: labpy1.
* lalu klik tombol Create repository

<img width="556" alt="11" src="https://user-images.githubusercontent.com/57052783/68079979-dcfa3500-fdaf-11e9-92d2-1b8f0f2b4bf0.png">

# Menambahkan Remote Repository
* Remote Repository merupakan repository server yang akan digunakan untuk menyimpan setiap perubahan pada local repository, sehingga dapat diakses oleh banyak user.
* Untuk menambahkan remote repository server, gunakan perintah git remote add origin [url]

<img width="392" alt="12" src="https://user-images.githubusercontent.com/57052783/68080004-49753400-fdb0-11e9-959a-bbfa9d885f12.png">

# Melihat hasilnya pada server repository
* Buka laman [github.com.](https://git.scm.),arahkan pada repositori- nya.
* Maka perubahan akan terlihat pada laman tersebut.

<img width="934" alt="14" src="https://user-images.githubusercontent.com/57052783/68080063-357e0200-fdb1-11e9-9a4e-01707da1a1d7.png">

FINISH............................
