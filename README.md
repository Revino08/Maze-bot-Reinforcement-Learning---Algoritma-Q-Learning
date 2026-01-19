# Maze-bot-Reinforcement-Learning---Algoritma-Q-Learning
Ini adalah Final Semester Exam dari Mata kuliah Sistem Kontrol RE703, Disini kami mengambil metode Reinforcement Learning menggunakan Algoritma Q-Learning.
****************************
## Nama Kelompok :
1. Silvanus Jokhanan Setijono - 4222001004
2. Revino Jantri Putra - 4222201021
****************************
**Reinforcement Learning (RL)** adalah salah satu cabang machine learning di mana sebuah agen belajar mengambil keputusan dengan cara mencoba (trial and error) di suatu lingkungan (environment) untuk mendapatkan reward (imbalan).
Konsep dasarnya :

State (S)
- kondisi lingkungan saat ini
contoh: posisi robot di labirin

Action (A)
- tindakan yang bisa dilakukan agent
contoh: maju, kiri, kanan

Reward (R)
- nilai umpan balik dari environment

Jadi pada tugas ini kami mengambil Reinforcement Learning dimana nanti Robot/bot berada pada lingkungan labirin, dimana robot tersebut berjalan dari titik Start menuju titik Goal.
Setiap pergerakan robot akan dihitung poinnya.
Goals = +100
Bergerak tanpa reward = -1
Nabrak dinding/stage = -10
