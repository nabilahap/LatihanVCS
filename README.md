# latihanNblh

![- 𝟑𝟎 𝐃𝐀𝐘𝐒_ 𝐓𝐑𝐔𝐓𝐇 𝐎𝐑 𝐃𝐀𝐑𝐄_](https://user-images.githubusercontent.com/92380488/137579775-a6b6a033-94b3-4601-b69e-8ca66e762288.gif)


# Instalasi Git
Download git terlebih dahulu, di website resmi [Git](https://git-scm.com/download)
# Tutorial Penggunaan Git
- Pada saat pertama kali mnggunakan git, peru dilakukan konfigurasi user.name dan user.email.
- Config Global Repository
> git config --global user.name "nama_user"

> git config --global user.email "nama_user"


![Gambar 1](ss/ss1.jpg)

- Setelah itu, buat direktory project pertama.
> mkdir latihanNblh

> cd latihanNblh

![Gambar 2](ss/ss2.jpg)

- Kemudian jalankan perintah git init< untuk membuat repository local.
> git init

![Gambar 3](ss/ss3.jpg)

- Untuk membuat file dapat menggunakan text editor, lalu menyimpan filenya pada repository. Disini saya membuat contoh satu file bernama README.md.
> echo "# latihanNblh" >> README.md

![Gambar 4](ss/ss4.jpg)

- Kemudian, untuk menambahkan file yang baru saja dibuat tersebut gunakan perintah **git add**.
> git add README.md

![Gambar 5](ss/ss5.jpg)

- Setelah itu, untuk menyimpan perubahan yang ada kedalam database repository local, gunakan perintah **git commit -m "komentar commit"**.
> git commit -m "Project Nabilah"

![Gambar 6](ss/ss6.jpg)

- Untuk menambahkan remote repository server, gunakan perintah **git remote add origin [url]**.
> git remote add origin https://github.com/nabilahap/LatihanVCS-3.git

![Gambar 7](ss/ss7.jpg)

- Kemudian, untuk mengirim perubahan pada local repository ke server gunakan perintah git push.
> git push -u origin master

![Gambar 8](ss/ss8.jpg)

- Selesai

# TERIMA KASIH




