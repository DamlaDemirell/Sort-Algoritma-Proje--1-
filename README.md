# Sort-Algoritma-Proje--1-
soru: [22, 27, 16, 2, 18, 6] -> Insertion Sort
Yukarıda gösterilen dizinin sort türüne göre aşamalarını yazın.
cevap : 
[22,27,16,2,18,6] -> Insertion Sort ise , 
En küçüğüne bak (n) ; [ 2 ile 22 yi değiştir ]  
Bu durumda , [ 2, 27,16,22,18,6]
2 hariç tutulacak şekilde (n-1) [ 6 ile 27 yerini değiştir]
En küçüğü 2 ile en büyüğü 27 olduğuna göre tekrar sıralanır. 
Dizinin son hali bu şekilde olacaktır. [2,6,16,18,22,27] --> 1 

Time Complexity 
soru : Dizi sıralandıktan sonra 18 sayısı aşağıdaki case' lerden hangisinin kapsamına girer yazınız.
cevap : [2,6,16,18,22,27] Lower -> 2 , Middle -> 18 , Higher -> 27 olacaktır. 

2.soru: [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.
En küçüğüne bak (n) 2, 7 ile değişir.
bu durumda, [ 2,3,5,8,7,9,4,15,6] olacaktır. (n-1)
2 hariç tutulacak şekilde, 4 ile 5 değiştirdi. [2,3,4,8,7,9,5,15,6] (n-2)
2,3,4 hariç tutuldu , 5 ile 8 yer değiştirdi. [ 2,3,4,5,7,9,8,15,6] 
ilk dört adım sorulduğu için, 
son adım ise şu şekilde olacaktır. 
[2,3,4,5,6,7,8,9,15] 

