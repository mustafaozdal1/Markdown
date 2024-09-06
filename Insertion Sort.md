## PROJE 1
### SORU 1
[22,27,16,2,18,6] -> Insertion Sort, Yanda verilen dizinin sort türüne göre aşamalarını yazınız.
#### ÇÖZÜM
1- İlk eleman 22 olduğundan sıralı olarak kabul edilir. 

Dizi: [22,27,16,2,18,6]

2- 27, 22'den büyük olduğu için yerinde sabit kalır.

Dizi: [22,27,16,2,18,6]

3- 16, 27'den küçük, 22'den de küçük olduğundan, 16'yı en başa alırız.

Dizi: [16,22,27,2,18,6]

4- 2, 27'den, 22'den ve 16'dan küçük olduğundan, en başa alırız.

Dizi: [2,16,22,27,18,6]

5- 18, 27'den küçük, 22'den de küçük ancak 16'dan büyük olduğu için, 16 ve 22'nin 
arasına koyarız. 

Dizi: [2,16,18,22,27,6]

6- 6, 27'den, 22'den, 18'den ve 16'dan küçük olduğu için 2'den sonraya alırız.

Dizi: [2,6,16,18,22,27]

### SORU 2
Big-O gösterimini yazınız.
#### ÇÖZÜM

Insertion Sort’un en kötü durumu (worst case) zaman karmaşıklığı (O(n^2)), en iyi durumu (best case) zaman karmaşıklığı (O(n)), ve ortalama zaman karmaşıklığı (O(n^2)) olarak ifade edilir

### SORU 3
Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Average case: Aradığımız sayının ortada olması

Worst case: Aradığımız sayının sonda olması

Best case: Aradığımız sayının dizinin en başında olması.

#### ÇÖZÜM
18 sayısı sıralandıktan sonra ortalarda yer alıyor. Bu yüzden average case kapsamına girer.

### SORU 4
[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

#### ÇÖZÜM
1. Adım: En küçük eleman 2, başa alırız.
Dizi: [2,3,5,8,7,9,4,15,6]
1. Adım: Kalan elemanlar içinde en küçük 3, yerinde kalır. 
Dizi: [2,3,5,8,7,9,4,15,6]
1. Adım: Kalan elemanlar içinde en küçük 4, üçüncü sıraya alırız. 
Dizi: [2,3,4,8,7,9,5,15,6]
1. Adım: Kalan elemanlar içinde en küçük 5, dördüncü sıraya alırız. 
Dizi:[2,3,4,5,7,9,8,15,6]
