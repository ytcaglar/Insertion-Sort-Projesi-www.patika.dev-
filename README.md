# Insertion-Sort-Projesi-www.patika.dev-
Patika Kapsamında Sort Dersleri Sonu Alıştırma Projeleri Kapsamında Yapılmıştır. Insertion Sort Projesi'dir. [www.patika.dev]

## Insertion Sort Projesi

[22,27,16,2,18,6] -> Insertion Sort
----------------------------
- ### Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

1. Aşama => [2,|27,16,22,18,6]
2. Aşama => [2,6,|16,22,18,27]
3. Aşama => [2,6,16,|22,18,27]
4. Aşama => [2,6,16,18,|22,27]
5. Aşama => [2,6,16,18,22,|27]

- ### Big-O gösterimini yazınız.

  - n + (n-1) + (n-2) + ---- + 1 = (n.(n+1))/2 = n^2/2 + n/2 ==> Buradanda Big-O Gösterimi O(n^2) 

- ### Time Complexity: 

- Average case: Aradığımız sayının ortada olması,
- Worst case: Aradığımız sayının sonda olması, 
- Best case: Aradığımız sayının dizinin en başında olması.

- ### Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

#### Dizi Sıralandıktan Sonra: [2,6,16,18,22,27]

- 18 Sayısının Ortada Olmasından Dolayı Average Case Kapsamına Girer...

- ### [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.