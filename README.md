#latihan1git

Cara dan langkah-langkah penggunaan Git
1. Download git, buka website resminya (git-scm.com)
2. Unduh git sesuai arsitektur komputer kita
3. Kalau menggunakan 64bit, unduh yang 64bit. Begitu juga kalau menggunakan 32bit.
4. Jika sudah berhasil terinstall, maka cobalah dengan membuka CMD atau PowerShell, kemudian ketik perintah
![git1 (2)](https://user-images.githubusercontent.com/57063216/68037727-f2f9ee00-fcfa-11e9-8086-17682f8fb190.png)
5. Menambahkan Global Config
6. Pada saat pertama kali menggunakan git, perlu dilakukan konfigurasi user.name dan user.email
7. konfigurasi ini bisa dilakukan untuk global repostiry atau individual repository
8. apabila belum dilakukan konfigurasi, akan mengakibatkan terjadi kegagalan saat menjalankan perintah git commit
9. Config Global Repository
$ git config --global user.name “nama_user”
$ git config --global user.email “nama_user”
![git2 (3)](https://user-images.githubusercontent.com/57063216/68038950-ab289600-fcfd-11e9-8fc9-0239671edf59.png)
10. Buka direktory aktif, misal: Documents\latihan1 (buka menggunakan Windows Explorer)
11. klik kanan pada direktory aktif tersebut, dan pilih menu Git Bash,sehingga muncul git bash commad
12. Buat direktory project praktikum pertama dengan nama latihan1
13. Sehingga terbentuk satu direktori baru dibawahnya, selanjutnya masuk kedalam direktori tersebut dengan perintah cd direktory
![capture-20191101-233338 (2)](https://user-images.githubusercontent.com/57063216/68040238-7ec24900-fd00-11e9-9f88-c3bbf6a9cb2d.png)
14. Membuat Reposiory Local
15. Jalankan perintah git init, untuk membuat repository local
![git init (2)](https://user-images.githubusercontent.com/57063216/68040919-f0e75d80-fd01-11e9-90c4-6e321b5aadb5.png)
16. Repository baru berhasil di inisialisasi, dengan terbentuknya satu direktori hidden dengan nama .git
17. Pada direktori tersebut, semua perubahan pada working directory akan disimpan
18. Tambahkan File baru pada repository
19. Untuk membuat file dapat menggunakan text editor, lalu menyimpan filenya pada direktori aktif (repository)
coba buat satu file bernama README.md (text file)
![readme (2)](https://user-images.githubusercontent.com/57063216/68041941-4b81b900-fd04-11e9-9bf7-004cecd445cf.png)
file readme telah berhasil dibuat.
20. Menambahkan File baru pada repository
Untuk menambahkan file yang baru saja dibuat tersebut gunakan perintah git add.
![addreadme](https://user-images.githubusercontent.com/57063216/68042453-82a49a00-fd05-11e9-99d3-a910ca1a1760.png)
21. Untuk menyimpan perubahan yang ada kedalam database repository local, gunakan perintah git commit -m “komentar commit”
![ss](https://user-images.githubusercontent.com/57063216/68042792-563d4d80-fd06-11e9-890f-8b6474380ff2.png)
22. Membuat repository server, server reopsitory yang akan kita gunakan adalah http://github.com
23. buat akun terlebih dahulu.Pada laman github, klik tombol start a project, atau Dari menu (icon +) klik New Repository
![67634370-81323680-f8ed-11e9-9f15-ab195b997bc8](https://user-images.githubusercontent.com/57063216/68043056-001cda00-fd07-11e9-8a2b-944b6756a89a.png)
24. Isi nama repositorynya, misal: latihan1git
![20191102_005004 (2)](https://user-images.githubusercontent.com/57063216/68045968-5bea6180-fd0d-11e9-895a-21fa98159a81.jpg)
klik tombol Create repository
25. Menambahkan Remote Repository
26. Untuk menambahkan remote repository server, gunakan perintah git remote add origin [url]
![9](https://user-images.githubusercontent.com/57063216/68044402-d3b68d00-fd09-11e9-9f0e-2ad912a11fb7.png)
27. Untuk mengirim perubahan pada local repository ke server gunakan perintah git push.
$ git push -u origin master
![10](https://user-images.githubusercontent.com/57063216/68044692-66efc280-fd0a-11e9-9cb8-d90ee0ae5a4d.png)

28. Buka laman github.com, arahkan pada repositorinya
29. perubahan akan terlihat pada laman tersebut
![20191030_232408](https://user-images.githubusercontent.com/57063216/68045280-b387cd80-fd0b-11e9-887f-56622e9fded5.jpg)
30. Clone repository, pada dasarnya adalah meng-copy repository server dan secara otomatis membuat satu direktory sesuai dengan nama repositorynya
31. Untuk melakukan cloning, gunakan perintah git clone [url]
![12](https://user-images.githubusercontent.com/57063216/68045573-648e6800-fd0c-11e9-9098-b41380a3365d.png)
Kegunaan file README.md
• Apabila kita menggunakan github, untuk memberikan penjelasan
awal pada project yang kita buat, maka dapat menggunakan sebuah
file yang bernama README.md
• Pada file tersebut kita dapat membuat dokumentasi awal dari setiap
project yang kita buat untuk memberikan penjelasan atau sekedar
cara penggunaan dari aplikasi yang kita kembangkan.
• Penulisan file README.md berbasis teks, dan untuk pemformatannya
menggunakan Markdown format.
• untuk lebih jelasnya, dapat anda pelajari cara penggunaan markdown
pada url berikut: https://guides.github.com/features/masteringmarkdown




















