# duck-home
merge sort

[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.

  
                         [16,21,11,8,12,22]  -> İlk işlemimiz diziyi ortadan ikiye bölmektir.
                         /                \
                     [16,21,11]          [8,12,22]    ->Bölme işlemine kutular tek kalıncaya kadar devam edilir.                 
                      /    \                /  \  
                   [6]    [21,11]        [8]    [12,22] 
                   /       /   \          /      /   \
                 [6]      [21]  [11]    [8]     [12] [22]  -> Bu adımda sonra ise kutucuklardaki sayılar karşılaştırılır ve küçük sayı sola yazılır(küçükten büyüğe)
                  \        \     /       \        \   /
                  [6]      [11,21]       [8]     [12,22]  -> Kutucukalrın ilk elemanları karşılaştırılır. Küçükten büyüğe sıralanır.
                    \        /             \      / 
                     [6,11,21]             [8,12,22]      -> İki kutudaki wn küçük değerler karşılaştrılır. Küçük olan yazılır.Aynı işlem tüm diziye uygulanır.
                         \                     /
                            [6,8,11,12,21,22]             -> Merge sort'un sıralanmış hali 
                            
                            
www.patika.dev
