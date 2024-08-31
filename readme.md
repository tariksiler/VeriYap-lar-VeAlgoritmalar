## Selection Sort Projesi

 [22,27,16,2,18,6] -> Insertion Sort

 İşlem adımları
 [22,27,16,2,18,6] -> [2,27,16,22,18,6] -> [2,6,16,22,18,27] -> [2,6,16,18,22,27]

 Burada tüm elemanlar taranıyor ve en küçüğü ilk kutucuktaki elemanla yer değiştiriyor. Taki son elemanda tamamlanana kadar.

 Burada Big-O(n2(n kare))

 Time Complexity: Dizi sıralandıktan sonra 18 sayısı "Average case: Aradığımız sayının ortada olması" kapsamına girer.


 [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımı -->

 [2,3,5,8,7,9,4,15,6] -> [2,3,4,8,7,9,5,15,6] -> [2,3,4,5,7,9,8,15,6] -> [2,3,4,5,6,9,8,15,7]


## Merge Sort Projesi

             [16,21,11,8,12,22]           -> Merge Sort
            [16,21,11]    [8,12,22]
           [16] [21,11]  [8] [12,22]
         [16] [21] [11]  [8] [12] [22]
            [16,21] [11]    [8,12] [22]
             [11,16,21]      [8,12,22]
                [8,11,12,16,21,22]
                
                Big-O (nlogn)

## Binary Search Tree Projesi

            [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree

                            [6]
                        [4]      [8]
                      [3]  [5] [7]  [9]     Yöntem 1 
                    [1]            
                 [0]  [2]


                              [5]
                        [3]        [7]
                    [1]    [4]   [6]  [8]      Yöntem 2 
                  [0] [1]                [9]
                  
