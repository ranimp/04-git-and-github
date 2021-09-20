```html
1. git reset adalah kondisi dimana ketika kita ingin kembali ke commit sebelumnya dan commit setelahnya akan terhapus, git reset biasanya digunakan ketia ingin menghapus commit yang sudah ada dan kembali ke commit tujuan.
sedangkan
git revert adalah kondisi dimana ketika kita kembali ke commit sebelumnya, kita hanya mundur dan tidak menyebabkan commit setelahnya ikut terhapus, git revert biasanya digunakan kita ingin kembali ke commit sebelumnya dan ingin melakukan perubahan tanpa menghapus commit yang sudah ada sehingga akan membuat semacam cabang baru.
2. merge mempertahankan riwayat lengkap file, termasuk urutan kronologis, sedangkan rebase membuat commit yang bersih dan hanya relevan dengan file yang ada di branch. 
3. git stash pop membuang simpanan (paling atas, secara default), sedangkan git stash apply menaruhnya di daftar simpanan untuk kemungkinan digunakan kembali nanti.
4. Rebasing interaktif dapat digunakan untuk mengubah commit dalam banyak cara seperti mengedit, menghapus, dan squashing. Untuk memberi tahu Git di mana memulai rebase interaktif, gunakan SHA-1 atau indeks commit yang segera mendahului commit yang ingin dimodifikasi.
```