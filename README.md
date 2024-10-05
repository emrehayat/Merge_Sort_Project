# Merge Sort Projesi

## Patika Dev - Veri Yapıları ve Algoritmalar - Proje 2

[16, 21, 11, 8, 12, 22] -> Merge Sort

- Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
- Big-O gösterimini yazınız.

## Cevap

Dizi: [16, 21, 11, 8, 12, 22]

### Merge Sort Aşamaları

[16, 21, 11] [8, 12, 22] <br/>
[16] [21, 11] [8] [12, 22] <br/>
[16] [21] [11] [8] [12] [22] <br/>
[16] [11, 21] [8] [12, 22] <br/>
[11, 16, 21] [8, 12, 22] <br/>
[8, 11, 12, 16, 21, 22]

### Big-O Gösterimi

Merge Sort algoritması, her bölme işlemi için logaritmik sayıda adımda bölünür ve her birleştirme işlemi O(n) zaman alır. Bu nedenle Merge Sort'un Big-O gösterimi: **O(n*logn)** olur.
