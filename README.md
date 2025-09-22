# Lab1Web.
*Nama : Muhammad Ridho Hafiedz*

*Nim  : 312410195*

*Kelas: TI.24 A2*

1. Lakukan perubahan pada kode sesuai dengan keinginan anda, amati perubahannya adakah error ketika terjadi kesalahan penulisan tag?   
   **Jawaban:**

   Perubahan kode dan kesalahan tag
   Jika terjadi kesalahan penulisan tag (misalnya `<p>` ditulis `<pp>`), browser biasanya **tetap menampilkan halaman**, tapi struktur HTML bisa jadi kacau. Ada elemen yang        tidak ditutup atau salah ketik bisa menyebabkan tampilan tidak sesuai. Jadi, bukan error fatal seperti di bahasa pemrograman, tapi lebih ke error tampilan (rendering error).

2. Apa perbedaan dari tag `<p>` dengan tag `<br>`, berikan penjelasannya!    
   **Jawaban:**
   
   Perbedaan `<p>` dan `<br>`
   - `<p>` (paragraph) digunakan untuk membuat paragraf baru, otomatis memberi jarak atas-bawah.
   - `<br>` (break) hanya digunakan untuk membuat baris baru **tanpa** jarak paragraf. Jadi `<p>` lebih untuk blok teks, sedangkan `<br>` hanya memindahkan baris.

3. Apa perbedaan atribut **title** dan **alt** pada tag `<img>`, berikan penjelasannya!  
   **Jawaban:**

   Perbedaan atribut `title` dan `alt` pada `<img>`
   - ``alt`` = teks alternatif, muncul kalau gambar **nggak bisa ditampilkan** (misalnya koneksi lemot). Selain itu, `alt` juga penting untuk `aksesibilitas`, karena screen reader akan membacakan teks ini buat pengguna disabilitas.
   - `title` = teks yang muncul kalau kita **hover mouse** di atas gambar (tooltip). Jadi, `alt` buat pengganti gambar dan aksesibilitas, `title` buat info tambahan saat hover.
  
4. Untuk mengatur ukuran gambar, digunakan atribut **width** dan **height**. Agar tampilan gambar proporsional sebaiknya kedua atribut tersebut diisi semua atau tidak? Berikan penjelasannya!  
   **Jawaban:**

   Penggunaan **width** dan **height** pada gambar
   - Kalau isi dua-duanya **(width & height)** tanpa sesuai rasio asli gambar → bisa bikin gambar **gepeng atau melar**.
   - Kalau isi **satu aja** (misalnya cuma ``width="200"`), browser otomatis menyesuaikan sisi satunya biar tetap **proporsional**.

5. Pada **link** tambahkan atribut **target** dengan nilai atribut bervariasi (`_blank`, `_self`, `_top,` `_parent), apa yang terjadi pada masing-masing nilai atribut tersebut?   
   **Jawaban:**

   Atribut `target` pada link `<a>`, Atribut target dipakai buat ngatur di mana link akan dibuka:
   - ` _blank` → buka di **tab/jendela baru**.
   - `_self` → buka di **halaman yang sama** (ini default kalau target nggak ditulis).
   - `_top` → buka link di **jendela utama**, berguna kalau halaman pakai farame/iframe
   - `_parent` → buka link di **halaman induk** (kalau ada frame), kalau nggak ada sama kayak `_self`.
  

# TUGAS 
