```html
1. git clean menghapus semua file yang tidak terlacak (untracked) atau file yang belum masuk ke stage
2. -f atau -force berguna untuk menghapus file untracked secara paksa
Opsi -d memberi tahu git clean bahwa Anda juga ingin menghapus direktori yang tidak terlacak, secara default ia akan mengabaikan direktori.
3. git branch [branch name]
4. pada fast-forward, riwayat hanya satu garis lurus,setelah melakukan percabangan dan membuat beberapa commit, tidak ada commit baru pada master. sedangkan recursive merge, setelah melakukan peracabangan dan membuat beberapa commit, ada beberapa commit baru di 'master'. Jadi, ketika sedang merge, git akan "rekursif" di atas cabang dan membuat commit gabungan baru. sehingga commit akhirnya memiliki dua parents.
5. git checkout [branch name]
6. git rm [file name]
7. git branch -d [branch name]
8. git diff berguna untuk melihat dan membandingkan perubahan apa saja yang telah dilakukan
9. git reset HEAD [file name]
10. Merge conflict dapat terjadi ketika menggabungkan branch, rebasing branch, atau commit. Jika Git mendeteksi konflik, itu akan menyorot area yang berkonflik dan menanyakan kode mana yang ingin disimpan.
```