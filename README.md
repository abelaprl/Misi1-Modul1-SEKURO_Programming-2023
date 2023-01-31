# Misi1-Modul1-SEKURO_Programming-2023-19622008
Tugas Modul 1 SEKURO - Abel Apriliani 19622008

## Tentang Git dan GitHub
### Git
Secara sederhana merupakan sebuah *Version Control System* atau sebuah sistem yang dapat mengelola perubahan file di dalam folder.
>  *Version Control System* (atau disebut juga pengontrol versi atau pengontrol revisi) merupakan suatu sistem pengelolaan berbagai revisi atas perubahan dari suatu unit informasi baik berupa dokumen, kode sumber, ataupun informasi lainnya yang disimpan dalam media penyimpanan komputer.
> [Kendali Versi](https://id.wikipedia.org/wiki/Kendali_versi)

> **Manfaat *Version Control System***
> - Melacak perubahan yang terjadi pada *source code*, dokumen, dan lainnya.
> - Memungkinkan bekerja berkolaborasi dengan baik.
> - Mengetahui siapa yang melakukan dan kapan sebuah perubahan terjadi.
> - Memungkinkan kita untuk kembali ke keadaan sebelum perubahan (checkout).

**Istilah-istilah dalam Git**
- **Repository / repo** : Folder yang mengelola perubahan file sebuah software.
- **Commit** : Riwayat perubahan file disimpan menggunakan serangkaian commit.
- **Hash** : Penanda unik untuk setiap commit.
- **Branch** : Cabang pada commit agar tidak menganggu commit utama.
- **Merge** : Penggabungan dua buah branch.
- **Checkout** : Berpindah ke sebuah commit.
- **Remote** : Sumber yang memiliki repo.
- **Clone** : Mengambil repo dari remote.
- **Push** : Mengirimkan commit ke repo.
- **Pull** : Mengambil commit dari repo.

Git bisa dilakukan di komputer pribadi (lokal) dengan cara menginstall software Git.

### GitHub
Layanan cloud untuk menyimpan dan mengelola project / repo git atau sebuah website yang di dalamnya menggunakan Git.
> GitHub dan Git bisa digunakan bersamaan. *Push* mengirimkan source code / repo / project komputer ke Github, *Pull* proses diambilnya source code / repo / project ke komputer. Proses ini yang di*pull* dan di*push* adalah commit.
>> Cara *pull* dan *push* commit :
>> - Membuat GitHub menjadi *remote* atau sumber repo.
>> - Repo di*clone* ke komputer.
>> <img width="317" alt="pull push" src="https://user-images.githubusercontent.com/123937217/215650626-5f929ae7-1820-4234-96fe-5be92f49eff0.png">


## Bekerja Menggunakan GitHub
- **Membuat Repository**

Repository merupakan folder tempat menyimpan project. 
> Membuat text file sederhana
> 
> <img width="678" alt="newfile" src="https://user-images.githubusercontent.com/123937217/215648755-e4a76178-fe9f-4bfb-9f57-25e1ce621b9f.png">
> 
> *Intailize this repository with a README* digunakan untuk menjelaskan project repo yang dibuat secara otomatis di GitHub.
> Didalam repo bisa menyimpan banyak folder atau file dengan berbagai tipe seperti txt, HTML, mengupload file dari komputer, dan lainnya.
> 
> <img width="589" alt="repo rill" src="https://user-images.githubusercontent.com/123937217/215648940-53e9d90c-8c70-457c-8892-931dce6bec85.png">

- **Menyimpan Perubahan dengan Commit**

> Tambahkan judul dan keterangan pada commit.  
<img width="474" alt="commit" src="https://user-images.githubusercontent.com/123937217/215649182-58896c87-781a-48f4-838e-b423c39bd1f9.png">

> Jika terjadi perubahan, semua commit akan terdeteksi meliputi siapa yang melakukan perubahan, kapan dilakukannya perubahan tersebut. 
> <img width="942" alt="vid1 rush" src="https://user-images.githubusercontent.com/123937217/215649595-01ed1ec2-dc20-4843-b351-7d49d59660c7.png">
> Angka random yang terdapat di setiap commit pada sisi kanan atas adalah **hash** 

## Lebih Lanjut tentang Branch 
Branch merupakan cabang dari repository utama. Kode yang dimodifikasi pada branch tidak akan menimbulkan efek apapun pada repository utama. [Branch](https://idwebhost.com/blog/cari-tahu-apa-itu-github-dan-cara-menggunakannya/)

Dalam satu repo bisa dibuat beberapa branch.

### Branching atau Teknik Branch
- Membuat Git Branch
<img width="651" alt="branch" src="https://user-images.githubusercontent.com/123937217/215695779-3a7033a3-86ab-4e0f-959a-dfaba418672b.png">

- Membuat snapshot tanpa menganggu jalur utama (master branch).
<img width="449" alt="rangkuman" src="https://user-images.githubusercontent.com/123937217/215697121-e1731e47-6cc6-4bc5-bbe5-8362830d54b3.png">
<img width="613" alt="cabang lain" src="https://user-images.githubusercontent.com/123937217/215699161-426ff8e5-cb22-4c09-8a89-317a3e9d08e8.png">

- Fitur experimental 
- Dua orang mengerjakan repo yang sama.

Didalam Branch terdapat merge.

#### Merge

<img width="913" alt="gabung" src="https://user-images.githubusercontent.com/123937217/215705951-a4bb296e-55d5-4231-a572-948f3a45a8cc.png">

Merge berfungsi untuk menggabungkan commit ke jalur utama.
> **Merging**

> Menggabungkan dua buah branch.

> <img width="695" alt="compare" src="https://user-images.githubusercontent.com/123937217/215700124-edfbca9e-235d-49cc-8843-c2d1736effc9.png">

> Pull request adalah branch meminta menarik perubahan yang terjadi kepada master.

> <img width="943" alt="pull req" src="https://user-images.githubusercontent.com/123937217/215701241-5d920fb1-d26a-4886-9584-a98cf3e7b2a0.png">

> Berhasil melakukan merge.

> <img width="721" alt="yeay" src="https://user-images.githubusercontent.com/123937217/215702831-496e8327-9c1a-481f-ab8a-730551d86d75.png">




