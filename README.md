# latihanNblh
![- 𝟑𝟎 𝐃𝐀𝐘𝐒_ 𝐓𝐑𝐔𝐓𝐇 𝐎𝐑 𝐃𝐀𝐑𝐄_](https://user-images.githubusercontent.com/92380488/137579775-a6b6a033-94b3-4601-b69e-8ca66e762288.gif)


# Instalasi Git
Download git terlebih dahulu, di website resmi [Git](https://git-scm.com/download)
# Tutorial Penggunaan Git
- Pada saat pertama kali mnggunakan git, peru dilakukan konfigurasi user.name dan user.email.
- Config Global Repository
> git config --global user.name "nama_user"

> git config --global user.email "nama_user"


![A1](https://user-images.githubusercontent.com/92380488/137577098-7bba163e-ab5f-4d91-917c-c96bd454d2d8.JPG)

- Setelah itu, buat direktory project pertama.
> mkdir latihanNblh

> cd latihanNblh

![A2](https://user-images.githubusercontent.com/92380488/137577331-67a50be9-f8c7-4682-8198-6ea01b187735.JPG)

- Kemudian jalankan perintah git init< untuk membuat repository local.
> git init

![A3](https://user-images.githubusercontent.com/92380488/137577808-c512c23d-74e5-4cbb-8cb5-77fcc2b91421.JPG)

- Untuk membuat file dapat menggunakan text editor, lalu menyimpan filenya pada repository. Disini saya membuat contoh satu file bernama README.md.
> echo "# latihanNblh" >> README.md

![A4](https://user-images.githubusercontent.com/92380488/137578108-c509b621-9910-46dc-9d7b-e612e81eca53.JPG)

- Kemudian, untuk menambahkan file yang baru saja dibuat tersebut gunakan perintah **git add**.
> git add README.md

![A5](https://user-images.githubusercontent.com/92380488/137578195-564b1554-d0a8-41d4-be32-c59f796d35a7.JPG)

- Setelah itu, untuk menyimpan perubahan yang ada kedalam database repository local, gunakan perintah **git commit -m "komentar commit"**.
> git commit -m "Project Nabilah"

![A6](https://user-images.githubusercontent.com/92380488/137578283-29139fdc-500b-42e0-876c-4422609f8006.JPG)

- Untuk menambahkan remote repository server, gunakan perintah **git remote add origin [url]**.
> git remote add origin https://github.com/nabilahap/LatihanVCS-3.git

![A7](https://user-images.githubusercontent.com/92380488/137578446-cb64a92b-1a05-4e79-8fd9-597af0bd365b.JPG)

- Kemudian, untuk mengirim perubahan pada local repository ke server gunakan perintah git push.
> git push -u origin master

![A8](https://user-images.githubusercontent.com/92380488/137578561-2c9249ac-09e6-410d-a660-85433a71628c.JPG)

- Selesai

# TERIMA KASIH
![minho tidak tau jika tugas nya kali ini harus…](https://user-images.githubusercontent.com/92380488/137579891-d9e8aa2c-911c-4752-9b4c-1030ed8914fe.gif)


