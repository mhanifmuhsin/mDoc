---
layout: post
title:  "Source code management"
date:   2020-07-23 09:9:00 +0700
categories: vcs
---

Reference [Attlasian](https://www.atlassian.com/git/tutorials/source-code-management)

Bahasan sebelumnya [Version control system](https://mhanifmuhsin.github.io/mDoc/vcs/2020/07/22/mengenal-version-control-system.html) 

---

_Source code management_ (SCM) digunakan untuk melacak ataupun memodifikasi ke repositori _source code_, SCM juga identik dengan _Version control._

SCM sangatlah penting ,karena SCM dapat mengatur _source code_ dengan jumlah kontributor yang banyak sehingga dapat menekan biaya pengembangan, biaya overhead komunikasi dan dapat menumbuhkan kompleksitas manajemen. 

Sebagai _software engineer_, SCM ini sangatlah membantu ketika kita sedang mengerjakan dalam basis kode yang sama secara bersamaan. Pengambang 1 dengan pengembang 2 dapat mengerjakan fitur masing-masing tanpa akan mengganggu pekerjaan dari pengembang lainnya, lebih dari itu pengembang 1 dan pengembang 2 dapat menggabungkan fitur nya dan melihat riwayat dari setiap perubahan. Kalaupun ada konflik dikarenakan overwriting, SCM mempunyai _safeguard_ yang berfungsi untuk melacak perubahan dari masing-masing pengembang individu dan secara otomatis akan mengidentifikasi area konflik dan mecegah overwrites, setelah itu SCM akan memberikan poin-poin atau informasi konflik tersebut ke pengembang sehingga mereka dapat meninjau dan mengatasi dengan aman.

Selain sebagai _version control_, SCM dapat juga mengembalikan basis kode ke titik waktu sebelumnya, dimana arsip SCM / atau pekerjaan yang kita _commit_ akan tersimpan dan dapat kita jadikan sebagai catatan berharga untuk transparansi sebuah proyek. Secara keseulurhan SCM sangat membantu bagi tim teknik yang akan menurunkan biaya pengembangan dengan memungkinkan sumber daya teknik untuk berdiskusi lebih efisien.

***Source code management best practies***
1. _Commit often_ (Sering melakukan commit)
2. _Ensure you're working from lates version_ (Pastikan anda bekerja dari versi terbaru)
3. _Make detailed notes (Buat catatan rinci)_
4. _Review changes before commiting_ (Tinjau perubahan sebelum melakukan commit)
5. _Use Branches_ (Gunakan cabang)
6. _Agree on a Workflow_ (Setuju pada alur kerja), dengan maksud alur kerja SCM untuk menentukan pola dan proses menggabungan cabang.

Sekian postingan mengenai _Source code management_ .

---
Bahasan selanjutnya [Apa itu Git ?](https://mhanifmuhsin.github.io/mDoc/vcs/2020/07/25/apa-itu-git.html)
