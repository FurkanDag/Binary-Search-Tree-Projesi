

## Binary Search Tree Projesi

# [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary Search Tree'ye göre adımları;

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin root elemanı 5 olarak seçilmiştir.

Dizinin ilk elemanı olan 7'nin sayısal değeri 5'den büyük olduğu için, 5'in sağ düğümüne geçecek.

  ```
   5
      ⇘
         7
  ```
Dizinin ikinci elemanı olan 5 sayısını zaten root olarak seçtildiği için atlanır.

Dizinin üçüncü elemanı olan 1, root elemanımız olan 5'den küçük olduğu için, 5'in sol düğümüne geçecek.

  ```
          5
       ⇙     ⇘
    1           7
  ```

Dizinin dördüncü elemanı olan , root elemanımız olan 5'den büyük olduğu için, 5'in sağ düğümüne geçecek. Sağ düğümdeki 7 ile karşılaştırılıp, 7'den büyük olduğu 7'nin sağ düğümünde kendine yer alacak.

  ```
          5
       ⇙     ⇘
    1           7
                   ⇘       
                      8
      
  
  ```

Dizinin beşinci elemanı olan 3, root elemanımız olan 5'den küçük olduğu için, 5'in sol düğümüne geçecek. Sol düğümdeki  1'den büyük olduğu için 1'in sağ düğümünde kendine yer alacak.

  ```
          5
       ⇙     ⇘
    1            7
      ⇘            ⇘       
        3             8
      

  ```

Dizinin altıncı elemanı olan 6, root elemanımız olan 5'dan büyük olduğu için, 5'inn sağ düğümüne geçecek. Sağ düğümde 7'den küçük olduğu için 7'nin sol düğümüne geçecek.

  ```
          5
       ⇙     ⇘
    1            7
      ⇘       ⇙     ⇘       
        3    6          8
      


```
Dizinin yedinci elemanı olan 0, root elemanımız olan 5'den küçük olduğu için, 5'in sol düğümüne geçecek. Sol düğümde 1'den küçük olduğu için 1'nin sol düğümüne geçecek.

  ```
              5
          ⇙     ⇘
        1           7
      ⇙   ⇘      ⇙    ⇘       
    0        3   6       8
      


  ```

Dizinin sekizinci elemanı olan 9, root elemanımız olan 5'den ve diğer elemanlardan daha büyük olduğuna göre direkt ağacın en sağ alt köküne gider.

  ```
              5
          ⇙     ⇘
        1           7
      ⇙   ⇘      ⇙    ⇘       
    0        3   6        8
                             ⇘
                                9
  ```

Dizinin dokuzuncu elemanı olan 4, root elemanımız olan 5'den küçük olduğu için, 5'in sol düğümüne geçecek. Sol düğümdeki 1 ile karşılaştırılıp, 1'den büyük olduğu için 1'in sağ düğümüne geçecek. Sağ düğümdeki 3 ile karşılaştırılıp, 3'den büyük olduğu için 3'ün sağ düğümüne geçecek. 
  ```
              5
          ⇙     ⇘
        1            7
      ⇙   ⇘       ⇙     ⇘       
    0        3    6          8
               ⇘                 ⇘
                  4                 9
  ```
  
  Dizinin dokuzuncu elemanı olan 4, root elemanımız olan 5'den küçük olduğu için, 5'in sol düğümüne geçecek. Sol düğümdeki 1 ile karşılaştırılıp, 1'den büyük olduğu için 1'in sağ düğümüne geçecek. Sağ düğümdeki 3 ile karşılaştırılıp, 3'den büyük olduğu için 3'ün sağ düğümüne geçecek. 
  ```
              5
          ⇙      ⇘
        1           7
      ⇙   ⇘      ⇙    ⇘       
    0        3   6        8
               ⇘            ⇘
                  4            9
  ```
  
  Dizininson elemanı olan 2, root elemanımız olan 5'den küçük olduğu için, 5'in sol düğümüne geçecek. Sol düğümdeki 1 ile karşılaştırılıp, 1'den büyük olduğu için 1'in sağ düğümüne geçecek. Sağ düğümdeki 3 ile karşılaştırılıp, 3'den küçük olduğu için 3'ün sol düğümüne geçecek. 
  ```
              5
          ⇙     ⇘
        1            7
      ⇙   ⇘       ⇙    ⇘       
    0        3    6        8
            ⇙   ⇘            ⇘
          2        4             9
  ```
