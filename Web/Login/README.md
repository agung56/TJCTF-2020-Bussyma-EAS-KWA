# Login - 30 points
## Description

Could you login into this [very secure site](https://login.tjctf.org/)? Best of luck!

## Penyelesaian

Dalam website tersebut berisi tulisan **Can you log in?** dan terdapat dua kotak untuk mengisi username dan password beserta tombol **login** dibawahnya.
Untuk mengetahui cara loginnya, klik F12 untuk menuju ke inspect elemen. Pada bagian sources, kita dapat mengetahui bahwa password dihash menggunakan md5. Pada file index, line 70 berisi kode seperti berikut:

```
var _0xb31c=['value','c2a094f7d35f2299b414b6a1b3bd595a','Sorry.\x20Wrong\x20username\x20or\x20password.','admin','tjctf{','getElementsByName','toString'];
```
Dari situ dapat diketahui bahwa username adalah admin dan c2a094f7d35f2299b414b6a1b3bd595a adalah hash md5 dari passwordnya. Buka [md5 decrypt](https://www.md5online.org/md5-decrypt.html) dan lakukan decrypt pada tersebut. Akan didapat bahwa passwordnya adalah inevitable. 
Masukkan username : Admin dan password : inevitable.

## Flag

```
tjctf{inevitable890898}
```