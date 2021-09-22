---
title: Apa Itu Limit?
description: Fikri Notes
---

<link rel="shortcut icon" type="image/png" href="https://fikrinotes.netlify.app/logo_fix.png">

<center>
<img alt="image" src="https://miro.medium.com/max/1128/1*5Tu6aWuWveoyX-5HYnksRA.png" width="500"/>
</center>

# Apa Itu Limit?
Sebenarnya, arti _limit_ dalam matematika itu sama saja dengan arti _limit_ dalam bahasa Inggris. Dalam bahasa Inggris, limit berarti **batas** atau **batasan**. Nah, arti tersebut juga berlaku pada istilah _limit_ dalam matematika. Jadi, limit adalah batasan. Pertanyaannya sekarang adalah, _"apa yang kita batasi?"_

Cuma sebagai pengingat, pada fungsi $f(x)=2x+3$, $x$ disebut sebagai domain dan $f(x)$ disebut sebagai kodomain. Nah, dalam konsep limit, **kita membatasi nilai x(domain) agar hanya mendekati suatu nilai, tapi bukan persis sama dengan nilai tersebut**. Contohnya, jika kita menyebut limit x mendekati 0, berarti kita membatasi agar nilai x tersebut hanya mendekati nol, tapi bukan x=0. Dengan kata lain, bisa saja x-nya itu 1, 0.1, 0.01, 0.001, 0.0001, dan seterusnya. Mari kita sebut angka yang didekati ini sebagai $a$. Kenapa kita memakai konsep "mendekati"? Ini karena dalam beberapa kasus matematika/fisika, kita tidak bisa begitu saja menghitung suatu nilai untuk $x=a$. Akan tetapi, kita bisa menghitung suatu nilai untuk **x mendekati a**. Seperti apa contohnya? Coba lihat soal ini :

<center>
<img alt="soal 1" src="https://miro.medium.com/max/1128/1*qW8l8rBLkioPkRz5hL-j2g.png"/>
</center>

Jika kamu menghitungnya dengan benar, kamu akan menemukan bahwa jawaban soal di atas adalah 0/0, _alias_ tidak terdefinisi. Tapi untuk suatu dan lain hal, kita tetap perlu mengetahui nilai $f(x)$ untuk $x$ mendekati 1 ini. Nah, disinilah konsep limit akan berguna. Kita bisa menghitung nilai $f(x)$ untuk x mendekati 1. Kata _mendekati_ disini berarti nilai x sangat-sangat dekat dengan 1, contohnya $x=0.999999...$ atau $x=1.000000...009$. kedua nilai tersebut sangat dekat dengan 1 sehingga nilai ini bisa dianggap merepresentasikan nilai yang tepat untuk f(1) (walaupun nilai f(1) sebenarnya tidak ada).

<center>

<img alt="image" src="https://miro.medium.com/max/1400/1*LRqHaLoSxSlok-onJMzcxA.png"/>

</center>

Pada grafik di atas, kita tetap bisa melihat nilai untuk x=1 karena sebenarnya itu hanyalah nilai limit untuk x mendekati 1. Coba lihat animasi berikut :

<center>

<img alt="image" src="https://miro.medium.com/max/1400/1*3T8p3VLmF22nciAVzh-O-Q.gif"/>

</center>

Kita tidak bisa mengatakan bahwa saat nilai x adalah 1, nilai y adalah 2. Walaupun begitu, kita tau bahwa saat nilai x sangat dekat dengan 1, maka nilai y akan sangat dekat dengan 2. Nah, untuk menyatakan hal ini, matematikawan menggunakan istilah _**limit**_. Jadi, grafik di atas dapat dinayatakan sebagai :
> _Nilai limit dari $y$ saat $x$ mendekati 1_

Dalam persamaan matematis, pernyataan tersebut bisa dituliskan sebagai :

$$
\lim \limits_{x->1} y = \lim \limits_{x->1} \frac{x^2-1}{x-1} = 1
$$  





{% include footer.html %}
