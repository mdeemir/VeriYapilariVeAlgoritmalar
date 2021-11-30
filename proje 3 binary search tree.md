## **DİZİMİZ [7, 5, 1, 8, 3, 6, 0, 9, 4, 2]**
-------------
# Binary Search Tree aşamaları
Binary Search Tree oluşturulurken önce dizi içerisinden bir **root eleman** seçilir ve siğer elemanlar bu root elemandan **büyükse root elemanın sağına küçükse soluna yerleştirilir**. 

* İlk aşamada root eleman olarak bu dizede **6** yı seçelim.
* sonra sayıları tek tek 6 ya göre Binary Search Tree de konuşlandıralım.
- 7>6 olduğundan 7 6 nın sağına yerleştirilecek. 
- 5<6 olduğundan 5 6 nın soluna yerleştirilecek
- 1<6 olduğundan 1 6 nın solunda olacak  ve daha önce yerleştirdiğim 5 ten de küçük olduğundan 5 in de altına sola yerleştirilecek  
- 8>6 olduğundan 8 6 nın sağına yerleştirilecek ve daha önce yerleştirdiğim 7 den de büyük olduğundan 7 in de altına sağa yerleştirilecek
-  3<6 olduğundan 3 6 nın solunda olacak  ve daha önce yerleştirdiğim 5 ten  küçük ve 1 den de büyük olduğundan 1 in  altına sağa yerleştirilecek
- 0<6 olduğundan 0 6 nın solunda olacak  ve daha önce yerleştirdiğim 5 ve 1 den de küçük olduğundan 1 in de altına sola yerleştirilecek
- 9>6 olduğundan 9 6 nın sağına yerleştirilecek ve daha önce yerleştirdiğim 7 ve 8 den de büyük olduğundan 8 in de altına sağa yerleştirilecek
- 4<6 olduğundan 4 6 nın solunda olacak  ve daha önce yerleştirdiğim 5 ten  küçük ve 1 den de büyük olduğundan 1 in de sağına 1 in altındaki 3 ten de büyük olduğundan 3 ün altına  sağa yerleştirilecek
- 2<6 olduğundan 2 6 nın solunda olacak  ve daha önce yerleştirdiğim 5 ten  küçük ve 1 den de büyük olduğundan 1 in de sağına 1 in altındaki 3 ten de küçük olduğundan 3 ün altına  sola yerleştirilecek.

# Binary Search Tree görselimiz
                       6
                    5      7  
                 1             8
            0        3              9
                   2   4


