# Insertion-Sort-Projesi

[22,27,16,2,18,6] -> Insertion Sort

## Yukarı verilen dizinin sort türüne göre aşamaları
 1- [2,27,16,22,18,6]
 2- [2,6,16,22,18,27]
 3- [2,6,16,22,18,27]
 4- [2,6,16,18,22,27]

## Big-O gösterimi (???)
[2,6,16] , [18,22,27]
[2,6],[16] , [18,22],[27]
[2],[6],[16], [18],[22],[27]

 ## Time Complexity
 1-Average case : aradığımız sayı 16 olsun. sayının tam ortada olması durumudur.
     [2,6,16,18,22,27]
     
 2-Worst case : aradığımız sayı 27 olsun. aradığımız sayı en sondaysa bu en kötü durumdur.
     [2,6,16,18,22,27]
     
 3-Best case: aradığımız sayı 2 olsun. sayının ilk sırada olması durumudur.
     [2,6,16,18,22,27]
     
 ## Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? 
     3.case çünkü indexleme 0'dan başlar
