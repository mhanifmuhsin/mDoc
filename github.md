---
layout: page
title: Github Guide
permalink: /github/
---

Logout akun diterminal
```
git config --global --unset user.name
git config --global --unset user.email
git config --global --unset credential.helper
```

Remove SSH Keys
```
~/.ssh
```

Setup git
```
git init
git add README.md
git remote add origin [https://github.com/mhanifmuhsin/mDoc.git]
git add . 
git commit -m ["description"] 
git push -u origin [master]

keterangan : hapus kurung siku
```

Checkout dan membuat branch baru
```
git checkout -b [master]

keterangan : hapus kurung siku
```

Checkout (pindah branch)
```
git checkout [gh-pages]

keterangan : hapus kurung siku
```

Cara mengecek branch

```
git branch
```

Merge
```
git merge [nama branch yang mau digabungkan]

keterangan : hapus kurung siku
```

Berpindah remote URLs dari HTTPS ke SSH
```
$ git remote -v
# Melihat List remote yang ada
> origin  https://github.com/USERNAME/REPOSITORY.git (fetch)
> origin  https://github.com/USERNAME/REPOSITORY.git (push)

# Merubah remote
$ git remote set-url origin git@github.com:USERNAME/REPOSITORY.git

#Verifikasi ulang, perubahan remote
$ git remote -v
> origin  git@github.com:USERNAME/REPOSITORY.git (fetch)
> origin  git@github.com:USERNAME/REPOSITORY.git (push)

```

Berpindah remote URLs dari SSH ke HTTPS
```
$ git remote -v
# Melihat List remote yang ada
> origin  git@github.com:USERNAME/REPOSITORY.git (fetch)
> origin  git@github.com:USERNAME/REPOSITORY.git (push)

# Merubah remote
$ git remote set-url origin https://github.com/USERNAME/REPOSITORY.git

#Verifikasi ulang, perubahan remote
$ git remote -v
> origin  https://github.com/USERNAME/REPOSITORY.git (fetch)
> origin  https://github.com/USERNAME/REPOSITORY.git (push)

```





















