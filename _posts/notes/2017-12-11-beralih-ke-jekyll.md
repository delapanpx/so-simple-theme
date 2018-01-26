---
layout: post
title: "Beralih ke Jekyll"
excerpt: "Setelah menggunakan blogspot, entah mengapa saya kangen banget sama Jekyll"
categories: notes
tags: [techno, webdev]
image:
  feature: 
  thumb: jekyll.jpg
  credit:  
  creditlink: 
comments: false
share: true
---

Sudah cukup banyak platform untuk ngeblog yang saya cobain, mulai dari [wordpress.com](https://wordpress.com) (subdomain wordpress, free), kemudian pindah ke [blogspot](https://blogger.com), lalu kemudian pindah ke [tumblr](https://tumblr.com), kemudian sempat nyaman ngeblog di [medium](https://medium.com), lalu sempet pindah ke [postach](https://postach.io), terus hosting sendiri [wordpress](https://wordpress.org), lalu kemudian nyobain web statis seperti [Jekyll](https://jekyllrb.com/) dan [Grav](https://getgrav.org/). Kemudian terakhir saya kembali menggunakan Blogspot cukup lama.

Setelah menggunakan blogspot, entah mengapa saya kangen banget sama Jekyll, web statis yang ternyata banyak banget yang pake, walaupun rata-rata penggunanya adalah programmer. Perbedaan dengan Grav adalah jekyll menurut saya lebih mudah dikostumisasi, dan juga minim error, maksudnya, ketika saya pake Grav CMS terus otak-atik tema dan plugin, entah kenapa tau-tau error, dan saya engga tau sama sekali letak kesalahannya.

Community support pada Grav CMS yang minim ini (terkahir pake grav di tahun 2014) menjadi alasan juga kenapa saya mulai meninggalkan Grav CMS. Tapi saat ini saya rasa community supportnya sudah lebih baik, hanya saja saya cukup sulit mengoperasikan panel adminnya. Berbeda dengan jekyll yang rasanya mudah sekali dan tidak perlu ribet mengoperasikan panel admin, cukup edit di editor kemudian tinggal commit dan push. Atau kalau tidak menggunakan pc sendiri, tinggal buka [github.com](https://github.com) kemudian tambah file post.

Sebagai awalan, saya langsung fork/kloning [template yang bagus](https://mademistakes.com/work/so-simple-jekyll-theme/) ke repository github saya. Namun seperti kebiasaan saya, saya engga memakai secara gitu aja template yang saya kloning, saya melakukan cukup banyak perubahan pada layout, font, dan settingan. Semuanya saya setup menggunakan sublime text 2, bahkan untuk menulis post juga menggunakan Sublime Text 2.

## Sedikit Setup 

Buat pengguna Windows seperti saya, kamu bisa [menginstall jekyll menggunakan command prompt dan chocolatey](https://davidburela.wordpress.com/2015/11/28/easily-install-jekyll-on-windows-with-3-command-prompt-entries-and-chocolatey/ "Easily install Jekyll on Windows with 3 command prompt entries and Chocolatey"). Tujuan menginstall jekyll di windows adalah supaya development bisa dilakukan offline. Cara menginstallnya mudah banget, apalagi buat pengguna windows 10 yang sudah Anniversary Update, karena bisa menggunakan command seperti di linux atau mac.

> Buat pengguna windows 10, bisa menginstall jekyll menggunakan cara ini: [Jekyll on Windows](https://jekyllrb.com/docs/windows/). 

## Deploy ke netlify

Saya mendeploy repository yang berisi website jekyll saya ini ke [Netlify](https://www.netlify.com/), karena mudah dikostumisasi untuk penggunaan custom domain. Selain itu saya bisa dengan mudah mengganti repository tanpa harus setup CNAME di setiap reponya, jadi tanpa DNS propagansi, saya bisa mengganti website dengan repository Github yang berbeda. 

Bahkan dengan satu repository, kita bisa membuat sub domain yang berbeda untuk setiap branch-nya menggunakan Netlify.

Selain github pages, Netlify juga bisa untuk web statis lainnya seperti [Hugo](https://gohugo.io/). Namun karena masih cinta sama jekyll, jadi saya hanya fokus ke Jekyll dulu saja.  

## Credit
- [Jekyll Documentation](https://jekyllrb.com/docs/home/)
- [Easily install Jekyll on Windows with 3 command prompt entries and Chocolatey](https://davidburela.wordpress.com/2015/11/28/easily-install-jekyll-on-windows-with-3-command-prompt-entries-and-chocolatey/)
- [Using Jekyl 2017](https://mademistakes.com/articles/using-jekyll-2017/) - Mademistakes
- [Netlify Custom Domain](https://www.netlify.com/docs/custom-domains/)



