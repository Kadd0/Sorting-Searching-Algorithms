# Proje 1

**[22,27,16,2,18,6] -> Insertion Sort**

1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

2. Big-O gösterimini yazınız.

3. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.



**[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.**

<hr>

## 1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
```
1. Aşama

[22,27,16,2,18,6]

2. Aşama

[2,27,16,22,18,6]

3. Aşama

[2,6,16,22,18,27]

4. Aşama 

[2,6,16,22,18,27]

5. Aşama

[2,6,16,18,22,27] 
```     

## 2. Big-O gösterimini yazınız.

```
Worst Case: O(n^2)

Average Case: O(n^2)

Best Case: O(n)
```

## 3. Time Complexity. 
```
Worst Case:

[27,22,18,16,6,2]

Average Case:

[6,16,22,2,18,27]

Best Case:

[2,6,16,18,22,27]
```

## 4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? 
 **Average Case**


 <hr>

 ## [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

 ```
1. Aşama

[7,3,5,8,2,9,4,15,6]

2. Aşama

[2,3,5,8,7,9,4,15,6]

3. Aşama

[2,3,4,8,7,9,5,15,6]

4. Aşama

[2,3,4,5,7,9,8,15,6]