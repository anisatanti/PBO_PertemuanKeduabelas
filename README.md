# **Tugas PBO TM 12 (Persistence)**
___
## **Daftar Isi**
- [Koneksi](https://github.com/anisatanti/PBO_PertemuanKeduabelas/blob/main/KoneksiDB.java)
- [Matakuliah.java](https://github.com/anisatanti/PBO_PertemuanKeduabelas/blob/main/Matakuliah.java)
- [Persistence.xml](https://github.com/anisatanti/PBO_PertemuanKeduabelas/blob/main/persistence.xml)
- [FrameMataKuliah.java](https://github.com/anisatanti/PBO_PertemuanKeduabelas/blob/main/FrameMataKuliah.java)
- [FrameMataKuliah.form](https://github.com/anisatanti/PBO_PertemuanKeduabelas/blob/main/FrameMataKuliah.form)
- [reportmatakuliah.jasper](https://github.com/anisatanti/PBO_PertemuanKeduabelas/blob/main/reportmatakuliah.jasper)
- [reportmatakuliah.jrxml](https://github.com/anisatanti/PBO_PertemuanKeduabelas/blob/main/reportmatakuliah.jrxml)
- [matkul.csv](https://github.com/anisatanti/PBO_PertemuanKeduabelas/blob/main/matkul.csv)

___
## **_Deskripsi:_**

Proyek ini merupakan Tugas Pertemuan Keduabelas Mata Kuliah Pemrograman Berorientasi Objek. Membuat Aplikasi CRUD pada Netbeans Java yang terhubung dengan Aplikasi basis data PostgreSQL menggunakan Persistence yakni membuat code CRUD tanpa menggunakan perintah sql di setiap button Gui nya
___
## **Berikut Langkah-langkahnya:**

1.	Buat project baru dengan nama PBO_Persistence kemudian unchecklist pada Create Main Class kemudian klik Finish.

    ![image](https://github.com/user-attachments/assets/cd823d4d-1549-4f8a-887a-171e474a5aa3)

2.	Buat Package dengan nama TM12. Klik kanan package TM12 kemudian klik New, klik Entity Classes from Database.

    ![image](https://github.com/user-attachments/assets/39844508-0d82-4698-a71e-d2f94572ca47)

3.	Pilih Database yang akan digunakan pada Database Connection.

    ![image](https://github.com/user-attachments/assets/2c9c8e1a-1501-482a-bc1a-c9e1419b7ad3)

4.	Pada Available Tables, pindahkan tabel kesebelah kanan (Selected Tables) dengan klik Add All>>

    ![image](https://github.com/user-attachments/assets/f77a8ff8-797d-415f-85d1-2201a31d9307)

    Setelah berhasil dipindah ke sebelah kanan klik Next.

    ![image](https://github.com/user-attachments/assets/7ffcfede-d042-4c93-91d9-704dbf81b6f3)

5.	Pada tampilan berikut klik Next.

    ![image](https://github.com/user-attachments/assets/c9dd4c3a-c0b6-4dda-a772-9ad965931c35)

6.	Pada Tampilan Mapping Options klik Finish.

    ![image](https://github.com/user-attachments/assets/0f952aa6-3e49-46a6-8c66-2f5ed7864b91)

7.	Persistence berhasil dibuat dan menampilkan kelas Matakuliah sesuai dengan tabel database yang kita pilih.

    ![image](https://github.com/user-attachments/assets/7a2ba6e3-8d0a-4abc-a41b-d94a79f1fcc5)

8.	Berikut Libraries yang terbentuk setelah berhasil membuat persistence.

    ![image](https://github.com/user-attachments/assets/5f947737-0cba-438a-83b4-4e1ea5956f53)

9.	Menambahkan library PostgreSQL beserta Library Jasperreport (untuk mencetak data).

    ![image](https://github.com/user-attachments/assets/079f99e9-557d-4e70-8daf-67adf981be31)

10.	Berikut tampilan persistence yang telah berhasil dibuat dengan nama PBO_PersistencePU.

    ![image](https://github.com/user-attachments/assets/8548eb77-ee9a-4153-ae07-e90d882fff3b)

11.	Berikut isi code dari kelas Matakuliah yang terbentuk.

    ![image](https://github.com/user-attachments/assets/4abb4f89-1bd3-4e04-8794-4b6563a8e1d6)
   	![image](https://github.com/user-attachments/assets/69d4e0f6-d078-48f9-984b-54a17c9126b8)
   	![image](https://github.com/user-attachments/assets/e9ccbac8-040d-475b-87b2-a6ae6f57ed4a)
   	![image](https://github.com/user-attachments/assets/5bdd2fb9-4ed0-4702-9b56-b3dd4ab5e25a)

12.	Membuat kelas KoneksiDB dan isi code programnya.

    ![image](https://github.com/user-attachments/assets/b848d82d-24e8-4133-be86-3f64ce363787)

    
13.	Membuat kelas FrameMataKuliah dengan JFrame Form kemudian membuat desain Tampilan GUI. Tampilan GUI Mata Kuliah Berisi Kode MK, SKS, Nama MK, dan Semester Ajar yang diinput menggunakan JTextField, button Insert, Update, Delete, Clear, Cetak, Upload, dan Exit menggunakan JButton, serta tabel Mata Kuliah menggunakan JTable.

    ![image](https://github.com/user-attachments/assets/b69c17a3-9493-48be-8044-b93e6430084e)

14.	Mulai isi code pada FrameMataKuliah. Berikut import yang digunakan.

    ![image](https://github.com/user-attachments/assets/793f6b3b-3a92-4c46-a9c8-abdca1197b96)

15.	Berikut code untuk koneksi program dengan database postgresql disertai method koneksi.

    ![image](https://github.com/user-attachments/assets/d1b6d608-4cf6-4c28-be05-75099d9921fb)

16.	Berikut code method tampil untuk menampilkan data pada tampilan gui, kemudian method peringatan, dan method clear untuk menghapus text pada JTextFields.

    ![image](https://github.com/user-attachments/assets/971400d1-b4dd-41cb-aaae-2736283e7248)

17.	Berikut code btnInsert.

    ![image](https://github.com/user-attachments/assets/95d420e2-2b4c-4c9b-ab90-46c49d8a9567)

18.	Berikut code pada btnUpdate.

    ![image](https://github.com/user-attachments/assets/5ff417d7-20e8-4e4f-ab40-d8b352a28ef5)

19.	Berikut code pada btnDelete.

    ![image](https://github.com/user-attachments/assets/cfe45ce8-2ca6-4fe0-b110-5b70c2ef1cf4)

20.	Berikut code pada btnClear, tblMKMouseClicked, dan btnExit.

    ![image](https://github.com/user-attachments/assets/0dd7c7b1-b250-4dee-b425-dd7239e8efa3)

21.	Berikut code pada btnCetak.

    ![image](https://github.com/user-attachments/assets/829973fd-69cd-4183-8ebc-c246196771b8)

    Desain report cetak:

    ![image](https://github.com/user-attachments/assets/12f7eed6-b2d0-4c4c-a956-03b3c890dcbb)

22.	Berikut code pada btnUpload.

    ![image](https://github.com/user-attachments/assets/f8904ae8-4eda-4506-9913-73a694ce43cd)
   	![image](https://github.com/user-attachments/assets/9da6fcd6-ba64-48cf-be9e-8ef301386942)

23.	Hasil ekseskusi insert data

    ![image](https://github.com/user-attachments/assets/607e7d6b-7d06-4d43-952a-2a54238e5f76)

24.	Hasil eksekusi update data (mengupdate semester ajar pada kode mata kuliah MK002 menjadi semester 2)

    ![image](https://github.com/user-attachments/assets/9d0f30c8-27ac-49ff-ae3c-8d5f2b410940)

25.	Hasil eksekusi delete data (Menghapus data pada kode mata kuliah MK002)

    ![image](https://github.com/user-attachments/assets/f65b53c9-d56a-4499-b3cd-4cd9164cf630)
   	![image](https://github.com/user-attachments/assets/a70da88c-390b-47be-aa45-229e23cd0430)

26.	Hasil eksekusi upload data

    Isi file csv matkul

    ![image](https://github.com/user-attachments/assets/f340a8e9-dabb-46f6-8fa5-a9e5fb475be2)

    Data setelah berhasil di upload

    ![image](https://github.com/user-attachments/assets/6f761475-de82-4fa6-8c69-2a50eef2bf85)

27.	Hasil eksekusi cetak data

    ![image](https://github.com/user-attachments/assets/c48fb028-95f8-4e67-8952-0bf2cd6e1128)





    
















    












