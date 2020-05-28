# Ling Ling - 10 points
## Description

Who made this [meme](https://static.tjctf.org/d25fe79e6276ed73a0f7009294e28c035437d7c7ffe2f46285e9eb5ac94b6bec_meme.png)? [I made this meme](https://www.reddit.com/r/lingling40hrs/comments/gam2if/this_popped_in_my_mind_as_i_was_playing_it_and_i/)! unless...

## Penyelesaian

Unduh gambar meme dan setelah dilihat gambar tersebut terdapat not balok chopins Third Ballade. Dari permasalahan tersebut dapat diketahui bahwa yang dicari adalah pembuat dari meme tersebut. Untuk mendapatkan data tersebut dapat menggunakan perintah `exiftool` lalu grep Artist.

`$ exiftool meme.png | grep Artist`

## Flag

```
tjctf{ch0p1n_fl4gs}
```