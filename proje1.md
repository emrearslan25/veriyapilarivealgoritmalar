# Proje 1

[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.
Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

# Insertion Sort Aşamaları

 ```
 [22|,27,16,2,18,6]
 [22,27|,16,2,18,6]
 [16,22,27|,2,18,6]
 [2,16,22,27|,18,6]
 [2,16,18,22,27|,6]
 [2,6,16,18,22,27]
 ```
 # Big O Notation Gösterimi
 
 ```
Best Case : O(n)
Worst Case : O(n^2)
Average Case : O(n^2)
 ```
 
 # Time Complexity
 
 ```
Average Case : O(n^2)
Worst Case : O(n^2)
Best Case : O(n)
 ```
 
 [Patika](www.patika.dev)
 
 # Dizi Sıralandıktan Sonra 18 Sayısı Hangi Case Kapsamına Girer?
 ```
 18 sayısı ortada olduğu için average case kapsamına girer.
 ```
 
 # Dizinin İlk 4 Adımı
 
 ```
[7|,3,5,8,2,9,4,15,6]
[3,7|,5,8,2,9,4,15,6]
[3,5,7|,8,2,9,4,15,6]
[3,5,7,8|,2,9,4,15,6]
 ```
