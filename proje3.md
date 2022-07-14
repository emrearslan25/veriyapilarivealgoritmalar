# Proje 3

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.
<br> <br>
Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

# Binary-Search-Tree

```
    Soldan sağa okumaya başladığımız için root *7* oluyor.
    
    5, 7'den küçük olduğu için 7'nin soluna yazılıyor.
    
    1, hem 7'den hem de 5'den küçük olduğu için 5'in soluna yazılıyor.
    
    8, 7'den büyük olduğu için 7'nin sağına yazılıyor.
    
    3, 7 ve 5'den küçük 1'den büyük olduğu için 1'in sağına yazılıyor.
    
    6, 7'den küçük 5'den büyük olduğu için 5'in sağına yazılıyor.
    
    0, 7,5 ve 1'den küçük olduğu için 1'in soluna yazılıyor.
    
    9, 7 ve 8'den büyük olduğu için 8'in sağına yazılıyor.
    
    4, 7 ve 5'den küçük 1 ve 3'den büyük olduğu için 3'ün sağına yazılıyor.
    
    2, 7 ve 5'den küçük 1'den büyük 3'den küçük olduğu için 3'ün soluna yazılıyor.
    
    
    
```

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

[Patika](www.patika.dev)
