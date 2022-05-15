# veri-yapilari-odev-1

Veri yapıları ve algoritmalar 1. ödevidir.

## Çözüm

```
[22,27,16,2,18,6]
1. adım: En küçük sayı 2'dir, 2 ile 22'yi swap ediyoruz. [2,27,16,22,18,6]
2. adım: İkinci küçük sayı 6. 6 ile 27'yi swap ediyoruz. [2,6,16,22,18,27]
3. adım: Üçüncü küçük sayı 16. 16'nın yeri sabit kalıyor. [2,6,16,22,18,27]
4. adım: Dördüncü küçük sayı 18. 18 ve 22'yi swap ediyoruz. [2,6,16,18,22,27]
5. adım: Beşinci küçük sayı 22. Yeri sabit kalıyor.
Dizinin sıralanmış hali: [2,6,16,18,22,27].
```

```
Algoritma karmaşıklığı: O(n^2).
Best case: O(1).
Worst case: O(n).
Average case: O(n).
Dizi sıralandıktan sonra 18 sayısı yaklaşık olarak average case kapsamına girer.
```

```
[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
1. adım: [2,3,5,8,7,9,4,15,6]
2. adım: [2,3,5,8,7,9,4,15,6]
3. adım: [2,3,4,8,7,9,5,15,6]
4. adım: [2,3,4,5,7,9,8,15,6]
```

