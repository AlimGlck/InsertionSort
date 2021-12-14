# InsertionSort
Insertion Sort Örneği

Proje 1
[22,27,16,2,18,6] -> Insertion Sort

	1.Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
	2.Big-O gösterimini yazınız.
	3.Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
	4.Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.


[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.


 # 1.Cevap

 En küçük elemanı bulup en başta bulunan eleman ile değiştiriyor. Yani 2 ile 22 yer değişiyor.
 
     1---->[2,27,16,22,18,6]
 
 Daha sonra ikinci en küçük elemanı bulup ikinci sırada bulunan eleman ile yer değiştiriyor. 

 Yani 6 ile 27 yer değişiyor.

     2---->[2,6,16,22,18,27]

 Daha sonra üçüncü en küçük elemanı buluyor. 

 Üçüncü en küçük eleman 16 ve zaten 3. sırada olduğu için ona dokunulmuyor.

     3---->[2,6,16,22,18,27]
 
 Daha sonra dördüncü en küçük elemanı buluyor yani 18 bunu da 4. sırada bulunan 22 ile yer değiştiriyor.

     4---->[2,6,16,18,22,27]

 Daha sonra beşinci en küçük elemanı buluyor yani 22 o da zaten 5 sırada olduğu için ona dokunulmuyor.

     5---->[2,6,16,18,22,27]

 Daha sonra altıncı en küçük elemanı buluyor yani son eleman 27 o da zaten son sırada olduğu için ona da dokunulmuyor.

 # 2.Cevap

     O(n^2)

 # 3.Cevap

    -Average case: Aradığımız sayının ortada olması

    -Worst case: Aradığımız sayının sonda olması

    -Best case: Aradığımız sayının dizinin en başında olması

 # 4.Cevap

     18 Sayısı Average case kapsamına girer

 
 # 5.Cevap
  
 En küçük elemanı bulup en başta bulunan eleman ile değiştiriyor.Yani 2 ile 7 yer değişiyor.
 
     1---->[2,3,5,8,7,9,4,15,6]

 Daha sonra en küçük ikinci elemanı buluyor yani 3. Oda zaten ikinci sırada olduğu için dokunulmuyor.

     2---->[2,3,5,8,7,9,4,15,6]

 Daha sonra üçüncü en küçük elemanı buluyor yani 4. Oda üçüncü sırada bulunan elemanan ile yani 5 ile yer değişiyor.

     3---->[2,3,4,8,7,9,5,15,6]

 Daha sonra dördüncü en küçük elemanı buluyor yani 5. Onu da dördüncü sırada bulunan 8 ile değiştiriyor.

     4---->[2,3,4,5,7,9,8,15,6]
