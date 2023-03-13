# www.patika.dev
# Veri Yapıları Ve Algoritmaları -Selection Sort Projesi

---
## Selection Sort
Başlangıçtaki sayı ile en küçük sayı yer değiştirir. Baştan sağ doğru sıralama bu şekilde devam eder.

[22,27,16,2,18,6]  sayılarını ele alırsak sıralama;

1-[2,27,16,22,18,6] = 22 ve 2 yer değiştirdi.

2-[2,6,16,22,18,27] = 27 ve 6 yer değiştirdi.

3-[2,6,16,18,22,27] = 22 ve 18 yer değiştirdi.

### Sayının Big-O gösterimi şu şekildedir; O(n^2)
### Time Complexity: Aradığımız sayı ortada olmasından dolayı Worst Case'dir.
---
## [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

1. Adım [2,3,5,8,7,9,4,15,6]= 2 ile 7 yer değiştirir.

2. Adım [2,3,5,8,7,9,4,15,6]= 3 kendinden küçük sayı bulamadığından olduğu yerde kalır.

3. Adım [2,3,4,8,7,9,5,15,6]= 5 ile 4 yer değiştirir.

4. Adım [2,3,4,5,7,9,8,15,6]= 8 ile 5 yer değiştirir.

5. Adım [2,3,4,5,7,9,8,15,6]= 5 kendinden küçük sayı bulamadığından yerinde kalır.

6. Adım [2,3,4,5,6,9,8,15,7]= 7 ile 6 yer değiştirir.

7. Adım [2,3,4,5,6,7,8,15,9]= 9 ile 7 yer değiştirir.

8. Adım [2,3,4,5,6,7,8,15,9]= 8 kendinden küçük sayı bulamaz.

9. Adım [2,3,4,5,6,7,8,9,15]= 15 ile 9 yer değiştirir.
