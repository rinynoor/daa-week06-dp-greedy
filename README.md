# DAA Week 06 — Dynamic Programming & Greedy Algorithms

Interactive learning module untuk mata kuliah **Design and Analysis of Algorithms (DAA)** pada Pertemuan 06.

Modul ini membantu mahasiswa memahami dua strategi penting dalam desain algoritma:

- Dynamic Programming (DP)
- Greedy Algorithm

Pembelajaran dirancang secara problem-based dan interaktif. Mahasiswa tidak langsung diberikan definisi, tetapi diajak mencoba problem, mengamati hasil, memahami konsep, menjalankan simulasi, membandingkan strategi, dan memberikan reasoning terhadap pilihan algoritma.

## Learning Outcome

Setelah menyelesaikan modul ini, mahasiswa diharapkan mampu:

1. Mengenali karakteristik optimization problem.
2. Menjelaskan cara berpikir Greedy Algorithm.
3. Menjelaskan cara kerja Dynamic Programming.
4. Memahami subproblem, overlapping subproblems, dan optimal substructure.
5. Membedakan memoization dan tabulation.
6. Menentukan kapan Greedy atau Dynamic Programming lebih sesuai digunakan.
7. Memberikan reasoning terhadap strategi algoritma yang dipilih.

## Learning Flow

Problem → Try → Observe → Understand → Simulate → Compare → Decide → Explain → Reflect

## Materi dan Aktivitas

Modul mencakup:

- Coin Change Problem
- Greedy Algorithm
- Local Choice dan Global Optimum
- Activity Selection
- Fibonacci
- Dynamic Programming
- Subproblem
- Overlapping Subproblems
- Optimal Substructure
- Memoization
- Tabulation
- Knapsack Problem
- Fractional Knapsack
- 0/1 Knapsack
- DP vs Greedy Decision Guide
- Decision Lab
- Knowledge Check
- Reflection

## Interactive Simulations

Beberapa konsep dipelajari melalui simulasi interaktif:

### Coin Change

Mahasiswa mencoba menyelesaikan target menggunakan sejumlah koin dan melihat bahwa pilihan yang terlihat terbaik pada satu langkah belum tentu menghasilkan global optimum.

### Activity Selection

Mahasiswa mengamati bagaimana Greedy Algorithm dapat memilih aktivitas berdasarkan earliest finish time.

### Fibonacci & Dynamic Programming

Mahasiswa melihat munculnya overlapping subproblems dan bagaimana hasil perhitungan dapat disimpan dan digunakan kembali.

### Memoization vs Tabulation

Mahasiswa membandingkan pendekatan:

- Memoization — Top-Down
- Tabulation — Bottom-Up

### Knapsack

Mahasiswa membandingkan:

- Fractional Knapsack → dapat diselesaikan dengan Greedy pada formulasi klasiknya.
- 0/1 Knapsack → digunakan sebagai contoh Dynamic Programming.

## Prinsip Pembelajaran

Modul tidak hanya meminta mahasiswa menghafal definisi algoritma.

Mahasiswa diarahkan untuk menjawab pertanyaan:

> Strategi apa yang saya pilih, dan mengapa strategi tersebut sesuai untuk problem ini?

AI, jika digunakan dalam proses pembelajaran, ditempatkan sebagai learning assistant setelah mahasiswa mencoba melakukan reasoning sendiri.

## Cara Menjalankan

Tidak diperlukan instalasi khusus.

Buka file:

`daa-week06-dp-greedy.html`

menggunakan web browser.

Modul menggunakan HTML, CSS, dan JavaScript dan dapat dijalankan secara lokal.

## GitHub Pages

Repository ini dapat dipublikasikan menggunakan GitHub Pages.

Jika menggunakan file `index.html`, halaman dapat diakses langsung dari root GitHub Pages repository.

Jika menggunakan nama:

`daa-week06-dp-greedy.html`

maka file tersebut dapat diakses melalui URL GitHub Pages dengan menambahkan nama file pada akhir URL.

## Repository Structure

```text
daa-week06-dp-greedy/
│
├── README.md
└── daa-week06-dp-greedy.html
