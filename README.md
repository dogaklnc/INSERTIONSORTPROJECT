# INSERTIONSORTPROJECT
KODLUYORUZ proje 1

1. Madde
Insertion Sort yani araya ekleme sıralama algoritması ikinci elemandan başlayarak elemanın kendinden önceki elemanlarla karşılaştırılması suretiyle büyük elemanların dizide sağa doğru kaydırılması işlemlerini tekrar eder.
[22,27,16,2,18,6]

[2,27,16,22,18,6] -> 2 ile 22 yer değiştiriyor.
[2,6,16,22,18,27] -> 6 ile 27 yer değiştiriyor.
[2,6,16,22,18,27] -> 3. sıradaki eleman en küçük. Dokunmadan devam et.
[2,6,16,18,22,27] -> 18 ile 22 yer değiştiriyor ve sonlanıyor.
[2,6,16,18,22,27] -> 5. sıradaki eleman en küçük. Dokunmadan devam et.
[2,6,16,18,22,27] -> 6. sıradaki eleman en büyük ve bitir.

2.Madde
Big-O gösterimini yazınız.
O(n²) = O(6²) = O(36)

3. Madde
"Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması."

4.Madde
18 sayısı ortada olacağından Average Case kapsamındadır.

5.Madde
2,3,5,8,7,9,4,15,6] -> 7 ile 2 yer değiştiriyor.
[2,3,5,8,7,9,4,15,6] -> 2. sıradaki 3 rakamı en küçük, dokunmadan devam et.
[2,3,4,8,7,9,5,15,6] -> 5 ile 4 yer değiştiriyor.
[2,3,4,5,7,9,8,15,6] -> 8 ile 5 yer değiştiriyor.
