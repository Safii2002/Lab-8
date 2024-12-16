# Lab 8
Program ini bertujuan untuk mengelola data nilai mahasiswa menggunakan konsep class dan object, dengan tampilan perintah sebagai berikut :

![Screenshot 2024-12-16 210938](https://github.com/user-attachments/assets/df87b385-abc4-4793-a618-e35a38ad1e64)

![Screenshot 2024-12-16 211000](https://github.com/user-attachments/assets/f38e3582-6c2e-4119-878c-0ad71c498b95)

# Struktur Program
Program ini terdiri dari satu class bernama Mahasiswa, yang bertugas mengelola data mahasiswa seperti nama dan nilai mereka. Ada juga logika utama di bawah blok if __name__ == "__main__" untuk menjalankan aplikasi secara interaktif.

# Class Mahasiswa
Class ini berisi atribut dan metode sebagai berikut:

A. Atribut:

- data: Sebuah dictionary (dict) untuk menyimpan data mahasiswa.
- Key: Nama mahasiswa (str).
- Value: Nilai mahasiswa (float).

B. Method:

- __init__():
    > Konstruktor untuk menginisialisasi atribut data sebagai dictionary kosong.
- tambah(nama, nilai):
    > Menambahkan data mahasiswa ke dalam atribut data.
    > Jika mahasiswa sudah ada, nilainya akan diperbarui secara otomatis.
- tampilkan():
    > Menampilkan semua data mahasiswa dalam format yang rapi.
    > Jika tidak ada data, mencetak pesan "Tidak ada data mahasiswa."
- hapus(nama):
    > Menghapus data mahasiswa berdasarkan nama.
    > Jika nama tidak ditemukan, mencetak pesan "Data tidak ditemukan."
- ubah(nama, nilai):
    > Mengubah nilai mahasiswa berdasarkan nama.
    > Jika nama tidak ditemukan, mencetak pesan "Data tidak ditemukan."


# Program Utama:

   A) Menu Utama
      Menampilkan pilihan operasi
       1. Tambah Data
       2. Tampilkan Data
       3. Hapus Data
       4. Ubah Data
       5. Keluar dari program.

    B) Operasi
       - Tambah Data:
         > Meminta input nama dan nilai mahasiswa untuk ditambahkan. 
       - Tampilkan Data:
         > Menampilkan seluruh daftar mahasiswa dan nilai mereka.
       - Hapus Data:
         > Meminta input nama mahasiswa untuk menghapus data mereka.
       - Ubah Data:
         > Meminta input nama mahasiswa dan nilai baru untuk memperbarui data mereka.
       - Keluar:
         > Mengakhiri program.
   C) Validasi Input:
      - Program memeriksa validitas input (misalnya, apakah nama ditemukan atau tidak) dan memberikan pesan yang sesuai.

# Diagram Class:

+---------------------+
|      Mahasiswa      |
+---------------------+
| - data: dict        |
+---------------------+
| + __init__() : None                         |
| + tambah(nama: str, nilai: float) : None    |
| + tampilkan() : None                        |
| + hapus(nama: str) : None                   |
| + ubah(nama: str, nilai: float) : None      |
+---------------------+

![diagram class](https://github.com/user-attachments/assets/0e5eaf50-4555-46e8-8e63-593bf2b91510)

# Contoh Hasil Output dari Program:

![Screenshot 2024-12-16 211016](https://github.com/user-attachments/assets/e1643187-590d-4c92-99c2-24782978de08)

![Screenshot 2024-12-16 211029](https://github.com/user-attachments/assets/7171c605-0be1-423d-9f22-f77628b0292c)

# Flowchart

![flow chart](https://github.com/user-attachments/assets/bcb02c91-b942-467b-91cc-a532694bc056)
