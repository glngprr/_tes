# 🚀 GIT CHEAT SHEET

## 🔧 1. Setup Awal (Sekali saja)
```bash
git config --global user.name "Nama Kamu"
git config --global user.email "[email@kamu.com](mailto:email@kamu.com)"
```
---

## 📁 2. Membuat Repo
```bash
git init
```
---

## 📌 3. Cek Status
```bash
git status
```
---

## ➕ 4. Menambahkan File (Staging)
```bash
git add .
git add nama-file
```
---

## 💾 5. Commit (Simpan Perubahan)
```bash
git commit -m "pesan commit"
```
---

## 🔗 6. Hubungkan ke GitHub
```bash
git remote add origin https://github.com/username/nama-repo.git

Cek remote:
git remote -v
```
---

## 🚀 7. Push ke GitHub
```bash
Pertama kali:
git push -u origin main

Selanjutnya:
git push
```
---

## 📥 8. Ambil Perubahan dari GitHub
```bash
git pull
```
---

## 🌿 9. Branch
```bash
Lihat branch:
git branch

Buat branch:
git branch nama-branch

Pindah branch:
git checkout nama-branch

Buat + pindah:
git checkout -b nama-branch
```
---

## 🔀 10. Merge Branch
```bash
git merge nama-branch
```
---

## 📜 11. Lihat History
```bash
git log
git log --oneline
```
---

## 🔍 12. Melihat Perubahan
```bash
git diff
```
---

## ❌ 13. Undo / Reset
```bash
Batalkan perubahan file:
git restore nama-file

Hapus dari staging:
git reset

Hapus semua perubahan (HATI-HATI):
git reset --hard
```
---

# 🧠 WORKFLOW DASAR (WAJIB PAHAM)
```bash
git init
git add .
git commit -m "pesan"
git remote add origin ...
git push -u origin main
```
---

# ⚠️ CATATAN PENTING

* git commit tidak akan bekerja tanpa git add
* git push pertama harus pakai -u
* git commit -am tidak untuk file baru
* git reset --hard bisa menghapus semua perubahan

---
