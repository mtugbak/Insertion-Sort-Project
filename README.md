# Insertion-Sort-Project
[22,27,16,2,18,6] -> Insertion Sort

1- Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.[22,27,16,2,18,6]
İlk aşamada en küçük sayı olan 2 yi en sola yazıyoruz. En solda yer alan 22 sayısı da 2'nin olduğu yere yazılır. [2,27,16,22,18,6]
İkinci olarak en küçük sayı 6 ve 27 ile yerleri değiştirilir. [2,6,16,22,18,27]
Üçüncü olarak 16 sayısı konumu aynı kalır yer değişmez. [2,6,16,22,18,27]
Dördüncü aşamada 22 ve 18 sayıları yer değiştirir. [2,6,16,18,22,27]

2- Big-O gösterimini yazınız.
[22,27,16,2,18,6] n işlem
[2,27,16,22,18,6] n-1 işlem
[2,6,16,22,18,27] n-2 işlem
[2,6,16,22,18,27] n-3 işlem
[2,6,16,18,22,27] n-4 işlem

O(n^2)=0(6^2)=O(36)

3-Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
4-Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
Sıralandıktan sonra 18 average case kapsamında olacaktır.

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

1- [2,3,5,8,7,9,4,15,6]
2- [2,3,4,8,7,9,5,15,6]
3- [2,3,4,5,7,9,8,15,6]
4- [2,3,4,5,6,9,8,15,7]



