# INSERTION SORT
![image](img/insertionsort.png)
## [22,27,16,2,18,6] -> Insertion Sort

### 1. Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.
```
- [22,27,16,2,18,6]
- [16,22,27,2,18,6]
- [2,16,22,27,18,6]
- [2,16,18,22,27,6]
- [2,6,16,18,22,27]
```

### 2. Big-O gösterimini yazınız.
```
- n+(n-1)+(n-2)+(n-3)+...+1
- = n * (n+1) / 2
- = (n^2 + n) / 2
- Bu değerin Big O değeri O(n^2) dir.
```

![image](img/Insertion_sort.gif)

### 3. Time Complexity
```
- Average Case: Bu örnekte ortalarda olan değerlerden en ortada olan 16 değeri örneklenebilir
Big O gösterimi ise O(n^2)'dir. 

- Worst Case: Bu örnekteki en kötü senaryoda 6'dır.
Big O gösterimi ise O(n^2)'dir.

- Best Case: Bu örnekte en iyi senaryo 22'dir.
Big O gösterimi ise O(n)'dir.
```
### 4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
```
- 18 sayısı Average Case kapsamına girer.
```

![image](img/Insertion-sort-example-300px.gif)

## [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
```
- [7,3,5,8,2,9,4,15,6]
- [3,7,5,8,2,9,4,15,6]
- [3,5,7,8,2,9,4,15,6]
- [2,3,5,7,8,9,4,15,6]
- [2,3,4,5,7,8,9,15,6]
```

