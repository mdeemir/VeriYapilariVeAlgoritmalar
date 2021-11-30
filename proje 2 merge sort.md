## **DİZİMİZ [16,21,11,8,12,22]**

Merge sort bir diziyi her adımda parça parça ayırıp tek eleman kalıncaya kadar böler. Böldükten sonra birleştirken sıralama yapar.
# **Aşamaları**
1. aşamada dizi [16,21,11] ve [8,12,22] olarak iki parçaya bölünür

2. aşamada birinci parça [16] ve [21,11], ikinci parça ise [8] ve[12,22] parçalarına bölünür

3. asamada [21,11] parçası  [21],[11]; [12,22] parçası da [12],[22] parçalarına bölünür. böylece dizideki bütün elmanlar tek kalana kaldığından bölme işlemi sonlandırılır

4. aşamada parçalanan yapılar tekrar sıralanarak birleştirilir .
* ilk bölmenin sonucunda elde edilen birinci parcanın alt parçaları önce [11,21] ve [16] sonra ise [11,16,21] şeklinde birleştirilir
* ilk bölmenin sonucunda elde edilen ikinci parcanın alt parçaları [8,12,22]şeklinde birleştirilir

* son olarak kendi içinde sıralanan [11,16,21] ve [8,12,22] parçaları [8,11,12,16,21,22] şeklinde sıralanır ve işlem sonuçlanır. 

# **Big-O gösterimi**
Dizi önce ikiye bölünerek 2 adet 3 lü dizi elde edildi. sonra bu 3iü diziler de bölündü ve 1 li ve 2 li ikişer tane dizi elde dildi. son aşamada 2 li diziler de ikiye bölündü ve bütün elemanlar tek kalana kadar bölme işlemi devam etti. 

Big-O gösteriminde n tane elaman her seferinde değişmediğinden O (n) , bu her seferinde yarıya bölünerek devam ettiği için 2 üzeri x = n yani x=logn kez yapılan bölmede tek elemana düşüyor. Bu yüzden merge sort da Big-O gösterimi logn* O(n) = **O (nlogn)**   dur.