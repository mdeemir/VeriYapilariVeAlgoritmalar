# VeriYapilariVeAlgoritmalar
# DİZiMİZ [22,27,16,2,18,6]
**1. İnsertion sort türüne göre aşamaları**
* [2,27,16,22,18,6] ilk aşamada en küçük sayı olan 2 yi buldu ve en baştaki 22 ile yer değiştirdi
* [2,6,16,22,18,27] ikinci aşamada kalanlar arasında en küçük sayı olan 6 yi buldu ve en baştaki 27 ile yer değiştirdi
* [2,6,16,22,18,27] üçüncü aşamada kalanlar arasında en küçük sayı olan 16 yi buldu en başta olduğu için atladı
* [2,6,16,18,22,27] dördüncü aşamada kalanlar arasında en küçük sayı olan 18 yi buldu ve 22 ile yer değiştirdi
* [2,6,16,18,22,27] beşinci aşamada kalanlar arasında en küçük sayı olan 22 yi buldu en başta olduğu için atladı ve sıralama bitti

**2. Bİg-O gösterimi**
 insertion sort da big-o gösterimi n+(n-1)+(n-2)+(n-3) ….+1 = [n.(n+1)]/ 2 = n kare/ 2 + n/2 burada dominant faktör 1/2.[n kare] oldugundan ve katsayılar big o da gösterilmediğinden O(n kare) dir. 

**3. ve 4.** dizi sıralandıktan [2,6,16,18,22,27] sonra 18 sayısı ortada yer aldığından time complexity average case kapsamına girer.  