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

## Fork
Fungsi Fork atau Forking adalah sebagai berikut.
- Membuat 'copy / duplikat' dari repo orang lain (beserta history-nya).
- Jembatan antara repo original dan duplikatnya.
- Modifikasi terhadap repo original.
> Contoh saat melakukan fork pada repo akun orang lain adalah sebagai berikut.

<img width="956" alt="fork2" src="https://user-images.githubusercontent.com/123937217/216068306-53a2b45b-2464-48f9-adcc-b35b545c952f.png">

- Berkontribusi pada repo orang lain.
> Bisa mengusulkan perubahan repo orang lain dan dikembalikan pada pemilik repo asli atau melakukan pull request pada pemilik aslinya.

<img width="782" alt="frok3" src="https://user-images.githubusercontent.com/123937217/216068033-bb5c55d2-7c7c-4dda-b891-a030699c9b97.png">

<img width="926" alt="fork4" src="https://user-images.githubusercontent.com/123937217/216067659-cc8b313f-2b15-44d2-a1af-9f4c9b1a17ba.png">

<img width="950" alt="fork5" src="https://user-images.githubusercontent.com/123937217/216069098-7e16e8a3-7029-4183-a9e9-f607717d3488.png">

> Contributor akan bertambah saat kita berhasil melakukan fork.

- Fork tidak sama dengan Clone.

## Bekerja Menggunakan Git
Implementasi Software Git di komputer lokal.

