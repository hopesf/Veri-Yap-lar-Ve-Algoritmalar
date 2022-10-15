# Patika Veri Yapıları Ve Algoritmaları

# https://app.patika.dev/selimcoder

## Insert Sort Projesi

[22,27,16,2,18,6] -> Insertion Sort

A.Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

1-) [2,27,16,22,18,6] -> 2 ile 22 sayısı yer değiştirdi

2-) [2,6,16,22,18,27] -> 6 ile 27 rakamı yer değiştirdi

3-) [2,6,16,22,18,27]-> siradaki sayı 16 yer değiştirme yapılmadı

4-) [2,6,16,18,22,27]-> 18 ile 22 rakamı yer değiştirdi

5-) [2,6,16,18,22,27]-> siradaki sayı 22 yer değiştirme yapılmadı

6-) [2,6,16,18,22,27]-> siradaki sayı 27 yer değiştirme yapılmadı
Toplam işlem sayısı 6

B.Big-O gösterimini yazınız.
1-) O(n^2)

C. Time Complexity:

Best case: Aradığımız sayının dizinin en başında olması
Worst case: Aradığımız sayının sonda olması
Average case: Aradığımız sayının ortada olması

D.Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

[2,6,16,18,22,27]=> Siralanmiş dizi

Cevap : Aradigimiz sayi başta(best case) ve sonda(worse case) olmadigindan beklenilen durum olarak Average Case'dir

E.[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

1-)[2,3,5,8,7,9,4,15,6] -> 2 ile 7 sayısı yer değiştirdi

2-)[2,3,4,8,7,9,5,15,6] -> 5 ile 4 sayısı yer değiştirdi

3-)[2,3,4,5,7,9,8,15,6] -> 8 ile 5 sayısı yer değiştirdi

4-)[2,3,4,5,6,9,8,15,7] -> 6 ile 7 sayısı yer değiştirdi

# Merge Sort Dersi

[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

\*\*\* [16,21,11,8,12,22] ilk asama olarak parcalama yapmaliyiz

1-)[16,21,11] [8,12,22] => 3 erli 2 gruba ayirdik

2-)[16] [21,11] [8,12] [22] => 3 lu gruplari 2 serli gruplara ayirdik(esi olmayan tek kalabilir,tek kalan rastgele secilir)

3-)[16] [21] [11] [8] [12] [22] => 2 li gruplar tekli gruplara dagilir

4-) [16] [11,21] [8,12] [22] => gruplar tekrar 2'li gruplara donusturulur tek fark grup yapilirken kucuk basa gecer

5-) [11,16,21] [8,12,22] => 3'lu sirali gruplara gecilir

6-) [8,11,12,16,21,22] => tum grup birlesir ve kendi icinde siralanir

Big-O gösterimini yazınız.

\*_ O(6_(log6))

## Binary Search Tree Projesi

### Binary-Search-Tree aşamalarını yazınız.

1-) [7, 5, 1, 8, 3, 6, 0, 9, 4, 2]=> İşleme başlamak için kendimize bir root sayısı vermemiz lazım.

Benim root rakamim "5"dir
Baştan başlayarak 5 sayısından büyüklar sağa küçükler sola geçecek.

                                      5
                              1       |      7
                           0  |   3        6 |  8
                                2 |  4           |  9
