# proje-1  > insertion sort projesi

[22,27,16,2,18,6] -> Insertion Sort

1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

1.adım (n) [22,27,16,2,18,6] 

16 sayısı, 27 den küçüktür. 16 ile 27 yer değiştirir.

2.adım (n-1) [22,16,27,2,18,6]

16 sayısı, 22 den küçüktür. 16 ile 22 yer değiştirir.

3.adım (n-2) [16,22,27,2,18,6] 

2 sayısı 27 den küçüktür yer değiştirir, 22 den küçüktür yer değiştirir, 16 dan küçüktür yer değişitirir.

4.adım (n-3) [2,16,22,27,18,6] 

18 sayısı 27 den küçüktür yer değiştirir, 22 den küçüktür yer değiştirir.

5.adım (n-4) [2,16,18,22,27,6]

6 sayısı 27 den, 22 den, 18 den, 16 dan küçüktür sırayla bu sayılardan yer değiştirir.

6.adım (n-5) [2,6,16,18,22,27]

2. Big-O gösterimini yazınız.

 Big-o (n^2) dir.
 
 3. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
 
 Average case: 16 ve 18 
 
 worst case: 27
 
 best case: 2

4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

18 sayısı average case kapsamına girer.


[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

1.adım > [7,3,5,8,2,9,4,15,6]

2.adım > [3,7,5,8,2,9,4,15,6]

3.adım > [3,5,7,8,2,9,4,15,6]

4.adım > [3,5,7,2,8,9,4,15,6]


www.patika.dev

