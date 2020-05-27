# RSABC - 50 points
## Descryption

I was just listening to some [relaxing ASMR](https://www.youtube.com/watch?v=J2g3lvNkAfI&feature=youtu.be) when a notification popped up with [this](https://static.tjctf.org/68f148e8d4b5ceb8f9fa6da568db024c28b80b55891fba49880b76b35d436114_rsa.txt)

```
n = 57772961349879658023983283615621490728299498090674385733830087914838280699121`
e = 65537
c = 36913885366666102438288732953977798352561146298725524881805840497762448828130
```

## Penyelesaian

Soal ini mirip dengan soal Easy as RSA pada TJCTF 2019. Langkah pertama yang dilakukan adalah melakukan faktorisasi pada `n` menggunakan [website](factordb.com). Faktor dari `n` kemudian disimpan dalam `p` dan `q`

```
p = 202049603951664548551555274464815496697
q = 285934543893985722871321330457714807993
```
Masukkan `n`, `e`, `c`, `p` dan `q` ke [solve.rb](./solve.rb). Gunakan terminal untuk menjalankan program ruby dan flag akan muncul langsung
`$ruby solve.rb`

## Flag

```
tjctf{BOLm1QMWi3c}
```
