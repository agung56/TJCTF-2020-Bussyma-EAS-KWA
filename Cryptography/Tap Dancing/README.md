# Tap Dancing - 25 points
## Descryption

My friend is trying to teach me to dance, but I am not rhythmically coordinated! They sent me a list of [dance moves](https://static.tjctf.org/518d6851c71c5482dbd5bbe812b678684238c8f4e9e9b3d95a188f7db83a0870_cipher.txt) but they're all numbers! Can you help me figure out what they mean so I can learn the dance?

NOTE: Flag is not in flag format.

1101111102120222020120111110101222022221022202022211

## Penyelesaian

Kode angka tersebut adalah morse code. <br>
1 melambangkan - atau _ <br>
2 melambangkan . <br>
0 melambangkan (spasi) <br>
Kode angka tersebut diubah menjadi kode morse <br>
`-- ----- .-. ... . -. ----- - -... ....- ... . ...--`

Dengan bantuan [morse translator](https://morsecode.world/international/translator.html), kita dapat menerjemahkan morse tersebut.

## Flag

```
M0RSEN0TB4SE3
```