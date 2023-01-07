[22,27,16,2,18,6] - Insertion Sort

[22,27,16,2,18,6] - 22 mi küçük 27 mi? Küçük olan sola kalır.


[22,16,27,2,18,6] - 27 mi küçük 16 mi? Küçük olan 16 sola geçer.


[16,22,27,2,18,6] - 22 mi küçük 16 mi? Küçük olan 16 sola geçer.


[16,22,2,27,18,6] - 27 mi küçük 2 mi? Küçük olan 2 sola geçer.


[16,2,22,27,18,6] - 22 mi küçük 2 mi? Küçük olan 2 sola geçer.


[2,16,22,27,18,6] - 16 mi küçük 2 mi? Küçük olan 2 sola geçer.


[2,16,22,18,27,6] - 27 mi küçük 18 mi? Küçük olan 18 sola geçer.


[2,16,18,22,27,6] - 22 mi küçük 18 mi? Küçük olan 18 sola geçer.


[2,16,18,22,6,27] - 27 mi küçük 6 mi? Küçük olan 6 sola geçer.


[2,16,18,6,22,27] - 22 mi küçük 6 mi? Küçük olan 6 sola geçer.


[2,16,6,18,22,27] - 18 mi küçük 6 mi? Küçük olan 6 sola geçer.


[2,6,16,18,22,27] - 16 mi küçük 6 mi? Küçük olan 6 sola geçer.


En küçük sayıyı en başa almak için n sayıda işlem yapılır. İkinci sayıyı getirmek için n-1, üçüncü sayıyı getirmek için n-2...n-1

Toplam işlem sayısı n*(n+1)/2 = (n²+n)/2

BigO gösterimi O(n²) 'dir.

Dizi sıralandıktan sonra 18 tam ortada yer aldığı için Average Case olur.

[7,3,5,8,2,9,4,15,6] - Selection Sort 

Listenin ilk eleman ile listedeki en küçük elemanı bulup karşılaştır. Bu adımları listenin ikinci elemanından başlayarak yinele.

Bu durumda ilk eleman 7, en küçük değerli eleman 2' dir. Bunlar yer değiştirir.

[2,3,5,8,7,9,4,15,6] - 3 ikinci en küçük değerli sayı olduğu için yerinde kalır.

[2,3,4,8,7,9,5,15,6] -  Sıralamadan sonraki ilk eleman 5 ve en küçük değer 4 yer değiştirir.

[2,3,4,5,7,9,8,15,6] -  Sıralamadan sonraki ilk eleman 8 ve en küçük değer 5 yer değiştirir.

[2,3,4,5,6,9,8,15,7] -  Sıralamadan sonraki ilk eleman 7 ve en küçük değer 6 yer değiştirir.

[2,3,4,5,6,7,8,15,9] -  Sıralamadan sonraki ilk eleman 9 ve en küçük değer 7 yer değiştirir.

[2,3,4,5,6,7,8,15,9] -  Sıralamadan sonraki ilk eleman 8 geriye kalan elemanlardan olduğu için yerinde kalır.

[2,3,4,5,6,7,8,9,15] -  Sıralamadan sonraki ilk eleman 15 ve en küçük değer 9 yer değiştirir.

[2,3,4,5,6,7,8,9,15] -  Listenin sıralanmış son hali.

patika.dev