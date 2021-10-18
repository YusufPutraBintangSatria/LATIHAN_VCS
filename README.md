# LATIHAN_VCS
# Tutorial Menggunakan Git
## Requirements
- [Git](https://git-scm.com/download)
## Informasi
Apa itu Git?
<p>
Git merupakan software berbasis Version Control System (VCS) yang bertugas untuk mencatat perubahan seluruh file atau repository suatu project. Developer software biasa menggunakan Git untuk distributed revision (VCS terdistribusi), hal ini bertujuan untuk menyimpan database tidak hanya ke satu tempat. Namun semua orang yang terlibat dalam penyusunan kode dapat menyimpan database ini.
</p>

# Tutorial
- Pada saat pertama kali menggunakan Git, perlu dilakukan konfigurasi
Username dan Email. Jalankan perintah berikut:
```bash
> git config --global user.name "username"
> git config --global user.email "email"
```
![Screenshot (5)](https://user-images.githubusercontent.com/92704969/137703537-7a7778ac-772b-4dfc-bfb2-efebc131bde6.png)
- Jalankan perintah git init. untuk membuat repository local
```bash
> git init
```
![Screenshot (6)](https://user-images.githubusercontent.com/92704969/137707052-66ca91c7-4520-4e4d-ad36-1c1d1aa4e7de.png)
- Untuk membuat file dapat menggunakan Text Editor, Lalu menyimpan
filenya pada repository. Sebagai contoh disini saya akan membuat file README.md dengan perintah berikut
```bash
> echo "# latihanvcs" >> README.md
```
![Screenshot (7)](https://user-images.githubusercontent.com/92704969/137707500-28ddfc34-e147-40b4-91cf-3bfa044dfd5f.png)
- Untuk menambahkan file yang sudah kita buat, gunakan perintah git add (Nama File) atau bisa menggunakan git add . (Jika file nya ada banyak)
```bash
> git add README.md
> git add .
```
![Screenshot (8)](https://user-images.githubusercontent.com/92704969/137707599-6b48217d-33c7-41dc-8787-a96aa51736f5.png)
- Untuk menyimpan perubahan yang ada kedalam database repository
local, gunakan perintah git commit -m "nama project"
- Dan yang ada di dalam tanda kutip " " itu nama project kita dan jangan sama setiap kali kita upload project
```bash
> git commit -m "First Project"
```
![Screenshot (9)](https://user-images.githubusercontent.com/92704969/137707716-7a70dbb3-87fd-471d-9d2e-52b4aa0f6c79.png)
- Untuk menyimpan setiap perubahan pada repository local, gunakan perintah git remote add origin (url)
```bash
> git remote add origin https://github.com/YusufPutraBintangSatria/LATIHAN_VCS.git
```
![Screenshot (10)](https://user-images.githubusercontent.com/92704969/137708010-4d608a1e-f82a-44d3-a404-dd9af1bf82b8.png)
- Untuk mengirim perubahan pada repository local ke server, gunakan perintah git push
- Perintah ini akan meminta Username dan Password pada akun github mu
```bash
> git push -u origin master
```
![Screenshot (11)](https://user-images.githubusercontent.com/92704969/137708301-4b27280e-0c20-431d-a1b3-32695b701ae7.png)
- Selesai

# TERIMAKASIH
