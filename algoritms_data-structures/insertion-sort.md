# Insertion Sort Projesi

## 1.Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

```
[22, 27, 16, 2, 18, 6] - n
[2, 27, 16,22, 18, 6] - n-1
[2,6, 16, 22, 18, 27] - n-2
[2,6, 16,18, 22, 27] - n-3

```

## 2. Big-O gösterimini yazınız.

---

```
(n*(n+1)/2) = (n^2 + n)/2 = n^2/2 + n/2

O(n^2)

```

## 3. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

---

## 4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer?

---

```
 - Average Case
```

## [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

```
1. 22|,27,16,2,18,6
2. 22,27|,16,2,18,6
3. 22,16,27|,2,18,6
4. 16,22,27|,2,18,6
5. 16,22,2,27|,18,6
6. 16,2,22,27|,18,6
7. 2,16,22,27|,18,6
8. 2,16,22,18,27|,6
9. 2,16,18,22,27|,6
10. 2,16,18,22,6,27|
11. 2,16,18,6,22,27|
12. 2,16,6,18,22,27|
13. 2,6,16,18,22,27|

```

[patika.dev](https://app.patika.dev/)
