#Query-query Dasar NoSQL

Repository ini dibuat untuk latihan dasar-dasar operasi dan query pada database **NoSQL**.  
Project ini berisi file HTML sederhana yang digunakan untuk latihan Git, GitHub, dan penyelesaian konflik merge antara local dan remote.

---

# Tujuan Project
- Memahami cara kerja Git (commit, push, pull)
- Mempelajari cara membuat konflik antar versi
- Melatih penyelesaian konflik merge
- Latihan membuat repository GitHub
- Latihan query dasar NoSQL (MongoDB / Firebase / Cassandra, dll.)

# Isi Repository
- index.html — File HTML yang digunakan sebagai latihan perubahan lokal dan remote.
- README.md — Dokumentasi project.

# Latihan Git yang Dipraktikkan
1. Membuat folder Tugas dan file (index.html)
2. Inisialisasi Git (git init)
3. Menambahkan remote repository GitHub
4. Push pertama (git push -u origin main)
5. Mengubah isi file di GitHub dan local secara berbeda
6. Membuat konflik merge
7. Menyelesaikan konflik menggunakan:
- git pull


# Contoh Query NoSQL Sederhana (MongoDB)
```js
// Insert data
db.users.insertOne({
  name: "Budi",
  age: 20
});

// Menampilkan semua data
db.users.find();

// Filter data
db.users.find({ age: { $gt: 18 } });
