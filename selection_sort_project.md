

## Insertion Sort
- Array =  [22, 27, 16, 2, 18, 6]

##### Question 1 : Yukarı verilen dizinin sort  türüne göre aşamalarını yazınız.

- Step 1 = [16, 22, 27, 2, 18, 6]
- Step 2 = [2, 16, 22, 27, 18, 6]
- Step 3 = [2, 16, 18, 22, 27, 6]
- Step 4 = [2, 6, 16, 18, 22, 27]

##### Question 2 : Big-O gösterimini yazınız.

- O(n) (Best case)
- O(n^2) (worst case and average case)

##### Question 3 : Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

-Average case kapsamına girer, çünkü 18 sayısı sıralanmış arrayin tam ortasındadır.

## Selection Sort
- Array =  [7, 3, 5, 8, 2, 9, 4, 15, 6] 

##### Question 1 : [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

- Step 1 = [2, 3, 5, 8, 7, 9, 4, 15, 6]
> Index 0 için 2 ile 7 yer değiştirir. 
- Step 2 = [2, 3, 5, 8, 7, 9, 4, 15, 6]
> Index 1 de yer alan 3 sayısı 2 den sonraki en küçük olduğu için bir değişiklik olmaz. 
- Step 3 = [2, 3, 4, 8, 7, 9, 5, 15, 6]
> Index 2 için 5 ile tüm sayılar karşılaştırılır ve 4 ile 5 yer değişir.
- Step 4 = [2, 3, 4, 5, 7, 9, 8, 15, 6]
> Index 3 için 8 ile tüm sayılar karşılaştırlır ve 5 ile 8 yer değişir.
