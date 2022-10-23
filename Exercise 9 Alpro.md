
## Review
- Jelaskan apa yang dimaksud Identifier!
- Jelaskan apa yang dimaksud dengan Object!
- Terdapat Code python sebagai berikut:

```python
C = 10
D = 20.5
C = C+1
D = C
```
Jelaskan dan gambarkan proses assignment yang terjadi menggunakan grafik variabel dan memory address!
- Berdasarkan Pemahaman anda, apakah perbedaan copy by reference dan copy by value?

## Python Sequence Type
- Jelaskan apa yang dimaksud dengan sequence class!
- Berikan 3 contoh sequence class dalam python!
- Jelaskan 2 persamaan antara 3 sequence class tersebut!
- Jelaskan apa yang dimaksud dengan array!
- Jelaskan 3 ciri utama dari array!
- Gambarkan dan illustrasikan contoh 1D array!
-  Gambarkan dan illustrasikan contoh 2D array!
- Berikan contoh 1D array dan 2D array!
- Jelaskan apa perbedaan antara Lists dan Array!

## Lists
- Jelaskan apa yang dimaksud dengan List dan ciri ciri nya!
- Jelaskan bagaimana cara access element di list! buatlah contoh programnya!
- Jelaskan bagaimana cara mengubah element di list!
- Jelaskan bagaimana cara menambahkan element di list!
- Jelaskan bagaimana cara menghapus element di list
- Berikan contoh impelementasi menggunakan fungsi .index() , .sort() dan .reverse()
- Jelaskan bagaimana cara iterasi element dari list!

## Tuple
- Jelaskan apa yang dimaksud dengan tuple dan ciri ciri nya!
- Jelaskan bagaimana cara untuk membuat tuple dan buat contoh code nya!
- Jelaskan cara membuat tuple dengan 1 elemen!
- Jelaskan mengenai tuple packing dan unpacking!
- Jelaskan bagaimana cara akses elemen dari tuple!
- Jelaskan mengenai operasi dalam tuple!
- Jelaskan bagaimana menghapus tuple!
- Berikan contoh implementasi method .count(), .index() dan cara iterasi elemen tuple!
- Jelaskan perbedaan antara tuple dan list!

## Set
- Jelaskan apa yang dimaksud dengan set dan ciri cirinya!
- Jelaskan bagaiamana cara untuk membuat set dan buat contoh code nya!
- Jelaskan apakah set dapat diubah elemen nya!
- Implementasikan fungsi add() dan update(), jelaskan perbedaan nya!
- Jelaskan bagaimana cara menghapus element dari set, implementasikan code nya!
- Jelaskan dan berikan contoh implementasi set operation union,intersection, set difference dan set symetric difference
- Implementasikan fungsi all(), any() , enumerate(),len(), max(), min(),sorted() dan sum()

## Dictionary
- Jelaskan apa yang dimaksud dengan dictionary dan ciri cirinya!
- Jelaskan bagaimana cara membuat dicitonary!
- Jelaskan bagaimana mengakses elemen dalam dictionary! berikan contoh code nya!
- Jelaskan bagaimana cara menambah dan mengubah elemen dari dictionary!
- Jelaskan bagaiamana cara menghapus elemen dari dictionary!

## Latihan
1. Lengkapi tabel berikut ini!

| Sequence Type | Mutability | Access by Index | Duplicate Element | Change Element | Add / Remove Element |
| ------------- | ---------- | --------------- | ----------------- | -------------- | -------------------- |
| List          |            |                 |                   |                |                      |
| Tuple         |            |                 |                   |                |                      |
| Set           |            |                 |                   |                |                      |
| Dictionary    |            |                 |                   |                |                      |

2. Terdapat data sebagai berikut: 
	**data:** 1,2,1,2,3,10,11,5,6,19,20,30,50,50,50,20,9,4,5,12,11,11,30,50,90,80,80
	dengan mengimplementasi sequence type , buatlah program untuk:
	- Menghitung rata rata dari data tersebut
	- Mencari apa saja nilai unik yang dari data tersebut
	- Menghitung frekuensi kemunculan dari setiap elemen unik tersebut

3. Terdapat tabel grade mahasiswa sebagai berikut:

| NIM        | NAMA  | ALPRO | STRUKDAT | ADS | LMD | ALE |
| ---------- | ----- | ----- | -------- | --- | --- | --- |
| 1301142289 | ISA   | A     | A        | A   | A   | A   |
| 1301140389 | LIA   | C     | A        | B   | A   | AB  |
| 1301142099 | NAMDY | B     | B        | BC  | AB  | D   |
| 1301142091 | SANDI | B     | C        | D   | A   | A   | 

- Jelaskan sequence type apa yang cocok digunakan untuk mengolah data tersebut!
- Buatlah program untuk menghitung ipk dari setiap mahasiswa pada tabel tersebut!

4. The Anagram Problem.

Original Text: 'Institut Teknologi Sumatera'

Result Text: EAIGLKNMROTSU

Buatlah program untuk mengubah sebuah string menjadi string lain dengan rule sebagai berikut:
- Hasil result string seluruhnya adalah capital.
- Tidak ada huruf yang duplikat dalam string result.
- Posisi character si string baru terurut secara ascending, namun index genap dan ganjil di tukar dalam pair. Contoh: AEJK menjadi EAKJ.