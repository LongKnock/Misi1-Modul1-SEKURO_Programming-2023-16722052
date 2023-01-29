# APA ITU GIT & GITHUB?

## APA ITU GIT?

Git merupakan salah satu dari VCS (Version Control System). Version Control System, disebut juga revision control system atau source code management adalah system yang mengelola perubahan dari sebuah dokumen, program komputer, website, dan kumpulan informasi lain.

Kegunaan VCS:  
1. Melacak versi atau riwayat dari suatu perubahan
2. Mempermudah kolaborasi
3. Membagikan file yang ingin dibagikan ke orang lain

Definisi VCS:
- Sebuah sistem yang menyimpan rekaman/snapshot perubahan pada source code
- Memungkinkan bekerja berkolaborasi dengan lebih baik
- Mengetahui siapa yang melakukan dan kapan sebuah perubahan terjadi
- Memungkinkan kita untuk kembali ke keadaan sebelum perubahan (**checkout**)

Jadi, git adalah sebuah software untuk mengelola perubahan file di dalam folder (**repository**/repo). Git menyimpan semua riwayat perubahan file menggunakan serangkaian **commit**. Setiap commit memiliki penanda unik yang disebut **hash**.

Dari suatu commit, kita bisa membuat cabang yang tidak mengganggu jalur commit utamanya atau saat kolaborasi, hal tersebut disebut **branch**. Saat fitur dari kedua branch ingin digabungkan, hal ini disebut **merge**.  


## APA ITU GITHUB?

GitHub adalah layanan cloud untuk menyimpan & mengelola project/repo git. GitHub dapat melakukan apapun yang bisa dilakukan dengan git di komputer. Hanya saja, GitHub melakukannya secara online melalui internet.


## GIT & GITHUB

Jika kita menginstall git di komputer dan memiliki akun GitHub, kita akan mulai memanfaatkan fungsi keduanya secara bersamaan. Kita bisa mengirim source code/project/repo ke GitHub (**push**) dan mengambil source code/project/repo dari GitHub ke komputer (**pull**). 

Syarat kita bisa mengombinasikan antara GitHub dengan git adalah memiliki **remote** repository di GitHub yang di**clone** ke komputer (local repository).