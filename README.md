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
- nilai hadiah dari environment

Jadi pada tugas ini kami mensimulasikan Reinforcement Learning menggunakan algoritma Q-Learning dimana nanti Robot/bot melatih dan menentukan jalan dari titik Start menuju titik Goal didalam lingkungang Maze atau Labirin.
Setiap pergerakan robot akan dihitung poinnya.
Goals = +100
Bergerak tanpa reward = -1
Nabrak dinding/stage = -10

Dan kami membuat 3 Step Maze/labirin namun kami bikin random pada programnya

**Easy/Simple = 5x5**

<img width="500" height="300" alt="image" src="https://github.com/user-attachments/assets/e13f58a8-2f06-4552-840d-94bb4c65089d" />

**Medium = 5x5 (Banyak rintangan labirin)**

<img width="500" height="300" alt="image" src="https://github.com/user-attachments/assets/19c0ae67-77be-4002-b97c-5b259c4f8e38" />

**Hard = 7x7**

<img width="500" height="300" alt="image" src="https://github.com/user-attachments/assets/5fb185cf-266b-49a3-a8ae-d23fcd14b75d" />

********************************
Penjelasan Program

<img width="250" height="200" alt="image" src="https://github.com/user-attachments/assets/914adf81-ddd2-4f43-8d97-4061b6e9c3a1" />

Library yang digunakan pada pensimulasian Gerak Robot

<img width="250" height="200" alt="image" src="https://github.com/user-attachments/assets/470f60be-babb-453c-8e55-d03983d2b204" />

Program ini adalah pemanggilan dari setiap maze atau labirin dimana terdapat 3 step dari easy, medium dan Hard

<img width="300" height="486" alt="image" src="https://github.com/user-attachments/assets/34551b45-8935-468c-b2b8-51e66f437912" />

Diatas adalah pemanggilan Reward yang akan didapatkan pada simulasi robot
* Goals = +100
* Bergerak tanpa reward = -1
* Nabrak dinding/stage = -10

<img width="1309" height="561" alt="image" src="https://github.com/user-attachments/assets/706d8f18-787b-40c7-8f06-57ddcc016351" />

Program diatas berfungsi untuk mengetahui visualisasi ukuran, warna dan bentuk dari maze atau labirin 

<img width="578" height="441" alt="image" src="https://github.com/user-attachments/assets/dd43c721-1dd6-43fe-9d83-789c7bd0acd9" />

Diatas ini tahap untuk mensimulasikan dari kesleuruhan program dan menampilkan pergerakan dan visualisasi map.
