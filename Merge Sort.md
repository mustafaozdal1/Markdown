## PROJE 2
### SORU 1
[16,21,11,8,12,22] -> Merge Sort

Yandaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.
#### ÇÖZÜM
----
1. ADIM SPLIT
- Dizi: [16,21,11,8,12,22]

Dizi ikiye bölünür
- [16,21,11], [8,12,22]

Sol taraf tekrar ikiye bölünür
- [16,21,11] -> [16] ve [21,11]

[21,11] tekrar ikiye bölünür
  - [21,11] -> [21] ve [11]

Sağ taraf tekrar ikiye bölünür
  - [8,12,22] -> [8] ve [12,22]
  
[12,22] tekrar ikiye bölünür
- [12,22] -> [12] ve [22]
 
-----------

2. ADIM MERGE

[21] ve [11] birleştirilir
  - [21] + [11] -> [11,21]

[16] ile [11,21] birleştirilir
  - [16] + [11,21] -> [11,16,21]

[12] ve [22] birleştirilir
  - [12] + [22] -> [12,22]

[8] ile [12,22] birleştirilir
  - [8] + [12,22] -> [8,12,22]

[11,16,21] ve [8,12,22] birleştirilir
  - [11,16,21] + [8,12,22] -> [8,11,12,16,21,22]

----

- **Zaman Karmaşıklığı (Big-O):** Birleştirme Sıralaması her aşamada diziyi ikiye böler ve ardından bu parçaları birleştirir. Her bölme ve birleştirme işlemi O(n) zaman alır ve toplam log(n) bölme gerçekleştirilir. Bu nedenle, Birleştirme Sıralaması'nın zaman karmaşıklığı O(n log n)'dir.

- **Uzay Karmaşıklığı (Big-O):** Birleştirme Sıralaması genellikle ek bir dizi kullanarak birleştirir, bu nedenle uzay karmaşıklığı O(n)'dir.
