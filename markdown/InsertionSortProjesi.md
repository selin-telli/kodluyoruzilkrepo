# Insertion Sort Projesi

## [22,27,16,2,18,6] -> Insertion Sort

<br>

### 1) Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.

<br>

```

[22,27,16,2,18,6]
[2,27,16,22,18,6]
[2,6,16,22,18,27]
[2,6,16,18,22,27]

```

<br>

### 2) Big-O gösterimini yazınız.

<br>

```

i)     n + (n-1) + (n-2) + (n-3) + ... + 1 = ( n * (n+1) ) / 2
ii)  ( n * (n+1) ) / 2 = ( n^2 + n ) / 2
iii) ( n^2 + n ) / 2 ~ n^2
iv) O(n^2)

```

<br>

### 3) Time Complexity

<br>

```

* Average case: Aradığımız sayının dizinin ortasında olması
* Worst case: Aradığımız sayının dizinin en sonunda olması
* Best case: Aradığımız sayının dizinin en başında olması

```

<br>

### 4) Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

<br>

```

18 sayısı, 6 elemanlı dizinin ilk ve son elemanı değildir.
Bu yüzden Best Case ve Worst Case kapsamına girmez.
18 sayısı, 6 elemanlı dizinin ortasında yer alır.
Bu yüzden Average Case kapsamına girer.

```

<br>

### 5) [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

<br>

```

[7,3,5,8,2,9,4,15,6]
--------------------
[2,3,5,8,7,9,4,15,6]
[2,3,4,8,7,9,5,15,6]
[2,3,4,5,7,9,8,15,6]
[2,3,4,5,6,9,8,15,7]

```
