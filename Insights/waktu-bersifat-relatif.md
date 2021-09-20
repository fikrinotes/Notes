---
title: Fikri Notes
--- 

# Apakah Waktu Bisa Melambat ?

mungkin di antara kalian ada yang pernah menonton film interstellar.Film tersebut bercerita tentang perjalanan tokoh utamanya (cooper) untuk mecari planet baru untuk ditinggali manusia.

nah,ceritanya cooper punya anak yang masih kecil,namanya murphy,yang tetap tinggal di bumi.sementara cooper pergi ke planet miller,untuk penyelidikan.terus cooper berkata kalau timnya mereka harus bergerak cepat karena 1 jam di planet miller sama dengan 7 tahun di bumi,karena periode revolusi planet miller yang sangat cepat,mendekati kecepatan cahaya.dan benar saja,ketika cooper kembali dari planet miller,murphy sudah berusia 23 tahun di bumi.padahal di planet miller,waktu baru berjalan 1 hari.

Oke,kita tau bahwa film tersebut hanyalah film fiksi.namun,apakah waktu benar benar bisa berjalan lebih lambat/lebih cepat?

sebenarnya pertanyaan di atas tidak berarti apa apa,pertanyaan di atas baru memiliki arti jika pertanyaannya berbunyi: 

> _"apakah waktu di suatu tempat bisa berjalan lebih cepat/lebih lambat daripada waktu di tempat lain?"_

kenapa pertanyaannya harus seperti itu?karena dalam fisika,suatu pernyataan tidak bermakna apa-apa kecuali memiliki kerangka acuan.misalnya pernyataan "bus bergerak" tidak bermakna apa-apa.tetapi pernyataan "bus bergerak terhadap stasiun" memiliki makna.hal ini karena walaupun bus bergerak terhadap stasiun,bus tidak bergerak terhadap penumpang di dalamnya.karena itulah "gerak" bersifat relatif.inilah dasar dari teori relativitas khusus einstein.

Balik lagi ke pertanyaan tadi,jawabannya adalah:**bisa**.alasannya bersumber dari teori relativitas khusus einstein.dalam teorinya, einstein mengajukan 2 postulat,yaitu:
1. kecepatana cahaya selalu sama walau diamati dari kerangka acuan yang berbeda.berbeda dengan bus yang kecepatannya berubah tergantung pengamat,kecepatan cahaya selalu sama.dengan kata lain,kecepatan cahaya bersifat mutlak.
2. hukum fisika yang berlaku selalu sama dalam setiap kerangka acuanyang berarti,darimana pun kita mengamati suatu peristiwa,hukum fisika yang terjadi/yang kita rasakan selalu sama, tidak berubah.jadi tidak ada kerangka acuan yang lebih baik daripada kerangka acuan yang lain, semuanya sama.

dengan 2 postulat ini,kita dapat menunjukkan bahwa "waktu" benar-benar relatif.misalkan ada pengamat O' yang diam di atas kereta yang bergerak dengan kecepatan $v$ terhadap tanah, sambil memegang sebuah laser yang diarahkan ke bagian atas kereta.di bagian atas kereta terdapat sebuah cermin yang berjarak $d$ dari laser. Lalu misalkan diluar kereta ada pengamat O yang diam terhadap tanah. menurut pengamat O' yang berada di dalam kereta,jalur lintasan cahaya laser akan terlihat seperti berikut:

<div align="center">

<img src="https://fikrinotes.netlify.app/rel1.JPG" alt="image"/>

</div>

karena kecepatan cahaya adalah $c$ ,dan jarak antara laser ke cermin adalah $d$, maka waktu yang dibutuhkan oleh laser untuk menuju cermin dan balik lagi menurut pengamat O' adalah 

$$
∆t_p = \frac{2d}{c}
$$


$$
d= \frac{∆t_p.c}{2}...(1)
$$

dimana $∆t_p$ adalah waktu menurut pengamat O'

sedangkan menurut pengamat O yang diam di luar kereta, lintasan cahaya laser akan terlihat seperti ini:

<div align="center">
<img src="https://fikrinotes.netlify.app/rel2.JPG" alt="image 2"/>
</div>

