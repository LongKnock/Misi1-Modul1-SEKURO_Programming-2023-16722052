# GIT BRANCH & MERGE

## Implementasi Branch

Setiap commit, pasti mengandung identifikasi berupa hash, username, email, beserta time stamp. Selain itu, commit ini juga terhubung dengan branch atau commit ini pasti dimiliki suatu branch.

Untuk mengetahui branch mana yang aktif, Git memiliki sesuatu yang disebut **head**, sebagai pointer yang mengarah ke branch yang aktif. Secara default, head mengarah ke branch master/main yang merupakan jalur utama default dari suatu proyek.

Saat kita telah membuat branch lalu pindah ke branch tersebut, maka head akan mengarah ke branch yang kita maksudkan. Setelah selesai dengan pekerjaan di branch tersebut dan bermaksud memasukkannya ke jalur utama, kita bisa melakukan merge branch.

## Merge

### Fast Forward

Fast Forward terjadi ketika branch berada dalam jalur langsung atau direct path.

### Three-way Merge

Ketika kedua branch tidak berada dalam jalur langsung, maka merge yang terjadi berlangsung dalam jenis Three-way merge. Merge ini memerlukan commit sehingga bisa juga disebut merge commit.

## Common Command

### Membuat branch

~~~
$ git branch <nama_branch>
~~~

### Melihat branch yang tersedia

~~~
$ git branch
~~~

### Pindah branch

~~~
$ git checkout <nama_branch>
~~~

### Menghapus branch  

~~~
$ git branch -d <nama_branch>
~~~

### Merge branch

~~~
$ git merge <nama_branch>
~~~

### Melihat graph

~~~
$ git log --all --decoreate --oneline --graph
~~~

## Contoh

Membuat branch

<img width="664" alt="Screenshot_1" src="https://user-images.githubusercontent.com/113768772/215325338-742c49f5-17ee-4b12-abf3-9976ce03dbcd.png">

Setelah itu, kita bisa mengubah isi dari branch baru. Ketika sudah selesai, kita bisa langsung saja merge branch baru ke jalur utama dan menghapus branch tersebut.  

<img width="664" alt="Screenshot_1" src="https://user-images.githubusercontent.com/113768772/215327624-36947cb8-c3b2-4e1f-b802-b6de7889b822.png">
