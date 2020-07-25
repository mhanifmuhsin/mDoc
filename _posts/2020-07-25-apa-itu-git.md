---
layout : post
title : "Apa itu Git ?"
date:   2020-07-25 15:17:00 +0700
categories: vcs
---

Reference [Attlasian](https://www.atlassian.com/git/tutorials/what-is-git)

Bahasan sebelumnya [Source code management](https://mhanifmuhsin.github.io/mDoc/vcs/2020/07/23/source-code-management.html)

---

Git salah satu _version control_ moderen yang paling banyak digunakan oleh pengembang proyek perangkat lunak, Git merupakan proyek _open source_  yang matang dan dipelihara secara aktif, Linus Torvald adalah pengembang awal dari Git pada tahun 2005.

Git memiliki arsitektur DVCS (Distributed Version Control System). Selain didistribusikan , Git telah dirancang dengan mempertimbangkan Kinerja (_performance_), Keamanan (_security_), dan Fleksibilitas (_flexibility_).

#### Kinerja (_performance_)

Dengan mengusung distibusi, Git memungkinkan manfaat kinerja yang signifikan, sebagai contoh pengembang 1 membuat perubahan pada _source code_, dan menambahkan fitur 1 untuk rilis 2.0 mendatang, kemudian melakukan _commit_ (perintah Git). Dia kemudian bekerja pada fitur lainnya atau kita sebut fitur 2 dan melakukan perubahan juga. Secara alami perubahan fitur 1 dan fitur 2 disimpan secara terpisah karena sudah melakukan _commit_ sebelum pindah ke fitur 2.

Hal yang dilakukannya (_commit_) bisa dilakukan tanpa adanya jaringan dan karenanya cepat dan dapat diandalkan, ketika siap untuk mengirim semua perubahan, bisa dilakukan dengan hanya 1 perintah yaitu _push_ (perintah Git).

#### Keeamanan (_security_)

Objek didalam repositori Git seperti (_direktories_, _version_, _tags_ dan _commit_) diamankan menggunakan algoritma Hasing atau sering disebut SHA1, dengan demikian dapat melindungi seluruh objek dengan baik dan memastikan bahwa _history_ dapat dilacak sepenuhnya.

#### Fleksibilitas (_flexibility_)

Git telah dirancang untuk mendukung perancangan dan penandaan sebagai _first-class citizens_ tidak seperti SVN dan operasi yang mempengaruhi cabang (_branches) dan penandaan (_tags_) (seperti penggabungan-_merging_  atau pengembalian-_reverting_) juga disimpan sebagai bagian dari riwayat perubahan. Tidak semua VCS menampilkan tingkat pelacakan ini.

Sekian postingan mengenai Apa itu Git, semoga bermanfaat.


