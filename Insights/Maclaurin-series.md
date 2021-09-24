---
title: Maclaurin Series In A Nutshell
description: Fikri Notes
---

<center>
  <img alt="image" src="https://fikrinotes.netlify.app/img-for-maclaurin.jpeg"/>
</center>

Saat berada di bangku SMA, tentunya anda pernah belajar tentang deret geometri, seperti 1,2,4,8,16,32,... . jika deret tersebut berlanjut sampai tak hingga, anda mengetahui bahwa jumlah nilai total semua suku sama dengan $S_n = \frac{a}{(1-r)}$.

tapi bagaimana caranya kita bisa memnentuk kembali deret tersebut dari formula $S_n = \frac{a}{(1-r)}$? ya, kita punya deret maclaurin / maclaurin series untuk menangani hal itu. apa itu deret maclaurin , dan bagaimana cara kerjanya?

deret maclaurin adalah deret yang pada dasarnya merupakan kasus khusus dari [Taylor Series](https://id.m.wikipedia.org/wiki/Deret_Taylor) di titik x=0. secara umum, kegunaan dari deret maclaurin adalah untuk membentuk persamaan dari kurva yang belum diketahui persamaannya dengan bermodalkan karakteristik dari kurva tersebut. karakteristik yang dimaksud adalah seberapa cepat sebuah titik di kurva itu berubah/gradient kurva di titik tersebut (=turunan pertama kurva tersebut),lalu seberapa cepat perubahan gradient kurva tersebut berubah (bisa diperoleh dari turunan kedua kurva tersebut), dan seterusnya.

lebih jelasnya seperti ini: 

<center>
  <img alt="image" src="https://fikrinotes.netlify.app/mac1.jpg"/>
</center>

misalkan anda memiliki kurva seperti gambar di atas. kurva di atas kita anggap terbentuk dari fungsi f(x). lalu kita ingin mencari tau formula untuk f(x) tersebut. misalkan formula yang kita dapatkan adalah p(x). jika kita ingin curva p(x) yang kita dapatkan dan kita ketahui formulanya memiliki bentuk yang sama dengan kurva f(x),tentu saja kita harus bisa menunjukkan bahwa kurva f(x) dan kurva p(x) memiliki karakteristik yang sama. maksudnya adalah jika kita ingin kurva p(x)=f(x), maka seharusnya:

$$
f(0)=p(0), f'(0)=p'(0), f"(0)=p"(0), f^{(3)}(0)=p^{(3)}(0),..
$$

jika kita ingin semua syarat di atas terpenuhi, maka formula yang mungkin untuk mengekspresikan f(x) adalah :

<div style="overflow-x: auto">
$$
f(x)=f(0)+f'(0)x+\frac{f"(0)}{2!}x^2 +\frac{f^{(3)}(0)}{3!}x^3 +\frac{f^{(4)}(0)}{4!}x^4+...
$$
</div>

{% include footer.html %}
