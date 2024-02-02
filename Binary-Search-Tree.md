# Binary Search Tree

## Soru->
[7,5,1,8,3,6,0,9,4,2] 
dizisinin Binary Search Tree aşamalarını yazınız.
Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

### Binary Search Tree

```
 [7,5,1,8,3,6,0,9,4,2]
 Root 7 dir. Root'un sağında 8, solunda 5 bulunur.

            [7]
          /    \
        [5]     [8]
       /   \      \  
     [1]   [6]    [9]
     /  \    
   [0]  [3]
       /   \
     [2]   [4]


     Step1: Root olarak 7 alınır.
     Step1: 7 > 5, bu yüzden 5, 7'nin soluna yazılır.
     Step1: 7 > 1 ve 5 > 1, bu yüzden 5'in soluna yazılır.
     Step1: 7 < 8, bu yüzden 8, 7'nin sağına yazılır.
     Step1: 7 > 3, 5 > 3 ve 1 < 3, bu yüzden 1'in sağına yazılır.
     Step1: 7 > 6 ve 5 < 6, bu yüzden 5'in sağına yazılır.
     Step1: 7 > 0, 5 > 0 ve 1 > 0, bu yüzden 1'in soluna yazılır.
     Step1: 7 < 9 ve 8 < 9, bu yüzden 8'in sağına yazılır.
     Step1: 7 > 4, 5 > 4, 1 < 4 ve 3 < 4, bu yüzden 3'ün sağına yazılır.
     Step1: 7 > 2, 5 > 2, 1 < 2 ve 3 > 2, bu yüzden 3'ün soluna yazılır.
```

### Big-O Gösterimi

``` O(n logn) ```