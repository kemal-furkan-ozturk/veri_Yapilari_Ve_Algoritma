# veri_Yapilari_Ve_Algoritma

## Selection Sort Projesi

#### A. [22,27,16,2,18,6] 

####	** Yukarı verilen dizinin sort türüne göre aşamalarını ve Big-O gösterimini yazınız.
#### 1-) [22,27,16,2,18,6] --> En küçük sayı bulunur ve ilk veri ile yer değiştirilir. (22->2)
#### 2-) [2,27,16,22,18,6] --> Daha sonra bu işlem 2. en küçük sayı ve ikinci sıradaki veri için tekrarlanır. (27->6)
#### 3-) [2,6,16,22,18,27] --> Aynı işlem 3. en küçük sayı ve üçüncü sıradaki veri için tekrarlanır. 16 sayısı zaten olması gereken yerde olduğu için sırası değiştirilmez. (16->16)
#### 4-) [2,6,16,22,18,27] --> Aynı işlem 4. en küçük sayı ve dördüncü sıradaki veri için tekrarlanır. (18->22)
#### 5-) [2,6,16,18,22,27] --> Aynı işlem 5. en küçük sayı ve beşinci sıradaki veri için tekrarlanır. 22 sayısı zaten olması gereken yerde olduğu için sırası değiştirilmez. (22->22)
#### 6-) [2,6,16,18,22,27] --> Aynı işlem 6. en küçük sayı ve altıncı sıradaki veri için tekrarlanır. 27 sayısı zaten olması gereken yerde olduğu için sırası değiştirilmez. (27->27)
#### -Sonuç olarak sorting (sıralama) işlemi tamamlanır.
#### -Selection sort algoritmasında Big O Notion, (n*(n+1))/2 sonucundan elde edilen dominant faktöre göre O(n2) olarak bulunur.
#### ** Yukarı verilen worst, average ve worst case'e göre time complexity değerlerini yazınız.
#### - Worst case: Elimizdeki veri dizisinin mümkün olan en ters şekilde sıralanmasıdır. Best case durumunun tam tersidir. Bu durumda işlem sayısı (n'den 1'e kadar) maksimum olacaktır. Bundan dolayı da O(n^2) olur.
#### - Best case: Elimizdeki veri dizisinin sıralı bir şekilde olmasıdır. Bu durumda dizideki tüm elemanları tek tek sırasında mı diye kontrol edeceğimiz için time complexity yine O(n^2) olur.
#### - Average case: Elimizdeki veri dizisinin ortalama bir şekilde dağınık olmasıdır. Gerçek hayatta karşımıza çıkması en olası durumdur. Bu durumda dizideki tüm elemanları tek tek kontrol edilecek ve yanlış sırada olanlar düzeltilecektir. Yukarıda yapılan örnek gibi dominant faktörü n^2 olacaktır bundan dolayı time complexit yine O(n^2) olur.

#### ** Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
#### - Dizinin sıralanmış hali [2,6,16,18,22,27] şeklindedir. "18" sayısı ortalarda sayılabileceği için bu durum average case kapsamına girer.

#### B. [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız

#### 1-) [2,3,5,8,7,9,4,15,6] --> En küçük sayı bulunur ve ilk veri ile yer değiştirilir. (7->2)
#### 2-) [2,3,5,8,7,9,4,15,6] --> Daha sonra bu işlem 2. en küçük sayı ve ikinci sıradaki veri için tekrarlanır. Fakat burada 3 zaten olması gerektiği yerde olduğu için veri dizisi aynı şekilde kalır. (3->3)
#### 3-) [2,3,4,8,7,9,5,15,6] --> Aynı işlem 3. en küçük sayı ve üçüncü sıradaki veri için tekrarlanır. (5->4)
#### 4-) [2,3,4,5,7,9,8,15,6] --> Aynı işlem 4. en küçük sayı ve dördüncü sıradaki veri için tekrarlanır. (8->5)

