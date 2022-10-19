# veri_Yapilari_Ve_Algoritma

## Insertion Sort Projesi

#### A. [22, 27, 16, 2, 18, 6] 

####	** Yukarı verilen dizinin sort türüne göre aşamalarını ve Big-O gösterimini yazınız.
#### 0-) [22*, 27, 16, 2, 18, 6] --> İlk terim kontrol edilir. (22)
#### 1-) [22, 27*, 16, 2, 18, 6] --> İkinci terim seçilir, diğer terimle kıyaslanır ve terimler sıralanır.  (22-27)
#### 2-) [16, 22, 27*, 2, 18, 6] --> Üçüncü terim  seçilir, diğer 2 terimle sırayla kıyaslanır ve terimler sıralanır. (16-22-27)
#### 3-) [2, 16, 22, 27*, 18, 6] --> Dördüncü terim  seçilir, diğer 3 terimle sırayla kıyaslanır ve terimler sıralanır. (2-16-22-27)
#### 4-) [2, 16, 18, 22, 27*, 6] --> Beşinci terim  seçilir, diğer 4 terimle sırayla kıyaslanır ve terimler sıralanır. (2-16-18-22-27)
#### 5-) [2, 6, 16, 18, 22, 27*] --> Beşinci terim  seçilir, diğer 5 terimle sırayla kıyaslanır ve terimler sıralanır. (2-6-16-18-22-27)
#### -Sonuç olarak sorting (sıralama) işlemi tamamlanır.
#### -Insertion sort algoritmasında Big O Notion, (n*(n+1))/2 sonucundan elde edilen dominant faktöre göre O(n2) olarak bulunur.
#### ** Yukarı verilen worst, average ve worst case'e göre time complexity değerlerini yazınız.
#### - Worst case: Elimizdeki veri dizisinin mümkün olan en ters şekilde sıralanmasıdır. Best case durumunun tam tersidir. Bu durumda işlem sayısı (n'den 1'e kadar) maksimum olacaktır. Bundan dolayı da O(n^2) olur.
#### - Best case: Elimizdeki veri dizisinin sıralı bir şekilde olmasıdır. Bu durumda dizideki tüm elemanları sırayla olmaları gereken yerde mi diye kontrol etmemiz gerekir. Dizi sıralı olduğu için n sayıda işlem yapılır ve yer değiştirme işlemi yapılmaz. Bundan dolayı O(n) olur.
#### - Average case: Elimizdeki veri dizisinin ortalama bir şekilde dağınık olmasıdır. Gerçek hayatta karşımıza çıkması en olası durumdur. Bu durumda dizideki tüm elemanları tek tek kontrol edilecek ve yanlış sırada olanlar düzeltilecektir. Yukarıda yapılan örnek gibi dominant faktörü n^2 olacaktır bundan dolayı time complexit yine O(n^2) olur.

#### ** Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
#### - Dizinin sıralanmış hali [2, 6, 16 , 18, 22, 27] şeklindedir. "18" sayısı ortalarda sayılabileceği için bu durum average case kapsamına girer.

#### B. [7, 3, 5, 8, 2, 9, 4, 15, 6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız
#### 0-) [7*, 3, 5, 8, 2, 9, 4, 15, 6] --> İlk terim seçilir.
#### 1-) [3, 7*, 5, 8, 2, 9, 4, 15, 6] --> İkinci terim seçilir, diğer terimle kıyaslanır ve terimler sıralanır. (3-7)
#### 2-) [3, 5, 7*, 8, 2, 9, 4, 15, 6] --> Üçüncü terim  seçilir, diğer 2 terimle sırayla kıyaslanır ve terimler sıralanır. (3-5-7)
#### 3-) [3, 5, 7, 8*, 2, 9, 4, 15, 6] --> Dördüncü terim  seçilir, diğer 3 terimle sırayla kıyaslanır ve terimler sıralanır. "8" olması gereken indexte olduğu için sırası değiştirilmez. (3-5-7-8)
#### 4-) [2, 3, 5, 7, 8*, 9, 4, 15, 6] --> Beşinci terim  seçilir, diğer 4 terimle sırayla kıyaslanır ve terimler sıralanır. (2-3-5-7-8)
#### İlk 4 adımın sonunda elde edeceğimiz veri seti şu şekilde olur: [2, 3, 5, 7, 8*, 9, 4, 15, 6].

