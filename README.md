# Catatan Github Dan Git

Catatan ini saya buat berdasasrkan pemahaman saya saja atau tepatnya catatan mungkin yang mengerti hanya saya saja dan dibuat untuk catatan jika sewaktu waktu saya lupa dasar-dasar dari Github dan Git jadi bisa buka langsung ini catatan 

----




Github
------
**1. Edit (commit)**
 - masuk repository
 - kemudian klik tombol edit
 - kemudian klik tombol commit change + keterangannya

**2. cek history yang kita ubah**
 - bisa dihistory atau di insights

**3. Branch**
 - merubah repo tanpa merubah jalur masternya (master branch)
 - dalam satu repo bisa membuat beberapa branch
 - bisa digunakan untuk membuat fitur yang belum fix / yang bekerja dengan repo yang sama
 
**4. Merge**
 - menggabungkan commit dari branch kembali ke master branch nya
 - 

**5. Fork**
 - untuk menduplikat repo orang lain ke github kita
 - jika menambahkan sesuatu di repo hasil fork maka bisa di pull ke repo aslitnya (yang punya repo aslinya)
 - klik "New Pull Request" untuk pull ke repo aslinya siapa tau di merger atau di gabungkan sama yang punya nya

----



Git
----
**1. Commit**
 - git add . (jika status belum modifield)
 - git commit -m "create commit"
 - git status (mengecek file yang dirubah)
 
**2. Branch**
 - git branch <nama branch>
 - git branch use <nama branch> mengganti branch
 - menghapus bracnh = git branch -d <namadosen>
 
**3. Pull**
 - git pull <link https>
 
**4. Push**
 - git remote add <namaremote> <link https>
 - harus di git add . 
 - kemudian di git commit -m "<keterangan>"
 - kemudian git branch -M Main
 - kemudian git push -u <nama remote> main
 
**5. membuat graph log**
 - git log --all --decorate --oneline --graph
 - membuat alias git = git config --global alias.graph 'log --all --decorate --oneline --graph'
 - menampilkan graphic = git graph
 
**6. Merge**
 - git merge
 - kemudian fit merge <namabranch>
 - 

**7. clone**
 - git clone <link>
 - menggabungkan commit dari branch kembali ke master branch nya
