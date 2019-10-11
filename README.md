# latihan1

## Pengertian VCS
Version Control System merupakan sebuah sistem yang merekam perubahan dari sebuah berkas atau sekumpulan berkas dari waktu ke waktu,
sehingga anda dapat melihat kembali setiap perubahanya.

## Langkah-langkah menggunakan GIT
1.Buka software “Git Bash”

2.Masuk ke penyimpanan file yang akan dibuat misal akan dibuat di direktori D dengan command "cd /d”

3.Buat file terlebih dahulu dengan command "mkdir Latihan1"

4.Lalu masuk ke dalam file yg telah dibuat dengan command "cd /d/Latihan1"

5.Lalu command “git init”. Git init untuk meng-set folder yang digunakan tersebut sebagai repo local git. Bisa di bilang ini instalasi git pertama kali,akan terlihat seperti ini: /d/latihan1 (master)

6.Lalu buat file README.md dengan command “echo “# Latihan1” > README.md

7.Setelah itu isi file README.md dengan tugas yang sudah diberikan dengan command “nano README.md”

8.Langkah selanjutnya adalah mengkomit file dengan command “git commit -m “isi commit”. Git commit untuk menambahk keterangan/status perubahaan saat upload ke repo online.

9.Lalu meremot repositori yang sudah dibuat di github dengan command “git remote add origin https://github.com/rickyrusandi/Latihan1.git (bisa diganti link repositori anda sendiri”.

10.Lalu upload file README.md ke repositori online dengan command “git push -u origin master”

11.Kemudian command “git pull origin master”. Git pull untuk mengambil commit terbaru lalu otomatis menggaubungkan (merge) dengan branch yang aktif.

12.Terakhir mengecek file yang README.md yang sudah diupload dengan command “ll”

