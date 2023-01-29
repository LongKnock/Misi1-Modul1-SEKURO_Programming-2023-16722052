# GIT MERGE CONFLICT

Saat kita berkolaborasi menggunakan git atau tercipta banyak branch, besar kemungkinan akan terjadi merge conflict. Merge conflict terjadi ketika dua branch yang ingin dimerge memiliki perubahan pada baris yang sama. Ketika terjadi merge conflict, akan timbul pesan berikut di terminal.

<img width="724" alt="Screenshot_1" src="https://user-images.githubusercontent.com/113768772/215329514-f288f02f-3eca-4ebd-af75-96bc815cba0b.png">

Merge conflict harus diresolve secara manual menggunakan text editor/IDE. Bagian yang mengalami conflict akan diberi tanda seperti berikut.

~~~
<<<<<<< HEAD (Current Change)
<berisi baris-baris yang berubah pada branch yang aktif>
=======
<berisi baris-baris yang berubah pada branch yang ingin dimerge>
>>>>>>> (Incoming Change)
~~~

Baris-baris yang conflict tersebut harus dipilih mana yang akan dihapus dan mana yang akan diterima. Setelah selesai melakukan resolve conflict, kita baru bisa melakukan commit seperti biasa.
~~~
$ git commit
~~~