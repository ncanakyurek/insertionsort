# Veri yapılar ve Algoritmalar
## Insertion Sort Projesi  - roje 1

### [22,27,16,2,18,6] -> Insertion Sort

### Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

1-     [22,27,16,2,18,6]   n <br>
2-     [2,27,16,22,18,6]   n-1 <br>
3-     [2,6,16,22,18,27]   n-2 <br>
4-     [2,6,16,18,22,27]   1   <br>
  


### Big-O gösterimini yazınız.

  ==>  n+ (n-1)+n(n-2)...+1 <br>
  ==>  (n.(n+1)/2) <br>
  ==>  (n² + n) / 2 <br>
  ==>  Big-O (n²) <br>

### Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Average case: Aradığımız sayının ortada olması <br>
Worst case: Aradığımız sayının sonda olması <br> 
Best case: Aradığımız sayının dizinin en başında olması. <br>

  Dizi sıralaması  [2,6,16,18,22,27] şeklinde olur.<br>
  Aradığımız 18 sayısı sıralamanın ortasında yer alan eleman olması nedeniyle Avarage Case kapsamına girer.<br>





### [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız. <br>


  
 1-   [7, 3|, 5, 8, 2, 9, 4, 15, 6] => [3, 7, 5, 8, 2, 9, 4, 15, 6]  <br>
 2-   [3, 7, 5|, 8, 2, 9, 4, 15, 6] => [3, 5, 7, 8, 2, 9, 4, 15, 6]  <br>
 3-   [3, 5, 7, 8|, 2, 9, 4, 15, 6] => [3, 5, 7, 8, 2, 9, 4, 15, 6]  <br>
 4-   [3, 5, 7, 8, 2|, 9, 4, 15, 6] => [2, 3, 5, 7, 8, 9, 4, 15, 6]  <br>
 5-   [2, 3, 5, 7, 8, 9|, 4, 15, 6] => [2, 3, 5, 7, 8, 9, 4, 15, 6]  <br>
 6-   [2, 3, 5, 7, 8, 9, 4|, 15, 6] => [2, 3, 4, 5, 7, 8, 9, 15, 6]  <br>
 7-   [2, 3, 4, 5, 7, 8, 9, 15|, 6] => [2, 3, 4, 5, 7, 8, 9, 15, 6]  <br>
 8-   [2, 3, 4, 5, 7, 8, 9, 15, 6|] => [2, 3, 4, 5, 6, 7, 8, 9, 15]  <br>
