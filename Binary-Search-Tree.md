## PROJE 3
### SORU 1
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

---
#### ÇÖZÜM
Binary Search Tree Oluşturma Aşamaları:
- Birinci Eleman (7): Birinci eleman 7 olduğundan, bu değer kök olarak alınır.
Kök = 7 - İkinci Eleman (5): 5, 7'den küçüktür, bu nedenle 7'nin çözümüne eklenir.
5, 7'nin çözümünde bulunur.
- Üçüncü Eleman (1): 1, 7' boyutlarından 5'ten büyüktür. Bu nedenle, 5'in çözümüne eklenir. 1, 5'in solunda bulunur.
- Dördüncü Eleman (8): 8, 7'den büyüktür, bu nedenle 7'nin sağına eklenir. 8, 7'nin sağında bulunur.
- Beşinci Eleman (3): 3, 7'den küçüktür, 5'ten küçüktür, ancak 1'den büyüktür. Bu nedenle, 1'in sağına ekleyin. 3, 1'in sağında bulunur.
- Altıncı Eleman (6): 6, 7'den büyüktür, 5'ten büyüktür. Bu nedenle, 5'in sağına ekleyin. 6, 5'in sağındadır.
- Yedinci Eleman (0): 0, 7'den büyüktür, 5'ten büyüktür ve 1'den küçüktür. Bu nedenle, 1'in çözümüne ekleyin. 0, 1'in çözümüne eklenir.
- Sekizinci Eleman (9): 9, 7'den ve 8'den büyüktür. Bu nedenle, 8'in sağına ekleyin. 9, 8'in sağındadır.
- Dokuzuncu Eleman (4): 4, 7'den, 5'ten, 1'den ve 3'ten büyüktür. Bu nedenle, 3'ün sağına ekleyin. 4, 3'ün sağındadır.
- Onuncu Eleman (2): 2, 7'den, 5'ten, 1'den ve 3'ten küçüktür. Bu nedenle, 3'ün çözümüne ekleyin. 2, 3'ün solundadır.
```
        7
       / \
      5   8
     / \   \
    1   6   9
   / \
  0   3
     / \
    2   4
```