sesuai postulat einstein yang pertama, pengamat O akan melihat bahwa garis diagonal di atas ditempuh cahaya dengan kecepatan $c$ pula,dan dalam rentang waktu $∆t$ untuk menuju cermin dan memantul kembali($∆t$ adalah waktu yang dirasakan pengamat O).jadi panjang 1 garis diagonal adalah $\frac{∆t.c}{2}$. lalu karena kereta bergerak dengan kecepatan $v$ dan waktu yang dibutuhkan agar cahaya laser sampai ke cermin dan kembali adalah $∆t$,maka waktu yang diperlukan cahaya untuk sampai ke cermin tanpa memantul adalah $\frac{∆t}{2}$. sehingga panjang garis horizontal adalah $\frac{v∆t}{2}$.untuk lebih jelasnya perhatikan gambar berikut:

<div align="center">

<img src="https://fikrinotes.netlify.app/rel3.JPG" alt="image3"/>

</div>

lalu dengan teorema pythagoras,kita dapat menyatakan: 

$$
d^2+(\frac{v∆t}{2})^2=(\frac{c.∆t}{2})^2
$$

lalu substitusi nilai $d$ dari persamaan 1:

$$
(\frac{c∆t_p}{2})^2+(\frac{v∆t}{2})^2=(\frac{c.∆t}{2})^2
$$

$$
\frac{c∆t_p}{2}=\sqrt[2]{\frac{∆t^2}{4}(c^2-v^2)}
$$

jika disederhanakan akan menjadi:

$$
∆t=\frac{∆t_p}{\sqrt[2]{1-\frac{v^2}{c^2}}}
$$

jika kita tetapkan $\gamma =\frac{1}{\sqrt[2]{1-\frac{v^2}{c^2}}}$ maka: 

$$
∆t=\gamma ∆t_p
$$ 

karena nilai $v$ selalu lebih kecil daripada nilai $c$,maka $\gamma\geq1$. berarti waktu yang dirasakan oleh pengamat yang diam terhadap tanah($∆t$) lebih lama daripada waktu yang dirasakan oleh pengamat yang bergerak terhadap tanah ($∆t$).

fenomena perbedaan waktu yang dirasakan pengamat kedua pengamat tersebut dikenal dengan nama **dilatasi waktu**. 

# Bukti Nyata 
fenomena dilatasi waktu telah memiliki banyak bukti walaupun terukur dalam skala kecil. contoh nyata tentang dilatasi waktu yaitu partikel mu-mesons(muons). muons adalah partikel elementer yang tidak stabil yang memiliki muatan seperti elektron dan massanya 207 kali elektron. muons terbentuk di atmosfer. muons hanya berumur 2,2$\mu s$ jika dikukur menurut pengamat yang diam terhadap partikel tersebut,dengan kata lain $∆t_p=2,2\mu s$. dengan umur sepanjang itu,muons hanya menempuh jarak sekitar 600m sebelum partikel tersebut rusak. partikel muons tidak akan pernah mencapai permukaan bumi walaupun dengan kecepatan mendekati kecepatan cahaya.tapi nyatanya para ilmuwan menunjukkan bahwa muons bisa sampai ke bumi sebelum partikel tersebut rusak.peristiwa ini adalah bukti dari dilatasi waktu yang dialami muons.muons memiliki kecepatan sekitar 0,99$c$,maka $\gamma=7.1$,sehingga $∆t=\gamma∆t_p=7,1×2,2=15,6\mu s$, waktu yang cukup bagi muons dengan kecepatan mendekati kecepatan cahaya untuk mencapai permukaan bumi. 

hasil yang sama juga ditunjukkan oleh eksperimen yang dilakukan oleh joseph C.hafel dan richard E.keating dalam eksperimen yang bernama Hafel-keating experiment.Di dalam _paper_ mereka,mereka menulis:"Relatif terhadap waktu atom skala Observatorium Angkatan Laut AS, jam terbang kehilangan 59 ns selama perjalanan ke timur dan naik 273 ns selama perjalanan ke barat" .ya,beda waktu nya cuma dalam satuan nanosekon,tapi itu eksperimen yang cukup untuk membuktikan dilatasi waktu.

jadi waktu di suatu tempat memang bisa melambat terhadap waktu di tempat lain,fenomena ini disebut dilatasi waktu.sekian penjelasan untuk kali ini,terimakasih atas perhatiannya.

{% include footer.html %}
