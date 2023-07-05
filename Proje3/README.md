# Proje 3
# 1.Soru
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

# Çözüm

Verilen dizinin Binary Search Tree (BST) aşamaları:

Dizi: [7, 5, 1, 8, 3, 6, 0, 9, 4, 2]

1.Adım:

İlk elemanı kök olarak belirliyoruz (root = 7).


2.Adım: 

Root'un sağına ve soluna elemanları ekliyoruz.

```
         7
        / \
       5   8
      / \   \
     1   6   9
    / \
   0   3
      / \
     2   4
```

Yukarıdaki şekilde gösterilen BST ağacı, verilen dizinin BST aşamalarını temsil etmektedir. Her adımda, bir eleman ağaca eklenmiştir. Ağacın yapısı, elemanların karşılaştırılarak doğru konumlarına yerleştirildiği bir şekilde oluşturulmuştur.

Bu aşamalarda, her eleman önce root ile karşılaştırılmıştır. Daha küçük olanlar sol tarafa, daha büyük olanlar sağ tarafa yerleştirilmiştir.

Dolayısıyla, verilen dizinin BST aşamaları yukarıda gösterildiği gibi olacaktır.
