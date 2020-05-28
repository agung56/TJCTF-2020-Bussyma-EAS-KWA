# Titanic - 35 points
## Description

I wrapped tjctf{} around the lowercase version of a word said in the 1997 film "Titanic" and created an MD5 hash of it: `9326ea0931baf5786cde7f280f965ebb`.

## Penyelesaian

hash MD5 tersebut berasal dari script film "Titanic" pada tahun 1977. Setiap katanya dibuat lowercase atau huruf kecil semua dan ditambahi dengan tjctf{}.
Langkah yang dilakukan adalah menyalin script film TItanic terlebih dahulu di [situs ini](http://sites.inka.de/humpty/titanic/script.html), kemudian dengan bantuan teks editor salah satunya vscode, ubah semua huruf menjadi huruf kecil serta hapus `.``,``:``/` dan ubah spasinya menjadi enter dan tambahkan tjctf{} di tiap barisnya.
Setelah itu gunakan perintah hashcat melalui terminal.

```
hashcat -m 0 -a 0 9326ea0931baf5786cde7f280f965ebb titanic.txt --force --show
```
Titanic.txt merupakan script film Titanic yang telah diubah.

## Flag

```
tjctf{marlborough's}
```