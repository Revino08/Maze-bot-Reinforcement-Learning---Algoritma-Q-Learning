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

Jadi pada tugas ini kami mensimulasikan Reinforcement Learning menggunakan algoritma Q-Learning dimana nanti Robot/bot melatih dan menentukan jalan dari titik Start menuju titik Goal didalam lingkungang Maze atau Labirin.
Setiap pergerakan robot akan dihitung poinnya.
Goals = +100
Bergerak tanpa reward = -1
Nabrak dinding/stage = -10

Dan kami membuat 3 Step Maze/labirin namun kami bikin random pada programnya

Easy/Simple = 5x5
<img width="1919" height="934" alt="image" src="https://github.com/user-attachments/assets/e13f58a8-2f06-4552-840d-94bb4c65089d" />


Medium = 5x5 (Banyak rintangan labirin)

Hard = 7x7
