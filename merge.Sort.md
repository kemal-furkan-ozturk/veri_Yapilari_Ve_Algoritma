# veri_Yapilari_Ve_Algoritma
## Merge Sort Projesi
#### A. [16, 21, 11, 8, 12, 22]
#### ** Yukarı verilen dizinin sort türüne göre aşamalarını ve Big-O gösterimini yazınız.
#### 1-) [16, 21, 11] - [8, 12, 22] 
#### 2-) [16] - [21, 11] - [8] - [12, 22] 
#### 3-) [16] - [21] - [11] - [8] - [12] - [22] 
#### 4-) [16, 21] - [11] - [8, 12] - [22] 
#### 5-) [11, 16, 22] - [8, 12, 22] 
#### 6-) [8, 11, 16, 18, 21, 22] 
#### - Bu işlem yukarıda görüldüğü gibi dizi terimleri 2 eşit (mümkün olduğunca) parçaya bölünerek her elemen tek bırakılır.Daha sonra terimler aralarında aynı şekilde birleştirilerek ve sıralanarak, tekrar veri dizisi birleştirilir. Sonuç olarak sorting (sıralama) işlemi tamamlanır.
#### - Merge sort algoritmasında Big O Notion O(n*logn) olarak bulunur.
