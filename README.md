# Praktikum6
Tugas Praktikum 6 Mata Kuliah Program Komputer dan Praktek
=========================================================================================================================================



**Struktur Data**


    List mahasiswa: Ini adalah wadah utama untuk menyimpan data seluruh mahasiswa. Setiap elemen dalam list ini adalah sebuah dictionary yang merepresentasikan satu mahasiswa.

    Dictionary: Setiap mahasiswa diwakili oleh sebuah dictionary. Dictionary ini memiliki key-value pairs seperti:
    
    Nama: Menyimpan nama mahasiswa sebagai string.
    
    NIM: Menyimpan Nomor Induk Mahasiswa sebagai string.
    
    Nilai Tugas, Nilai UTS, Nilai UAS: Menyimpan nilai-nilai numerik masing-masing komponen penilaian.
    
    Nilai Akhir: Menyimpan nilai akhir yang dihitung berdasarkan bobot.
    
**Alur Program**
-> **Inisialisasi:**

Variabel-variabel seperti nama, nim, dan nilai-nilai lainnya diinisialisasi dengan nilai awal.

List mahasiswa diinisialisasi sebagai list kosong.

-> **Input Data:**
Program akan terus meminta input data mahasiswa selama pengguna ingin menambahkan data.

Setiap kali pengguna memasukkan data, data tersebut akan disimpan dalam sebuah dictionary.

Dictionary tersebut kemudian ditambahkan ke dalam list mahasiswa.

**Perhitungan Nilai Akhir:**
Nilai akhir dihitung berdasarkan rumus yang telah ditentukan, yaitu:

    nilai_akhir = (nilai_tugas * 0.3) + (nilai_uts * 0.35) + (nilai_uas * 0.35)

Hasil perhitungan kemudian disimpan dalam dictionary mahasiswa.


**Menampilkan Data:**
Setelah semua data dimasukkan, program akan menampilkan data seluruh mahasiswa dalam bentuk tabel.
Format tabel dibuat menggunakan print dan format string untuk mengatur tampilan.

**Fungsi-fungsi Utama**

Input: Mendapatkan input dari pengguna untuk setiap data mahasiswa.

Perhitungan: Menghitung nilai akhir berdasarkan bobot yang telah ditentukan.

Penyimpanan: Menyimpan data mahasiswa dalam struktur data yang sesuai (list of dictionaries).

Output: Menampilkan data dalam format yang mudah dibaca.

**CODING PROGRAM**



![Koding 1](https://github.com/user-attachments/assets/0e2d8565-5c17-4fae-84f0-b8bffd4aec57)




**FLOWCHART**

![praktikum 6](https://github.com/user-attachments/assets/b03775c7-d93a-4668-b398-233f22da8a68)



**HASIL PROGRAM**


![hasil 1](https://github.com/user-attachments/assets/1c830531-c4a8-4cef-ab4a-0e4066c52b4a)


