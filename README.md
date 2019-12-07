# Praktikum-5

**soal**
**Buat program sederhana yang akan menampilkan daftar nilai mahasiswa, dengan ketentuan 
• Program dibuat dengan menggunakan Dictionary 
• Tampilkan menu pilihan: (Tambah Data, Ubah Data, Hapus Data, Tampilkan Data, Cari Data)
• Nilai Akhir diambil dari perhitungan 3 komponen nilai (tugas: 30%, uts: 35%, uas: 35%) 
• Buat flowchart dan penjelasan programnya pada README.md. 
• Commit dan push repository ke github.**

**Langkah-Langkah**

1.Buat data kosong untuk memudahkan menambah data dictionary pada setiap statement

2.Kemudian input data yang berisi toolbar menu( Tambah,Ubah , Lihat,Keluar)

3.Buat statement dalam setiap menu tadi menggunakan _perulangan if_ 

4.Untuk menu _Tambah_ dapat menginputkan / memasukkan data baru 
![Screenshot (86)](https://user-images.githubusercontent.com/57002531/70381500-ed3c9b80-197d-11ea-8701-248bbe82ab1e.png)
5.Maka output akan menghasilkan seperti ini
![Screenshot (81)](https://user-images.githubusercontent.com/57002531/70381518-2aa12900-197e-11ea-94b2-89c15c1e0678.png)
6.Untuk melihat list yang kita buat maka gunakan perulangan _if_ dan untuk outputnya gunakan _.format_ seperti pada gambar berikut
![Screenshot (86)](https://user-images.githubusercontent.com/57002531/70381550-c03cb880-197e-11ea-83e0-4fb04d1b9b17.png)
dan akan keluar seperti ini
![Screenshot (81)](https://user-images.githubusercontent.com/57002531/70381557-d480b580-197e-11ea-8461-8a7c71937dee.png)
7._If_ apabila menunya keluar maka program tsb akan selesai
![Screenshot (86)](https://user-images.githubusercontent.com/57002531/70381563-0265fa00-197f-11ea-88d7-6ca8468b967e.png)
hasilnya
![Screenshot (85)](https://user-images.githubusercontent.com/57002531/70381572-275a6d00-197f-11ea-8ec6-893ebfd78303.png)
8._if_ menu _H)apus_ untuk menghapus data maka gunakan _if nim in data.keys():_
![Screenshot (80)](https://user-images.githubusercontent.com/57002531/70381590-891ad700-197f-11ea-8079-3a8526febb83.png)
Maka ouputnya akan keluar seperti ini
![Screenshot (83)](https://user-images.githubusercontent.com/57002531/70381596-a354b500-197f-11ea-8515-e1686af976d2.png)
9._if_ menu _C)ari_ untuk mencari suatu data,gunakan _else_ apabila data yang di cari tidak ada dengan mengouputkan _("Data tidak ada")_
![Screenshot (80)](https://user-images.githubusercontent.com/57002531/70381611-e747ba00-197f-11ea-8d9a-59a1c8a07dee.png)
outputnya akan menghasilkan
![Screenshot (82)](https://user-images.githubusercontent.com/57002531/70381612-f29ae580-197f-11ea-8bcc-c23e5ab4e876.png)
10._if_ menu _E)dit_ untuk mengedit foto atau mengubah data sesuai kebutuhan
![Screenshot (80)](https://user-images.githubusercontent.com/57002531/70381621-20802a00-1980-11ea-84d7-f69e31604eb9.png)
Setelah di ubah kita bisa ke menu _L)ihat_ karena tidak di tampilkan otomatis
![Screenshot (84)](https://user-images.githubusercontent.com/57002531/70381634-41e11600-1980-11ea-9343-53d3043b1c24.png)
11.Gunakan _else_ apabila menu yang di inginkan tidak ada dengan mengoutputkan _("pilih menu lainnya")_
