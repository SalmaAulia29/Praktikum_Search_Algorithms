# Praktikum Algoritma Pencarian (Search Algorithms)
2306143_SALMA AULIA NISA

## 🎉 Deskripsi
Repository ini berisi implementasi berbagai algoritma pencarian dalam **Python**, meliputi:

- **Uninformed Search**:
1. DFS (Depth First Search): Menelusuri graph dengan pendekatan menyelam ke dalam cabang terlebih dahulu sebelum kembali ke node sebelumnya.
2. BFS (Breadth First Search): Menelusuri graph secara melebar dengan mengunjungi semua node pada satu tingkat sebelum melangkah ke tingkat berikutnya.
3. UCS (Uniform Cost Search): Pencarian jalur optimal berdasarkan bobot atau biaya antar node.
   
- **Informed Search**:
1. Greedy Best-First Search: Menggunakan fungsi heuristik untuk memilih node dengan estimasi terbaik menuju tujuan.
2. A* Tree Search: Kombinasi UCS dan heuristik untuk mendapatkan jalur terpendek.
3. A* Graph Search: Mirip dengan A* Tree Search, tetapi menghindari eksplorasi ulang pada node yang sudah dikunjungi.

Algoritma-algoritma ini digunakan untuk mencari jalur optimal dalam suatu graph dengan berbagai pendekatan, baik pencarian tanpa informasi tambahan (uninformed) maupun pencarian dengan informasi heuristik (informed).

## 📁 File dalam Repository
- `dfs.py` → Implementasi Depth First Search
- `bfs.py` → Implementasi Breadth First Search
- `ucs.py` → Implementasi Uniform Cost Search
- `greedy_best_first.py` → Implementasi Greedy Best-First Search
- `a_star_tree.py` → Implementasi A* Tree Search
- `a_star_graph.py` → Implementasi A* Graph Search

Setiap file berisi implementasi algoritma dengan contoh penggunaan yang dapat diuji langsung.

## 🚀 Cara Menjalankan di Google Colab
1. **Clone repository ini ke Google Colab atau komputer lokal**:
   ```bash
   git clone https://github.com/username/repository-name.git
   cd repository-name
   ```
2. **Jalankan file Python yang diinginkan**:
   ```bash
   python dfs.py
   python bfs.py
   python ucs.py
   ```


