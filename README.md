# Keuangan1_3

Pastikan Python sudah terinstal, lalu instal Django menggunakan pip:
<br>
> pip install django

Pastikan pustaka html ke pdf sudah terpasang di program python anda
<br>
> pip install xhtml2pdf

xhtml2pdf sudah include beberapa dependency, seperti Pillow dan reportlab. Pastikan dependency tersebut sudah terinstal.
<br>
> pip install pillow reportlab

Kemudian akses folder projek dengan command line sampai menemukan file yang bernama "manage", lalu jalankan perintah: 
<br>
> python manage.py runserver

Akses urls Web
* Panel admin: http://127.0.0.1:8000/admin/
* Tampilan transaksi: http://127.0.0.1:8000/transaksi/
* Tampilan add transaksi tanpa perantara admin: http://127.0.0.1:8000/transaksi/tambah/
* Ekspor CSV: http://127.0.0.1:8000/transaksi/ekspor-csv/
* Backup Data: http://127.0.0.1:8000/transaksi/backup/
* Restore Data: http://127.0.0.1:8000/transaksi/restore/
* Halaman Laporan Keuangan: http://127.0.0.1:8000/transaksi/laporan/
* Cetak PDF hasil Laporan Keuangan: http://127.0.0.1:8000/transaksi/laporan/pdf/

<br>
username: admin
<br>
password: admin

# Fitur
Fitur Tambahan (Opsional)
<br>
1. Membuat tampilan lebih menarik dengan bantuan framework Bootstrap
2. Menambahkan fitur "delete" transaksi pada tampilan utama halaman transaksi

# Tampilan

![Sample Image](https://github.com/krisnasuma/keuangan1_3/blob/main/View1.PNG)

![Sample Image](https://github.com/krisnasuma/keuangan1_3/blob/main/View2.PNG)

![Sample Image](https://github.com/krisnasuma/keuangan1_3/blob/main/View3.PNG)

![Sample Image](https://github.com/krisnasuma/keuangan1_3/blob/main/View4.PNG)


# Versi Sebelumnya
* V0: https://github.com/krisnasuma/keuangan/
* V1: https://github.com/krisnasuma/keuangan1
* V1_1: https://github.com/krisnasuma/keuangan1_1
* V1_2: https://github.com/krisnasuma/keuangan1_2
