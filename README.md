###### Nama: Andico Novalino Andryanto.
###### Kelas: XII RPL 1
###### No.Absen: 15
## Modul-4
### View Blade Template
>Tugas 1 membuat view untuk project anda

1) membuat folder dan file yang akan di isi

Nama folder yang harus dibuat 
- barang
- kategori
- layout

Nama file yang harus dibuat
- home.blade.php
- index.blade.php
- app.blade.php

folder dan file-file nya menjadi satu seperti 
contoh gambar yang terlihat seperti dibawah ini

>![image](https://user-images.githubusercontent.com/91455522/183356863-ff2c5291-bde9-4c7a-a969-0e216fc32d6d.png)

>Tugas 2 membuat layout dengan master template blade untuk project anda

2) pada folder layout `file app.blade.php` kita mengambil **css dan js di bootstrap** ini linknya
[Bootstrap](https://getbootstrap.com/docs/5.2/getting-started/introduction/)

>![image](https://user-images.githubusercontent.com/91455522/183357027-9804e88c-c67f-4d6f-b141-870be4e9009a.png)
gambar diatas adalah bagian bootstrap yang kita pakai sebagai css dengan menambahkan syntax sebagai berikut

![image](https://user-images.githubusercontent.com/91455522/183357178-78806cb7-2102-4d88-ad92-0062d1264697.png)

selanjutnya bagian js dengan menambahkan syntax sebagai berikut

![image](https://user-images.githubusercontent.com/91455522/183357312-7c84b51b-be23-41c8-b32c-d6b6f45e4369.png)


Selanjutnya isi file `app.blade.php` dengan all codenya

![image](https://user-images.githubusercontent.com/91455522/183357814-78caa80c-a8d5-44a4-b9a3-950b6d0f44de.png)
saya tidak menggunakan cara yang saya jelaskan karena di bootstrap sudah ada yang mudah jadi saya tinggal copy dan paste saja

Selanjutnya folder **barang** yang berisi file `home.blade.php`

all codenya akan terlihat seperti dibawah ini karena kurang lebih saya memahami isi code dibawah
![image](https://user-images.githubusercontent.com/91455522/183357982-d27b6d78-7c27-407b-aae8-65c9532b754b.png)

Selanjutnya pada folder **kategori** file `index.blade.php` 


all codenya akan ditampilkan di bawah ini
![image](https://user-images.githubusercontent.com/91455522/183358043-86f6ee4e-331f-46f8-84b1-76cb714780a9.png)

<!-- @extends('layout.app') yang beratri mewariskan ke (folder.file) -->

<!-- @section('title') barang @endsection berarti mengelompokkan agar bisa dipanggil ke berbagai file seperti pewarisan -->

hasil dari code yang kita kerjakan akan terlihat seperti dibawah ini

code yang ditampilkan ini dari folder **barang** file `home.blade.php`

![image](https://user-images.githubusercontent.com/91455522/183358425-b64b96ae-fe99-4091-a621-6c0a434f9a97.png)
lalu hasil folder **kategori** file `index.blade.php`

![image](https://user-images.githubusercontent.com/91455522/183358498-c2107edd-5083-4038-8da0-ea0f3f2a599e.png)

