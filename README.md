SELECTİON SORT

[22,27,16,2,18,6] --> Selection Sort aşamalarını yazınız.


1-) En küçük eleman 2'dir. En soldaki eleman olan 22 ile yerini değiştiririz.
[2,27,16,22,18,6]

2-) Sonraki en küçük eleman 6'dır. 6 ile soldaki ikinci eleman yer değiştirir.
[2,6,16,22,18,27]

3-) Üçüncü en küçük eleman olması gerektiği yerdedir. Değişiklik olmaz.
[2,6,16,22,18,27]

4-) Dördüncü en küçük eleman 18'dir.  Onu da 22 ile yer değiştirdik.
[2,6,16,18,22,27]


Sıralama işlemimiz bitmiş oldu. 


Big-O gösterimini yazınız.
(n-1)+(n-2)+(n-3)+......+1=n(n-1)/2= (n^2-n)/2

O(n^2)'dir.


Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.


18 ortada olduğu için average case'tir.

------------------------------------------------------
[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız

1-) [2,3,5,8,7,9,4,15,6]

2-) [2,3,5,8,7,9,4,15,6]

3-) [2,3,4,8,7,9,5,15,6]

4-) [2,3,4,5,7,9,8,15,6]

5-) [2,3,4,5,6,9,8,15,7]

6-) [2,3,4,5,6,7,8,15,9]

7-) [2,3,4,5,6,7,8,9,15]
# selection_sort
