# Insertion Sort and Selection Sort

## Soru 1->
``` [22,27,16,2,18,6] ``` 
- dizisinin Insertion Sort türüne göre aşamalarını yazınız. 
- Big-O gösterimini yapınız. 
- Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız
1. Average case: Aradığımız sayının ortada olması
2. Worst case: Aradığımız sayının sonda olması
3. Best case: Aradığımız sayının dizinin en başında olması.

### Insertion Sort:
```
Step1: [22,27,16,2,18,6]    // 22, 27'den küçük olduğu için değişiklik yapılmadı
Step2: [22,16,27,2,18,6]    // 27 ile 16 yer değiştirdi
Step3: [16,22,27,2,18,6]    // 16 ile 22 yer değiştirdi
Step4: [16,22,2,27,18,6]    // 2 ile 27  yer değiştirdi
Step5: [16,2,22,27,18,6]    // 2 ile 22  yer değiştirdi
Step6: [2,16,22,27,18,6]    // 2 ile 16  yer değiştirdi
Step7: [2,16,22,18,27,6]    // 18 ile 27  yer değiştirdi
Step8: [2,16,18,22,27,6]    // 18 ile 22  yer değiştirdi
Step9: [2,16,18,22,6,27]    // 6 ile 27  yer değiştirdi
Step10: [2,16,18,6,22,27]   // 6 ile 22  yer değiştirdi
Step11: [2,16,6,18,22,27]   // 6 ile 18  yer değiştirdi
Step12: [2,6,16,18,22,27]   // 6 ile 16  yer değiştirdi

```
### Big-O gösterimi ->
` O(n^2) `


## Soru 2->
``` [7,3,5,8,2,9,4,15,6] ``` dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

```
[7,3,5,8,2,9,4,15,6]
Step1: [2,3,5,8,7,9,4,15,6] // 7 ile 2 yer değiştirdi
Step2: [2,3,4,8,7,9,5,15,6] // 3'den daha küçük olmadığı için aynı şekilde bırakıldı. 4 ile 5 yer değiştirildi
Step3: [2,3,4,5,7,9,8,15,6] // 5 ile 8 yer değiştirildi
Step4: [2,3,4,5,6,9,8,15,7] // 6 ile 7 yer değiştirildi

``` 