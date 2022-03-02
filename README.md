### Kodluyoruz Veri Yapıları ve Algoritmalar Dersi Merge Ödevi

[16,21,11,8,12,22] -> Merge Sort

## Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

1. [16,21,11] & [8,12,22]
2. [16] & [21,11] & [8,12] & [22]
3. [16] & [21] & [11] & [8] & [12] & [22]
4. [16] & [11,21] & [8,12] & [22]
5. [11,16,21] & [8,12,22]
6. [8,11,12,16,21,22]

## Big-O gösterimini yazınız.

Sürekli ikiye bölerek gittiği için n/2 -> n/4 şeklinde elaman sayısı kadar bölecek. Eleman sayısını x dersek 2^x = n olur. Bu da x = logn'dir. Big O(logn)