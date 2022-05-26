# patika.dev : Veri Yapıları ve Algoritmalar >Insertion Sort Projesi 

## 1)
```
	[22,27,16,2,18,6] -> Insertion Sort
	[22,27,16,2,18,6] -> Insertion Sort
	[22,16,27,2,18,6] -> Insertion Sort
	[16,22,27,2,18,6] -> Insertion Sort
	[16,22,2,27,18,6] -> Insertion Sort
	[16,2,22,27,18,6] -> Insertion Sort
	[2,16,22,27,18,6] -> Insertion Sort
	[2,16,22,18,27,6] -> Insertion Sort
	[2,16,18,22,27,6] -> Insertion Sort
	[2,16,18,22,6,27] -> Insertion Sort
	[2,16,18,6,22,27] -> Insertion Sort
	[2,16,6,18,22,27] -> Insertion Sort
	[2,6,16,18,22,27] -> Insertion Sort
```

## 2) Big-O :
```n! = n*(n+1)/2 => (n^2+n) / 2 => O(n^2)```

## 3) time complexity
```
	w.c. : O(n^2)
	a.c. : O(n^2)
	b.c. : O(n)
```

## 4) [2,16,6,18,22,27] 
```18 sayısı Ortalarda olduğu için averace case kapsamındadır
```	
## 5) [7,3,5,8,2,9,4,15,6]
```
[3,7,5,8,2,9,4,15,6]
[3,5,7,8,2,9,4,15,6]
[2,3,5,7,8,9,4,15,6]
[2,3,4,5,7,8,9,15,6]
```
