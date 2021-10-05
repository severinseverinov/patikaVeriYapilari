# Patika Veri Yapıları ve Algoritmalar
Veri yapıları ve Algoritmalar Patikasının Projeleri
## Proje 1 Insertion Sort Projesi
[22,27,16,2,18,6] -> İnsertion Sort
1. Yukarıda verilen dizinin sort türüne göre aşamaları
[2,27,16,22,18,6] -> [2,6,16,22,18,27] -> [2,6,16,18,22,27]
2. Big-O gösterimi
n.(n-1)/2 -> On^2)
3.Average Case : O(n^2) worst case : O(n^2) best case : O(n)
4. 18 sayısı average case kapsamına girer.
---
   [7,3,5,8,2,9,4,15,6]
1. [2,3,5,8,7,9,4,15,6]
2. [2,3,5,8,7,9,4,15,6]
3. [2,3,4,8,7,9,5,15,6]
4. [2,3,4,5,7,9,8,15,6]

## Proje 2 Merge Sort Projesi

[16,21,11,8,12,22] -> Merge Sort
> Yukarıdaki dizinin sort türüne göre aşamaları
1. [16,21,11]          [8,12,22]
2. [16,21][11]         [8][12,22]
3. [16][21][11]        [8][12][22]
4. [16,21][11]         [8,12][22]
5. [11,16,21]          [8,12,22]
6. [8,11,12,16,21,22]
> O(nlogn)

## Proje 3 Merge Sort Projesi
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] -> Binary-Search-Tree
> Yukarıdaki dizinin Binary-Search-Tree aşamaları
1. [7]
2. [5,7]
3. [1,5,7]
4. [1,5,7,8]
5. [1,3,5,7,8]
6. [1,3,5,6,7,8]
7. [1,3,5,6,7,8,9]
8. [1,3,4,5,6,7,8,9]
9. [1,2,3,4,5,6,7,8,9]