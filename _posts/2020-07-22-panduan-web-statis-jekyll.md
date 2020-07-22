---
layout: post
title:  "Panduan web statis Jekyll"
date:   2020-07-22 16:14:00 +0700
categories: jekyll update
---

**Membuat website static jekyll**
1. Pastikan jekyll sudah terinstall
2. Buat folder dimana jekyll akan disimpan
3. Masuk ke folder tersebut melalui terminal
4. Ketik perintah dibawah ini untuk membuat web-static jekyll :

```
jekyll new [nama-web]

Keterangan : Hapus kurung siku
```

**Menjalankan server**
1. Masuk ke folder jekyll(website yang dibuat)
2. Jalankan server dengan perintah :

```
jekyll serve
```

**Membuat Draft**

1. Buat folder ***_draft***
2. Buat file dalam folder itu, seperti kita membuat post
3. Jalankan server dengan perintah :

```
jekyll server --watch --drafts
```

**Membuat Post**
1. Buat file dalam folder ***_post***
2. Setting layout default dan save file seperti :

```
Setting layout

e.g
---
layout : page
title : [isikan sesuai title]
---


Save file

yyyy-mm-dd-[nama]-[file].markdown

e.g
2020-07-13-welcome-to-jekyll.markdown

Keterangan : Hapus kurung siku
```