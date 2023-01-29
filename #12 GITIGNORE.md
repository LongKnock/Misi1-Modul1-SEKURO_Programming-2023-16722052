# GITIGNORE

.gitignore adalah sebuah file yang bisa kita simpan di dalam repository git agar git bisa mengabaikan beberapa file yang termuat dalam file .gitignore. Hal ini bertujuan ketika kita tidak ingin membawa/commit beberapa file yang dapat berupa file sistem, dan masih banyak lagi.

Untuk membuat file gitignore itu cukup mudah, hanya perlu membuat file bernama .gitignore lalu mengedit isinya, salah satu caranya menggunakan text editor.

Beberapa cara menulis file dalam .gitignore
1. <nama_file>.<ekstensi_file>  
Mengabaikan file spesifik.
2. <nama_folder>/  
Mengabaikan folder beserta isinya.
3. *.<ekstensi_file>  
Mengabaikan seluruh file dengan ekstensi tersebut.

Kita juga bisa mengunjungi https://gitignore.io untuk otomatis membuat file gitignore yang sesuai dengan proyek yang sedang kita kerjakan.