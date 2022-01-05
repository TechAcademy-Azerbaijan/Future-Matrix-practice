# Matrix practice 🧠

## Task 1 🎯

### Matrisdə mənfi cüt elementlər
n * n ölçülü matris verilmişdir. Onun mənfi cüt elementlərinin sayını və cəmini tapın.

### Input
İlk sətirdə n (1 ≤ n ≤ 100) ədədi verilir. Növbəti sətirlərdə n * n olçülü matrisin elementləri verilir. Matrisin elementləri modulca 100-ü aşmır.

### Output
Matrisdəki mənfi cüt elementlərin sayını və cəmini çap edin.

:clock2: Time limit 1 second

:floppy_disk: Memory limit 128 MiB

#### Input example 

    3
    4 -2 5
    1 -4 -12
    0 1 -3


#### Output example 

    3 -18

---

## Task 2 🎯

### Matrisi çapa verin
nxn ölçülü massiv verilir - bu massivi [1..n] * [1..n] massivi adlandıraq. Verilən r və c dəyərlərinə uyğun [1..r] * [1..c] massivini çapa verin (verilən massivin r sayda sətrini və c sayda sütununu).

### Input
İlk sətirdə n ədədi verilir (1 ≤ n ≤ 100). Növbəti sətirdə nxn matrisi. Sonuncu sətirdə isə r və c ədədləri verilir (1 ≤ r, c ≤ n). Matrisin elementləri modulca 100-dən böyük deyil.

### Output
rxc matrisini çapa verin.

:clock2: Time limit 1 second

:floppy_disk: Memory limit 128 MiB

#### Input example 1

    4
    1 2 3 4
    5 6 7 8
    9 1 2 3
    4 5 6 7
    3 2



#### Output example 1
    1 2
    5 6
    9 1

#### Input example 2

    5
    1 5 -3 2 6
    6 3 34 5 8
    10 12 3 18 -25
    13 22 11 9 45
    23 39 20 15 -49
    4 3


#### Output example 2

    1 5 -3
    6 3 34
    10 12 3
    13 22 11


---


## Task 3 🎯

### Minimal elementin olduğu sətirlər
n * m ölçülü ikiölçülü massiv verilmişdir. Minimal elementin olduğu sətirləri tapın.


### Input
İlk sətirdə massivin sətir və sütunlarının sayını ifadə edən iki n və m (1 ≤ n, m ≤ 100) ədədləri verilir. Sonra hər birində m ədəd olan n sətir verilir. Bütün ədədlər modulca 100-ü aşmır. Massivin elementlərinin nömrələnməsi 1-dən başlayır.

### Output
Ayrı-ayrı sətirlərdə minimal elementin olduğu sətirlərin nömrələrini artan ardıcıllıqda çap edin.

:clock2: Time limit 1 second

:floppy_disk: Memory limit 128 MiB

#### Input example 1

    4 5
    2 5 3 1 4
    3 5 2 3 4
    4 6 1 2 3
    4 5 6 7 7



#### Output example 1

    1 3

#### Input example 2

    10 10
    12 13 23 11 21 11 11 11 11 11
    11 21 15 11 14 18 11 19 11 11
    12 31 61 11 31 17 11 67 11 11
    13 14 17 11 12 16 11 11 11 11
    14 13 81 11 13 51 11 11 35 44
    75 22 19 11 14 14 11 11 11 11
    16 34 11 11 15 31 11 11 11 11
    17 14 11 11 16 12 11 11 11 11
    21 15 11 11 11 11 11 11 11 11
    16 34 11 11 15 31 11 11 11 11



#### Output example 2

    1 2 3 4 5 6 7 8 9 10

---

## Task 4 🎯

### Print the chessboard
You are given a chessboard of size n * n. It is filled with numbers from 1 to n**2 in the following way: the first ceil(n**2 / 2) numbers from 1 to ceil(n**2 / 2) are written in the cells with even sum of coordinates from left to right from top to bottom. The rest n**2 - ceil(n**2 / 2) numbers from ceil(n**2 / 2) + 1 to n**2 are written in the cells with odd sum of coordinates from left to right from top to bottom. The operation ceil(x / y) means division x by y rounded up.

### Input
One integer n (1 ≤ n ≤ 9).


### Output
Print the matrix - the chessboard in the given manner. Watch for allignment!

:clock2: Time limit 1 second

:floppy_disk: Memory limit 128 MiB

#### Input example 1

    5

#### Output example 1

     1 14  2 15  3 
    16  4 17  5 18 
     6 19  7 20  8 
    21  9 22 10 23 
    11 24 12 25 13 


#### Input example 2

    6


#### Output example 2

     1 19  2 20  3 21 
    22  4 23  5 24  6 
     7 25  8 26  9 27 
    28 10 29 11 30 12 
    13 31 14 32 15 33 
    34 16 35 17 36 18 


---
