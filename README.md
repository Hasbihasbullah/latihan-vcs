# latihan-vcs
## Belajar VCS

### Apa itu VCS


 <p>version control system (VCS) adalah sebuah kumpulan perangkat lunak yang sudah terintegrasi dan digunakan untuk membantu software engineer mengelola perubahan dalam source code dari waktu ke waktu.<p>

<p>Software dalam sistem ini mampu melacak setiap modifikasi kode dalam seluruh jenis database perusahaan. 

Jika software menemukan kesalahan, engineer dapat membandingkan kode dari versi sebelumnya dan mulai memperbaiki kekeliruan tersebut.<p>

#### GIT adalah ?

<p>it merupakan software berbasis Version Control System (VCS) yang bertugas untuk mencatat perubahan seluruh file atau repository suatu project. Developer software biasa menggunakan Git untuk distributed revision (VCS terdistribusi), hal ini bertujuan untuk menyimpan database tidak hanya ke satu tempat. Namun semua orang yang terlibat dalam penyusunan kode dapat menyimpan database ini.

Prosedur yang diterapkan ini dapat membantu antar divisi project untuk memantau dan menghubungkan (merge) antar ekstensi yang berbeda dengan mudah. Sehingga aplikasi yang dibuat oleh sebuah tim project dapat berfungsi tanpa menghubungkan secara manual.<p>

Ini adalah tampilannya
![Gambar1](screenshoot/ss1.png)
![image](https://user-images.githubusercontent.com/92858927/138169879-70eccb55-57a5-40d8-8e37-6d9e35b6ec09.png)

<P>  1. Buka github.com lalu create new repository dengan nama "Latihan VCS" dengan settingan publik dan add README file<P>
![image](https://user-images.githubusercontent.com/92858927/138169951-2c9a3b85-bf5c-43af-b5f3-61a65f2b8e40.png)


<P>   2. Lalu buka Git Bash<p>
<P>   3. Karena kita ingin membuat repositorynya pada date C, maka ketik cd /c/ lalu git clone dan paste link repositorynya, maka akan muncul seperti ini<P>
![image](https://user-images.githubusercontent.com/92858927/138170067-44a15b60-5511-4714-9546-9f1738d89b91.png)

<P>   4. Lalu buka file readme tersebut, dan isi sesuai keinginan.
<P>   5. Setelah itu kembali lagi ke git, ketik git status untuk melihat statusb git pada saat itu. Karena kita telah merubah isi readme nya, maka kita ketik git add 'README.md' lalu ketik git commit -m 'Perubahan Pada Readme' dan ketik git push -u origin main untuk menambahkan pembaruan readme tersebut dalam repository github. <p>
 ![image](https://user-images.githubusercontent.com/92858927/138170131-9c78d9a1-edb8-47dd-9336-f6ea5029a4ab.png)

<p>   6. Jika ingin menampilkan Gambar pada repository, maka terlebih dahulu buat folder baru lalu isi gambarnya dalam folder tersebut. lalu kembali ke github ketik git add 'Gambar' lalu ketik git commit -m 'Menambah folder gambar' dan ketik git push -u origin main untuk menambahkan folder tersebut ke dalam repository. <p>
<p>   7. SELESAI- <p>



