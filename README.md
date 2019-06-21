# frontend-guideline
Frontend Guideline

## Pra-iterasi project:
- Tim frontend sudah memiliki tool development yang dibutuhkan (IDE, CSS preprocessor (SASS) compiler, browser, server lokal)
- Tim frontend sudah memiliki akses ke repository project yang akan dikerjakan. Jika belum memiliki, dikoordinasikan dengan dev leader untuk dibuatkan.
- Siapkan lingkungan untuk develop di workstation lokal (server apache, node, dan atau database). 
- Init atau clone repository project di server lokal. 

## Awal tiap iterasi project (sprint):
- Sebelum mengerjakan tugasnya, tim frontend sudah memahami apa yang harus dikerjakan terlebih dahulu.
- Pastikan apa yang akan dikerjakan sudah ada di halaman Trello project tersebut.
- Jika belum ada di Trello, mintalah ke PM atau buatlah card/ceklist sendiri.
- Pastikan preview desain dan file asset dari desainer sudah tersedia. 

## Proses mengerjakan dan definisi selesai:
- Jika website yang dibuat responsive, kerjakan dari mobile terlebih dahulu
- Sebisa mungkin buatlah class dan komponen-komponen yang modular
- Pastikan nama class mampu menjelaskan peran komponen yang dibuat
- Pisahkan styling untuk layout (display, position, width, height, dsb.) dengan presentasi (background, color, font, shadow, dsb.). Bisa mengacu pada konsep [BEM (Block Element Modifier)](https://en.bem.info/methodology/css/)
- Gunakan variabel dan mixin pada preprocessor CSS
- Pisahkan fungsi-fungsi per komponen atau lebih modular lagi untuk JS yang dibuat
- Pisahkan plugin css & js yang digunakan dari css dan js yang dibuat sendiri 
- Pastikan elemen html, css, dan js yang akan digunakan memiliki support menyeluruh untuk browser-browser utama dan/atau browser yang diminta khusus oleh klien. Daftar teknologi yang bisa digunakan bisa dilihat di https://caniuse.com/
- Lakukan test mandiri untuk responsive dan retina display
- Pastikan apa yang sudah dikerjakan tersinkron dengan repositori
- Tugas yang dikerjakan bisa dianggap selesai jika sudah melewati approval desainer (jika developer inhouse) dan QA
- Ubah status pekerjaan di Trello

## Setiap project yang dikerjakan DOT harus memenuhi standar kualitas yang harus terpenuhi berupa:
- Memiliki ranking page speed & performance yang baik (diuji dengan google chrome audit, pagespeed insight, dan )
- Responsive (minimal mobile dan desktop)
- Meta data properness (google preview, facebook preview, messenger app preview)
- Shortcut icon yang baik (android, ios)
CDN untuk asset

## Standard Code
[Standard Code](https://github.com/pt-dot/frontend-guideline/StandardCode.md)