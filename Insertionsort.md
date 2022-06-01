# Insertion Sort
1- Soldan sağa doğru en küçük değeri tespit edip ilk değerimizle değiştiriyoruz. Bu işlemi sıralama tamamlanana kadar uyguluyoruz.
### [22,27,16,2,18,6]
--[2,27,16,22,18,6] **n tane işlem**
--[2,6,16,22,18,27] **n-1**
--[2,6,16,22,18,27] **...**
--[2,6,16,18,22,27] **1 işlem**
2- Big O Notation:
[1+...+n-1+n]
[n*(n+1)/2]
[O(n^2)]
3- 18 sayısı *average case* kapsamına girer.

### [7,3,5,8,2,9,4,15,6]

--[2,3,5,8,7,9,4,15,6]
--[2,3,4,8,7,9,5,15,6]
--[2,3,4,6,7,9,5,15,8]
--[2,3,4,6,7,8,5,15,9]