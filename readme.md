# Insertion_Sort Projesi

## Problem

[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Average case: Aradığımız sayının ortada olması Worst case: Aradığımız sayının sonda olması Best case: Aradığımız sayının dizinin en başında olması. .

[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

## Çözüm

### 1) İlk olarak [22,27,16,2,18,6] dizisini insertion sort a göre sıralayalım.

Insertion sort a göre sıralama işlemi dizinin küçükten büyüğe sıralanmasıdır. Dizimizin en küçük elemanını ve ilk elemanını bulup yerini değiştiririz ve yaptığımız işlemi hafızada tutarız böylelikle yaptığımız sıralamaya dokunmadan sıralanmamış elemanlarla aynı işlemi tekrarlarız .Eğer ilk eleman ,en küçük eleman ise işleme 2.elemandan devam ederiz. Dizi tamamen küçükten büyüğe sıralı olana dek işlem dedvam eder.

[22,27,16,2,18,6] -> [2,27,16,22,18,6]
[2,27,16,22,18,6] -> [2,6,16,22,18,27]
[2,6,16,22,18,27] -> [2,6,16,22,18,27]
[2,6,16,22,18,27] -> [2,6,16,18,22,27]

### 2) Big-O gösterimini yazınız.

Big O notation -->O(n^2)

### 3) Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Avarage Case

### 4) [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

[7,3,5,8,2,9,4,15,6] -> [2,3,5,8,7,9,4,15,6]
[2,3,5,8,7,9,4,15,6] -> [2,3,5,8,7,9,4,15,6]
[2,3,5,8,7,9,4,15,6] -> [2,3,4,8,7,9,5,15,6]
[2,3,4,8,7,9,5,15,6] -> [2,3,4,5,7,9,8,15,6]