### Install Git (Windows)
Intall Git menggunakan website [Install Git](https://git-scm.com/download/win) sesuai sistem operasi komputer.

<img width="385" alt="instalgit" src="https://user-images.githubusercontent.com/123937217/216368676-2c9492be-9fbc-49f4-877c-3ecb52c74e99.png">

Git Bash bisa dibuka di Commad Promt atau di Git Bash yang diberi secara otomatis saat menginstall Git.

<img width="706" alt="help" src="https://user-images.githubusercontent.com/123937217/216369736-5fb2e96d-a853-4ec5-b6c9-6b8d9c0f0bd4.png">

### Git Command (lokal)
- $ git init : menginisialiasi repo Git yang dimiliki user.
> <img width="500" alt="init" src="https://user-images.githubusercontent.com/123937217/216377993-b54d11d3-aee5-4a1d-8035-03deca8c04b0.png">

> otomatis folder berubah menjadi repo Git dengan Branch master.
- $ git add <file(s)> : menambahkan file kedalam *staging area*
> <img width="488" alt="commit berhasil" src="https://user-images.githubusercontent.com/123937217/216382584-e85ba2c0-7443-4d99-bf5c-827b3c0072a0.png">

- $ git status : mengetahui status repo.
> <img width="509" alt="gitstatus" src="https://user-images.githubusercontent.com/123937217/216381615-7386073e-8589-459e-9c41-9a19a6ef9485.png">

- $ git config : memasukan konfigurasi ke dalam Git.
> <img width="477" alt="config" src="https://user-images.githubusercontent.com/123937217/216383902-f8ab081e-114e-488e-a450-935f80363d8b.png">

- $ git commit : melakukan commit.
> <img width="496" alt="git comti" src="https://user-images.githubusercontent.com/123937217/216384131-22110a55-e0f0-4be7-97ac-0bcdd4ccbe49.png">
> Kemudian git akan membuka kode editor default secara otomatis.

><img width="479" alt="1" src="https://user-images.githubusercontent.com/123937217/216385451-1273f0fe-9077-47cc-b9e6-7956a6f132d5.png">

> Memasukkan pesan atau detail pada commit.

- $ git branch : membuat branch.
- $ git help : mengetahui sebuah perintah dengan cepat.

### Tiga Area Pada Repo Git
1. Working tree : folder berisi file-file project yang dikerjakan.
> Menggunakan comment git add : jika terjadi perubahan, simpan perubahan ke dalam staging area.
2. Staging area : memberitahu Git bahwa sudah terjadi perubahan.
> Menggunakan git commit : staging ke history.
3. History : perubahan yang dicommit akan masuk ke history.
<img width="403" alt="gitlog" src="https://user-images.githubusercontent.com/123937217/216412704-b25d2110-b46f-46da-aaba-e7789691ee1c.png">

> branch **master** merupakan commit yang aktif, **head** menunjuk pada branch tersebut.

> Pada nomor 2 dan 3, repo akan tersimpan di folder .git secara otomatis.

## Git Branch & Merge
### Implementasi Branch
- Menambahkan fitur baru pada commit (membuat branch).
> $ git branch <nama_branch>

<img width="411" alt="git bran" src="https://user-images.githubusercontent.com/123937217/216416653-08bfeb3f-f6fd-48ce-810a-e160b8eadd66.png">

- Melihat perjalanan branch
> Menampilkan visualisasi branch dalam bentuk graph.
>> Untuk menampilkan visualisasi branch gunakan $ 'git log --all --decorate --oneline --graph'

> Membuat nama lain / alias untuk mempermudah
>> Untuk membuat nama alias gunakan $ 'alias <nama_alias>= "git log --all --decorate --oneline --graph"'

<img width="361" alt="Screenshot 2023-02-03 014405" src="https://user-images.githubusercontent.com/123937217/216419515-606f5658-f8e6-420a-86fe-8c649100dec4.png">

> Berpindah Branch
>> untuk berpindah ke branch lain gunakan $ 'git checkout <nama_branch>'

<img width="361" alt="Screenshot 2023-02-03 014405" src="https://user-images.githubusercontent.com/123937217/216422077-602d088b-b137-42e3-a443-fe93ee8758bc.png">

<img width="350" alt="gr" src="https://user-images.githubusercontent.com/123937217/216422507-ca87a97a-6326-4af1-a7ca-ead09e596eb6.png">

### Merge
Menggabungkan Branch

**Dua Jenis Merge**
- Fast Forward
Branch yang diinginkan berada di jalur langsung. 

<img width="336" alt="Screenshot 2023-02-03 021136" src="https://user-images.githubusercontent.com/123937217/216425667-7a37d1a3-4305-4faf-9e74-ed5dba433403.png">

> Menghapus Branch

> Untuk menghapus branch gunakan $ 'git branch -d <nama_branch>'

<img width="370" alt="Screenshot 2023-02-03 021641" src="https://user-images.githubusercontent.com/123937217/216427179-d0569d0b-8388-428a-9d86-b2150ce9c397.png">

- Three-way Merge
Branch yang tidak ada *direct path*.

<img width="346" alt="Screenshot 2023-02-03 022528" src="https://user-images.githubusercontent.com/123937217/216429145-0cb5b0ed-e0e1-433c-ae46-2e8c51b0b565.png">

## Git Merge Conflict
Hal ini bisa terjadi akibat dua branch melakukan baris yang sama dalam satu repo sehingga git tidak bisa melakukan merge secara otomatis.

Contoh implementasinya adalah sebagai berikut
- Menambah branch baru
<img width="453" alt="Screenshot 2023-02-03 085607" src="https://user-images.githubusercontent.com/123937217/216494218-6d918a95-a69f-4fb6-adb1-d689008d401c.png">

- Ada dua commit Three-way Merge, akan melakukan merge untuk digabungkan


<img width="386" alt="Screenshot 2023-02-03 090429" src="https://user-images.githubusercontent.com/123937217/216494612-6b89f93c-3d29-4717-859e-8e60d88ae01e.png">

<img width="392" alt="Screenshot 2023-02-03 090455" src="https://user-images.githubusercontent.com/123937217/216494634-f55dc19b-0843-4941-9cab-c3075250bd67.png">

**Terjadi konflik pada merge

>> Terdapat dua hal yang berubah, lalu memutuskan akan menggunakan yang akan digunakan.

<img width="464" alt="Screenshot 2023-02-03 090526" src="https://user-images.githubusercontent.com/123937217/216495175-a771d0b7-e754-4cb0-a4c6-4c61783cd5ed.png">

>> Hijau : perubahan pada branch aktif

>> Biru : data yang berubah pada branch yang digabungkan

> Merge belum selesai, lakukan merge pada branch yang conflict

<img width="347" alt="Screenshot 2023-02-03 092623" src="https://user-images.githubusercontent.com/123937217/216497076-84c293c6-5e69-496e-874f-4fd3ed20ef03.png">

>> Merge sudah selesai



 
