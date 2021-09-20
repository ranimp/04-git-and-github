```html
1. mkdir rani
2. cd rani
   touch README.md
   // isi dengan "halo perkenalkan aku halaman utama"
3. git init .
   git commit -m "inisialisasi git repository"
4. git branch cv
5. git checkout cv
   vim cv.txt
   // isi dengan "ini adalah file cv"
6. git add cv.txt
   git commit -m "inisialisasi CV"
7. vim cv.txt
   // isi dengan "gojek"
   git add cv.txt
   git commit -m "menambahkan perusahaan pertama"
   vim cv.txt
   // isi dengan "google"
   git add cv.txt
   git commit -m "menambahkan perusahaan kedua"
   vim cv.txt
   // isi dengan "shopee"
   git add cv.txt
   git commit -m "menambahkan perusahaan ketiga"
8. git checkout master
9. vim README.md
   // tambahkan "ini adalah update pertama branch master"
   git add README.md
   git commit -m "update master pertama"
10. git merge cv
11. gitu push -u origin master

```
![result](gbr.png)