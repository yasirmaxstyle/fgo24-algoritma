# Algoritma Menentukan Bilangan Ganjil dan Genap

1. mulai
2. tentukan sebuah bilangan
3. bagi bilangan tersebut dengan 2
4. apabila hasilnya bilangan bulat maka bilangan tersebut genap, lanjut langkah 6
5. apabila hasilnya bukan bilangan bulat maka bilangan tersebut ganjil
6. selesai


```mermaid
graph TD
A((start))
B[/x/]
C{x % 2 == 0?}
D[/'even'/]
E[/'odd'/]
F(((stop)))

A --> B
B --> C
C --true--> D
C --false--> E
D & E --> F

```