## Vidio.com HTML
Just for learning purpose

<table border="1">
    <tr>
        <td>Deskripsi Project</td>
        <td>Project membuat replikasi seperti vidio.com</td>
    </tr>
    <tr>
        <td>Nama Project</td>
        <td>replikasi vidio.com</td>
    </tr>
</table>

## How to add key - github

```
1. visit link: https://github.com/andrideng/vidio-dot-com-html/settings/keys
2. run command: ssh-keygen -t rsa -b 4096 -C "ninefoxlab@gmail.com"
    . give filename, example: nfl
3. cat nfl.pub
    . copy public key to deploy key (github)
    . tick allow access to write
    . save
4. run command: eval "$(ssh-agent -s)"
5. ssh-add nfl
```

## Step untuk push project ke github
```
1. git add .
2. git commit -m "pesan commit"
3. git push origin main
```

Readme menggunakan markup language

# Judul 1
Alternative Judul 1
===================

## Judul 2
Alternative Judul
-----------------

### Judul 3

###### Judul ada sampai 6


Ini adalah contoh _garis miring_ 

Ini adalah contoh garis *miring dengan asteriks*

Ini adalah contoh __bold text - cara 1 gunakan (underscore dua)__

Ini adalah contoh **bold text - cara 2 gunakan (asteriks dua)**

Combined emphasis with **asterisks and _underscores_**.

Strikethrough uses two tildes. ~~Scratch this~~.


Contoh Link:

[Dokumentasi Lebih lengkap readme](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

[Readme Best Practice - 1](https://www.freecodecamp.org/news/how-to-write-a-good-readme-file/)

[Readme Best Practice -2](https://github.com/jehna/readme-best-practices)