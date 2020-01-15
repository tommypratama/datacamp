# The Android App Market on Google Play

Muat, bersihkan, dan visualisasikan data yang di scraped dari Google Play Store untuk memahami pasar aplikasi Android.

## Project Description

Aplikasi seluler ada di mana-mana. Mereka mudah dibuat dan bisa menguntungkan. Karena dua faktor ini, semakin banyak aplikasi yang dikembangkan. Dalam proyek ini, Anda akan melakukan analisis komprehensif tentang pasar aplikasi Android dengan membandingkan lebih dari sepuluh ribu aplikasi di Google Play di berbagai kategori. Anda akan mencari wawasan dalam data untuk menyusun strategi untuk mendorong pertumbuhan dan retensi.

[Data](https://www.kaggle.com/lava18/google-play-store-apps) untuk proyek ini diambil dari situs web [Google Play](https://play.google.com/store/apps?hl=en). Meskipun ada banyak kumpulan data populer untuk Apple App Store, tidak ada banyak untuk aplikasi Google Play, yang sebagian disebabkan oleh meningkatnya kesulitan dalam scraping yang terakhir dibandingkan dengan yang sebelumnya. File data adalah sebagai berikut:

* `apps.csv`: berisi semua detail aplikasi di Google Play. Ada 13 fitur yang menggambarkan aplikasi yang diberikan.
* `user_reviews.csv`: berisi 100 ulasan untuk setiap aplikasi, ( [*most helpful first*](https://www.androidpolice.com/2019/01/21/google-play-stores-redesigned-ratings-and-reviews-section-lets-you-easily-filter-by-star-rating/) ). Teks dalam setiap ulasan telah diproses sebelumnya dan dikaitkan dengan tiga fitur baru: Sentimen (Positif, Negatif atau Netral), Sentimen Polaritas dan Subjektivitas Sentimen.

## Prerequisite

- [x] [Python Data Science Toolbox (Part 1](https://github.com/tommypratama/datacamp/tree/master/Python%20Data%20Science%20Toolbox%20(Part%201))
- [x] [Manipulating DataFrames with pandas](https://github.com/tommypratama/datacamp/tree/master/Manipulating%20DataFrames%20with%20pandas)

## Source

* https://www.datacamp.com/projects/619