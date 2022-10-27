# Patika-Insertion-Sort-Projesi-Patika.dev-https-www.patika.dev-tr-PatikaDev_Proje1
# [22,27,16,2,18,6] -> Insertion Sort #
1- Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
2- Big-O gösterimini yazınız.
3- Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
4- Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
5- [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

1- Insertion Sort Aşamaları:
[22, 27, 16, 2, 18, 6] . . . n

[16, 22, 27, 2, 18, 6] . . . n-1

[2, 16, 22, 27, 18, 6] . . . n-2

[2, 16, 18, 22, 27, 6] . . . n-3

[2, 6, 16, 18, 22, 27] . . . 1

2- Big-O gösterimini yazınız.
(n*(n-1)/2)
(n^2+n /2)
O(n^2)

3- Time Complexity:

Worst Case: O(n²) = n+(n-1)+(n-2)....+1

Average Case: O(n²)

Best Case: O(n)

Time Complexity Worst Case: [27,22,18,16,6,2]

Best Case: [2,6,16,18,22,27]

Avarage Case: [2,6,16,18,22,27]

4- [2,6,16,18,22,27] . . . Dizi sıralandıktan sonra 18 sayısı Avarage Case kapsamına girer.

5- [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

[2|,3,5,8,7,9,4,15,6]

[2,3|,5,8,7,9,4,15,6]

[2,3,4|,8,7,9,5,15,6]

[2,3,4,5|,7,9,8,15,6]

www.patika.dev







