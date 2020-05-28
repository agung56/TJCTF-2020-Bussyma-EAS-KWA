# Sarah Palin Page - 35 points
## Description

Are you a true fan of Alaska's most famous governor? Visit the [Sarah Palin fanpage](https://sarah_palin_fanpage.tjctf.org/).

## Penyelesaian

Menuju [halaman VIP](https://sarah_palin_fanpage.tjctf.org/exclusive) pada web tersebut. Kemudian menuju ke inspect elemen. Pada bagian cookie, salin value pada data tersebut dan kemudian didecode dengan [base64](https://cryptii.com/pipes/text-to-base64). Hasil decode akan tampak sebagai berikut:
`{"1":false,"2":false,"3":false,"4":false,"5":false,"6":false,"7":false,"8":false,"9":false,"10":false}`

Ubah kata **false** menjadi **true** dan encode kembali lalu kembalikan ke value cookie dan refresh halamannya.

## Flag

```
tjctf{wkDd2Pi4rxiRaM5lOcLo979rru8MFqVHKdTqPBm4k3iQd8n0sWbBkOfuq9vDTGN9suZgYlH3jq6QTp3tG3EYapzsTHL7ycqRTP5Qf6rQSB33DcQaaqwQhpbuqPBm4k3iQd8n0sWbBkOf}
```