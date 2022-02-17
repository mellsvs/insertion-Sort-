## insertion-Sort-
##Soru1

[22,27,16,2,18,6]  verilen dizinin sort türüne göre aşamalarını yazınız.

##cevap1

[2,27,16,22,18,6] 
[2,6,16,22,18,27]
[2,6,16,22,18,27] 
[2,6,16,18,22,27] 
[2,6,16,18,22,27]

n boyutlu dizi içindeki elemanlardan en küçük olan başa yazılır.Yeri sabitlenir.Geriye kalan (n-1) eleman içinde de en küçük olan
başa yazılarak devam edilir. Yapılan toplam işlem sayısı n+(n-1)+(n-2)+..1 =(n(n+1))/2 ile bulunur
hafızada extra space kaplamaz.Katsayılar önemli değildir domine eden değer big o notation a yazılır

##soru2

Big-O gösterimini yazınız.


##cevap2

Big o notation da yapılacak olan toplam işlem sayısının input size ile nasıl scale edileceğine bakılır.Algoritmaların performans
ve time complexini kıyaslamak için kullanılır.
Yukarıda ki dizinin big o gösterimi = o(n^2) ile gösterilir.

##soru3

Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

##cevap3

Time Complexity:
Average case: Aradığımız sayının ortada olması,
Worst case: Aradığımız sayının sonda olması,
Best case: Aradığımız sayının dizinin en başında olması.
[10,13,23,27,65] 
18 sayısı ortada olduğu için average case kapsamına girer.Beklenilen durumdur.

##soru4

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız

##cevap4

[2,3,5,8,7,9,4,15,6] ---> n.adım
[2,3,5,8,7,9,4,15,6] ---> (n-1).adım
[2,3,4,8,7,9,5,15,6] ---> (n-2).adım
[2,3,4,5,7,9,8,15,6] ---> (n-3).adım
 
 ##Meltem savaş
