# Rap God - 40 points
## Description

My rapper friend Big Y sent me his [latest track](./BigYAudio.mp3) but something sounded a little off about it. Help me find out if he was trying to tell me something with it. Submit your answer as tjctf{message}

## Penyelesaian

Berdasarkan file yang ada, saya berpikir bahwa flag tersebut berada dalam file mp3 tersebut. Saya coba menggunakan audacity untuk mendapatkan waveform dan spectogram yang ada pada file mp3 tersebut. Kemudian didapatkan tampilan sebagai berikut.

![rapgod](./rapgod.jpg)

Setelah melihat simbol pada gambar tersebut, dapat diketahui bahwa simbol tersebut merupakan wingdings character. Lalu translate simbol-simbol tersebut dan menghasilkan kata QUICKSONIC

## Flag

```
tjctf{QUICKSONIC}
```
