# SelectionSort_Insertion-Sort
Selection Sort Projesi ve Insertion Sort Projesi
www.patika.dev

[22,27,16,2,18,6] - Insertion Sort türüne göre aşamaları 

[22,27,16,2,18,6] - En küçük sayı ile baştaki sayı yer değiştirir.
[2,27,16,22,18,6] - Şimdi ise 2. en küçük sayıyı 2. sıraya alıp 2. sıradaki sayı ile yer değiştirelim.
[2,6,16,22,18,27] - Burada 3. en en küçük sayı 3 . sırada olduğu için işlem yapmıyoruz.
[2,6,16,18,22,27] - 4. en küçük olan 18 sayısı ile 22 sayısı yer değiştirir ve son adım gerçekleşmi olup sıralama bitmiş olur.

Big-O Gösterimi - O(n^2)

Time Complexity : Dizi sıralandığında 18 sayısı ortada olduğu için Average case kapsamına girer.

[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımı;

1.adım - [2/,3,5,8,7,9,4,15,6]
2.adım - [2,3/,5,8,7,9,4,15,6]
3.adım - [2,3,4/,8,7,5,15,6]
4.adım - [2,3,4,5/,7,9,8,15,6]
