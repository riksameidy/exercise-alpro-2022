# Algoritma Pemrograman
## Exercise 10


### Introduction
1. Jelaskan mengapa perlu menggunakan numpy array dalam pemrograman untuk sains data!
2. Jelaskan apa perbedaan antara List dan numpy array!
3. Jelaskan perbedaan numpy dengan numpy ndarray!

### Numpy Arrays Basic
1. Jelaskan apa saja cara untuk membuat numpy array!
2. Jelaskan 4 atribut utama dari ndarray!
3. Jelaskan perbedaan dimension dan shape!
4. Jelaskan dan berikan contoh program bagaimana cara slicing dalam numpy array untuk array dengan ndim=1 dan ndim=2!
5. Jelaskan dan berikan contoh program bagaimana cara melakukan reshaping pada ndarray!
6. Jelaskan dan berikan contoh program bagaimana cara melakukan  array concatenation untuk array dengan ndim = 1 dan ndim=2!
7. Jelaskan dan berikan contoh program bagaimana cara melakukan splitting array!
8. Jelaskan apa yang dimaksud dengan parameter axis dalam splitting dan joining array!

### Universal Functions
1. Jelaskan apa yang dimaksud dengan vectorized operation!
2. Jelaskan apa yang dimaksud dengan universal function !
3. Jelaskan keunggulan vectorized operation dengan unvectorized operation!
4. Berikan contoh program perbandingan antara vectorized operation dengan unvectorized operation!
5. Jelaskan 3 tipe universal function!
6. Jelaskan dan berikan contoh implementasi dari unary function!
7. Jelaskan dan berikan contoh implementasi dari binary function!
8. Jelaskan dan berikan contoh implementasi dari sequential function!
9. Jelaskan strategi mereduksi penggunaan memori pada saat mengimplementasikan operasi antara 2 array menggunakan universal function!

### Latihan

1. Height of Presidents. List Height berikut adalah data tinggi badan presiden negara A. 

height = \[189 170 189 163 183 171 185 168 173 183 173 173 175 178 183 193 178 173
 174 183 183 168 170 178 182 180 183 178 182 188 175 179 183 193 182 183
 177 185 188 188 182 185\]

Buatlah program python dengan mengimplementasikan numpy array untuk mengitung rata-rata, median , simpangan baku, dan tinggi maksimum dan minimum pada data height tersebut.


2. Estimating pi using dart
![[estimating_pi_with_dart.png]]

Anda adalah pemain dart yang sangat buruk sehingga ketika anda melemparkan dart ke target, hasilnya selalu random. Anda ingin menggunakan ketidakahlian anda untuk sesuatu yang lain, yaitu mengestimasikan nilai $\pi$. Nilai $\pi$ dapat di estimasikan dengan cara membangkitkan bilangan acak pada area biru dan orange.
Karena setiap lemparan akan menghasilkan titik secara acak, baik di area orange maupun biru, maka peluang dart akan kena di  lingkaran orange adalah rasio antara luas persegi biru dan lingkaran orange:

$$P_{circle} = \frac{Area_{circle}}{Area_{square}} = \frac{\pi r^2}{(2r)^2} = \frac{\pi}{4}$$

dengan menggunakan approksimasi, maka peluang $P_{circle}$ dapat didekati dengan :

$$ P_{circle} \approx \frac{N_{circle}}{N_{square}+N_{circle}} $$

$$ \frac{\pi}{4} \approx \frac{N_{circle}}{N_{square}+N_{circle}} $$

dimana $N_{circle}$ adalah jumlah dart yang kena di di  lingkaran orange dan $N_{square}$ adalah jumlah dart yang kena di area biru. Berdasarkan persamaan diatas kita juga mendapatkan hubungan berikut:

$$ N = N_{circle} + N_{square}$$

dimana N adalah jumlah pelemparan total dari dart.

Asumsikan titik pusat lingkaran adalah koordinat (0,0)

Buatlah program python dengan numpy array untuk mengestimasikan nilai $\pi$ dengan jumlah N=10000 dan r = 1 menggunakan cara:
- Unvectorized Solution
- Vectorized Solution

3. Menghitung Akurasi Model 

Sebuah model Neural Network mendapatkan hasil label target berikut setelah dilakukan proses forward propagation.

| x1  | x2  | x3  | predicted class |
| --- | --- | --- | --------------- |
| 1   | 0   | 1   | 0               |
| 2   | 1   | 0   | 1               |
| -1  | 3   | 5   | 1               |
| 1   | 1   | 1   | 0               |
| 0   | 4   | 3   | 1               | 

sementara data aslinya adalah sebagai berikut:

| x1  | x2  | x3  | actual class |
| --- | --- | --- | ------------ |
| 0   | 4   | 3   | 1            |
| 1   | 1   | 1   | 0            |
| -1  | 3   | 5   | 0            |
| 2   | 1   | 0   | 1            |
| 1   | 0   | 1   | 0            |


Untuk mengevaluasi model tersebut, maka digunakan metrics bernama akurasi yang didefinisikan sebagai:

$$accuracy = \frac{TP + TN}{N}$$

dimana :
- TP adalah jumlah kelas 1 yang tepat diklasifikasikan sebagai 1 (saat predicted class= 1 dan actual class = 1)
- TN adalah jumlah kelas 0 yang tepat diklasifikasian sebagai 0 (saat peredicted class=0 dan actual class = 0)
- N adalah total data

buatlah sebuah program python untuk menghitung akurasi dari model tersebut dengan menggunakan cara:
- Unvectorized Solution
- Vectorized Solution


