#SIA (Sistem Informasi Akademik)
---
![image](https://dl.dropboxusercontent.com/u/83059892/SIA/beranda.png)

### Tentang SIA

SIA merupakan proyek bersama yang digagas oleh `Django Indonesia` *([Facebook Group](https://www.facebook.com/groups/739647266049228/))*
dengan tujuan sebagai:

1. Tempat *sharing* pengetahuan sekitar pemrograman **Python Django** dan mengembangkan kemampuan dalam membuat Aplikasi Web baik secara teori maupun praktek
2. Membuat aplikasi yang dapat digunakan secara nyata dan berguna pada **Instansi Akademis** (Sekolah)


### Coding-Style

Untuk *Coding-Style* kita mengikuti acuan pada dokumentasi *Coding-Style* **Django** yang bisa ditemukan pada URL [https://docs.djangoproject.com/en/dev/internals/contributing/writing-code/coding-style/](https://docs.djangoproject.com/en/dev/internals/contributing/writing-code/coding-style/)

### Pengetahuan Dasar

Beberapa pengetahuan dasar yang dibutuhkan untuk mengembangkan Aplikasi Web berbasis **Python Django**

1. Dasar Bahasa Pemrograman Python  
   (Pembelajaran: [http://www.learnpython.org](http://www.learnpython.org/))
2. Menggunakan Django  
   (Pembelajaran: [http://realdjango.herokuapp.com/](http://realdjango.herokuapp.com/))


# Menginstall SIA
---
### Lingkungan Development
**Requirement**

1. Django 1.6.2  
   
2. South  
          
3. Django Suit  

4. Psycopg2
   


# Install semua paket yang dibutuhkan
---

> pip install -r requirements.txt





**Install SIA**

`git clone https://github.com/django-developer-indonesia/sia.git`

**Setup**

`./manage.py syncdb`

**Menjalankan SIA**

`./manage.py runserver`



# Struktur SIA
---
### Data Model
##### Entitas

1. Siswa
2. Guru
3. Pelajaran
4. Kelas
5. Jadwal
6. Jurusan
7. Jenis Agenda
8. Kalender Akademik

##### ERD
`draft version`
![image](https://dl.dropboxusercontent.com/u/83059892/SIA/SIA-ERD.png)

[Unduh ERD](https://dl.dropboxusercontent.com/u/83059892/SIA/SIA-ERD.vdx) *(format: Microsoft Visio)*

[Refensi Simbol ERD](https://dl.dropboxusercontent.com/u/83059892/SIA/referensi-membaca-ERD.png)
