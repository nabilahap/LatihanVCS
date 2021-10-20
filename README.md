# latihanNblh

![- 𝟑𝟎 𝐃𝐀𝐘𝐒_ 𝐓𝐑𝐔𝐓𝐇 𝐎𝐑 𝐃𝐀𝐑𝐄_](ss/A0.gif)


# Instalasi Git
Download git terlebih dahulu, di website resmi [Git](https://git-scm.com/download)
# Tutorial Penggunaan Git
- Pada saat pertama kali mnggunakan git, peru dilakukan konfigurasi user.name dan user.email.
- Config Global Repository
> git config --global user.name "nama_user"

> git config --global user.email "nama_user"


![Gambar 1](ss/ss1.JPG)
- Setelah itu, buat direktory project pertama.
> mkdir latihanNblh

> cd latihanNblh


![Gambar 2](ss/ss2.JPG)
- Kemudian jalankan perintah git init< untuk membuat repository local.
> git init


![Gambar 3](ss/ss3.JPG)
- Untuk membuat file dapat menggunakan text editor, lalu menyimpan filenya pada repository. Disini saya membuat contoh satu file bernama README.md.
> echo "# latihanNblh" >> README.md


![Gambar 4](ss/ss4.JPG)
- Kemudian, untuk menambahkan file yang baru saja dibuat tersebut gunakan perintah **git add**.
> git add README.md

![Gambar 5](ss/ss5.JPG)
- Setelah itu, untuk menyimpan perubahan yang ada kedalam database repository local, gunakan perintah **git commit -m "komentar commit"**.
> git commit -m "Project Nabilah"


![Gambar 6](ss/ss6.JPG)
- Untuk menambahkan remote repository server, gunakan perintah **git remote add origin [url]**.
> git remote add origin https://github.com/nabilahap/LatihanVCS-3.git


![Gambar 7](ss/ss7.JPG)
- Kemudian, untuk mengirim perubahan pada local repository ke server gunakan perintah git push.
> git push -u origin master


![Gambar 8](ss/ss8.JPG)


- Selesai

# TERIMA KASIH



