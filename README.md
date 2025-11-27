# Ujian-Akhir-Semester
### Soal dan Jawaban Ujian Akhir Semester Mata Kuliah Logika dan Algoritma.

#### Mata Kuliah: Logika dan Algoritma
#### Dosen Pengampu: Ahmad Syauqi Ahsan, S.Kom., M.T.


1. Perbedaan Rentang Indeks pada Modul 6 (List) dan Modul 10 (String)
Soal:
Dalam materi struktur data yang diajarkan, terdapat perbedaan mendasar mengenai aturan penomoran indeks awal. Mengacu pada pseudocode algoritma rata-rata kelas di Modul 6 (List) dan teori pengindeksan karakter di Modul 10 (String), jelaskan bagaimana perbedaan rentang indeks (index range) yang digunakan pada kedua modul tersebut?

Jawaban:
Modul 6 (List) menggunakan one-based indexing (indeks dimulai dari 1), sedangkan Modul 10 (String) menggunakan zero-based indexing (indeks dimulai dari 0). Hal ini memengaruhi cara mengakses elemen pertama (list[1] vs string[0]) dan elemen terakhir (list[N] vs string[N-1]).

2. Referensi Definisi Computational Thinking
Soal:
Banyak literatur umum mengasosiasikan istilah Computational Thinking dengan Jeanette Wing. Namun, pada Modul 2 (Introduction of Computational Thinking), terdapat kutipan definisi spesifik: "a focused approach to problem solving, incorporating thought processes that utilize abstraction, decomposition, algorithms, evaluation, and generalizations". Siapakah tokoh dan tahun berapakah referensi yang digunakan dalam slide tersebut untuk definisi ini?

Jawaban:
Definisi tersebut dikutip dari Shelby (2013), bukan Jeanette Wing, seperti yang tercantum pada Slide 5 Modul 2.

3. Proses Pertukaran Pertama pada Selection Sort
Soal:
Mengacu pada algoritma Selection Sort yang dideskripsikan langkah demi langkah dalam Modul 11 (Searching and Sorting), jika kita memiliki list awal [20, 12, 10, 15], jelaskan secara presisi apa yang terjadi pada proses pertukaran (swap) pertama berdasarkan instruksi tertulis di modul tersebut?

Jawaban:
Berdasarkan modul, langkah pertama Selection Sort adalah "Locate smallest element in array. Exchange it with element in position 0". Pada list [20, 12, 10, 15], elemen terkecil adalah 10 (indeks 2). Proses swap pertama menukar 10 dengan 20 (indeks 0), menghasilkan [10, 12, 20, 15].

4. Kategorisasi Argumen Berdasarkan Matriks Modul 1
Soal:
Dalam matriks klasifikasi argumen pada Modul 1 (Introduction of Logic Algorithm), bagaimana Anda mengkategorikan sebuah argumen yang alur logikanya valid dan runtut, namun didasarkan pada premis atau data awal yang salah secara fakta?

Jawaban:
Berdasarkan matriks Modul 1, argumen dengan logika valid tetapi berdasarkan premis fakta yang salah dikategorikan sebagai Logically Correct but Factually Incorrect. Contohnya adalah struktur deduktif yang runtut, namun kesimpulannya salah karena data awalnya keliru.

5. Simbol Flowchart untuk Subrutin
Soal:
Dalam Modul 9 (Decomposition), dijelaskan teknik memecah masalah kompleks menjadi bagian-bagian kecil. Simbol flowchart spesifik apakah yang disebutkan dalam modul tersebut sebagai penanda untuk langkah proses yang telah didefinisikan secara formal di tempat lain (subrutin)?

Jawaban:
Simbol yang disebutkan adalah Predefined Process Symbol. Simbol ini dalam flowchart menandai sebuah sub-proses atau subrutin yang langkah-langkah detailnya telah didefinisikan secara formal di tempat lain.

6. Syarat Eksekusi Loop Body pada Studi Kasus "Happy New Year"
Soal:
Pada studi kasus "Happy New Year" di Modul 5 (Pattern Recognition), terdapat analisis baris kode untuk hitung mundur. Berdasarkan teks penjelasan di slide, apa syarat spesifik agar instruksi pada baris 3 dan 4 (yang disebut sebagai loop body) dapat dieksekusi?

Jawaban:
Berdasarkan Modul 5, instruksi baris 3 dan 4 (loop body) hanya dieksekusi jika kondisi WHILE time > 0 pada baris 2 bernilai TRUE.

7. Definisi dan Konsekuensi Definiteness dalam Algoritma
Soal:
Modul 1 dan Modul 3 menyebutkan lima properti utama algoritma, salah satunya adalah Definiteness. Jelaskan definisi mendalam dari Definiteness menurut modul tersebut dan apa konsekuensi teknis jika properti ini tidak terpenuhi?

Jawaban:
Definiteness berarti setiap langkah algoritma harus didefinisikan secara tepat dan tanpa ambiguitas. Jika tidak terpenuhi, algoritma gagal dieksekusi secara konsisten oleh komputer, menyebabkan error atau output yang salah karena tidak ada ruang untuk interpretasi.
