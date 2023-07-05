# PatikaDev-Veri-Yapilari-ve-Algoritmalar
# Proje 1
# 1.Soru
[22,27,16,2,18,6] -> Insertion Sort

Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız. Big-O gösterimini yazınız.
Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız.

Average case: Aradığımız sayının ortada olması.

Worst case: Aradığımız sayının sonda olması.

Best case: Aradığımız sayının dizinin en başında olması.

# Çözüm

1.Adım:

22 | 27 16 2 18 6


2.Adım:

22 27 | 16 2 18 6


3.Adım:

22 16 27 | 2 18 6

16 22 27 | 2 18 6


4.Adım:

16 22 2 27 | 18 6

16 2 22 27 | 18 6

2 16 22 27 | 18 6


5.Adım:

2 16 22 18 27 | 6

2 16 18 22 27 | 6


6.Adım:

2 16 18 22 6 27 |

2 16 18 6 22 27 |

2 16 6 18 22 27 |

2 6 16 18 22 27 |


Dizinin sıralanmış hali: [2, 6, 16, 18, 22, 27]

Big-O gösterimi: O(n^2)

Time Complexity: 18 sayısı, dizi sıralandıktan sonra "Average case" kapsamına girer. Çünkü aradığımız sayı dizinin ortasında yer almaktadır.

# Soru 2
[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

# Çözüm

1.Adım:

En küçük eleman: 2

2 | 3 5 8 7 9 4 15 6


2.Adım:

Kalan elemanlar arasında en küçük eleman: 3

2 3 | 5 8 7 9 4 15 6


3.Adım:

Kalan elemanlar arasında en küçük eleman: 4

2 3 4 | 8 7 9 5 15 6


4.Adım:

Kalan elemanlar arasında en küçük eleman: 5

2 3 4 5 | 7 9 8 15 6

