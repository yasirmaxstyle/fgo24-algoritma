# Algoritma Menghitung Luas dan Keliling Lingkaran

1. Mulai
2. Tentukan *jari-jari* lingkaran
3. Apabila *jari-jari* habis dibagi 7 maka $phi$ = **22/7**
4. Apabila tidak maka $phi$ = **3,14**
5. Kalikan $phi$ dengan *jari-jari* yang dikuadratkan untuk menghitung luas lingkaran
6. Kalikan $phi$ dengan *jari-jari* lalu kalikan 2 untuk menghitung keliling lingkaran
7. Selesai

```mermaid

---
title: Flowchart
---
graph TD
A((start))
B[/r, &#960/]
C{r % 7 == 0?}
D[/&#960 = 22/7/]
E[/&#960 = 3.14/]
F[luas = &#960 * r * r]
G[keliling = &#960 * r * 2]
H[/'luas', "keliling"/]
I(((stop)))

A a@--> B
B b@--> C
C c@--true--> D
C d@--false--> E
D dd@--> F
E e@--> F
F f@--> G
G g@--> H
H h@--> I

classDef animate stroke-dasharray: 5,5,stroke-dashoffset: 500,animation: dash 15s linear infinite;
class a,b,c,d,dd,e,f,g,h animate
```