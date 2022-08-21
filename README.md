# BinarySearchTree

[7,5,1,8,3,6,0,9,4,2] Binary-Search-Tree aşamalarını yazınız.

Root 7'dir.

Her bir basamakta kendisinden küçükler sola, büyükler ise sağa yerleştirilecek şekilde yazılır.

1.Adım
      5, 7'den küçüktür. Sola yerleştirilir.
      
                      7
                     /
                    5
                     
2.Adım
      1, 7'den küçüktür ve sola yerleştirilir.
              
                      7
                     /
                    5
                   /
                  1

3.Adım
      8, 7'den büyüktür ve sağa yerleştirilir.
      
                 7
                / \
               5   8
              /
             1
4.Adım
      3, 7'den küçüktür ve sola yerleştirilir.
      
                7
               / \
              5   8
             /
            1
             \
              3
5.Adım
      6, 7'den küçüktür ve sola yerleştirilir.
      
                7
               / \
              5   8
             / \
            1   6
             \
              3
6.Adım
      0, 7'den küçüktür ve sola yerleştirilir.
      
                7
               / \
              5   8
             / \
            1   6
           / \
          0   3
7.Adım
      9, 7'den büüyktür. Sağa yerleştirilir.
      
              7
             / \
            5   8
           / \   \
          1   6   9
         / \
        0   3
8.Adım
      4, 7'den küçüktür ve sola yerleştirilir.
      
            7
           / \
          5   8
         / \   \
        1   6   9
       / \
      0   3
           \
            4
9.Adım
      2, 7'den küçüktür ve sola yerleştirilir.
      
            7
           / \
          5   8
         / \   \
        1   6   9
       / \
      0   3
         / \
        2   4
