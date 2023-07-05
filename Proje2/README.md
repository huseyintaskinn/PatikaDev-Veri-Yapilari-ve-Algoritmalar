# Proje 2

# 1.Soru
[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız. Big-O gösterimini yazınız.

# Çözüm

1.Adım (Bölme):

[16, 21, 11]    [8, 12, 22]

2.Adım (Bölme):

[16]    [21, 11]     [8]    [12, 22]

3.Adım (Bölme):

[16]    [21]    [11]   [8]    [12]    [22]

4.Adım (Birleştirme):

[16, 21]    [11]     [8, 12]    [22]

5.Adım (Birleştirme):

[11, 16, 21]     [8, 12, 22]

6.Adım (Birleştirme):

[8, 11, 12, 16, 21, 22]

Dizinin sıralanmış hali: [8, 11, 12, 16, 21, 22]

Big-O gösterimi: O(n log n)

Yukarıdaki çözüm, Merge Sort algoritmasının adımlarını ve dizinin sıralanmış halini göstermektedir. Her adımda, dizinin bölünüp birleştirilmesi gerçekleştirilmektedir.
