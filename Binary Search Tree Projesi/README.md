# veri yapıları ve algoritmalar
Proje-3

# [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

* Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

    
    - Binary Search Treede en üstte bulunan node Root olarak adlandırılır.
    - Root’tan küçük değere sahip olan node’lar Root’un sol tarafında yer alır
    - Root’tan büyük değere sahip olan node’lar Root’un sağ tarafında yer alır.
    - Bu kural Recursive olarak sol ve sağ tarafta yer alan subtree’ler içinde geçerlidir.

* Root ilk değer olan ;7 seçilir.

                             [7]
* ikinci sayı (5) eklenir; 5<7 olduğu için soluna eklenir.
                             
                             [7]
                            /    
                         [5] 
* Üçüncü sayı (1) eklenir; Root'tan küçük sola 1<5 olduğu için 5'in soluna eklenir.
                             
                             [7]
                            /    
                         [5]            
                       /                         
                    [1]
* Dördüncü sayı (8) eklenir; Root yani 8>7 olduğu için; Root'un sağına eklenir.
                             
                              [7]
                            /     \
                         [5]       [8]     
                       /                         
                    [1]
* Beşinci sayı (3) eklenir; Root'tan küçük sola, 5'ten küçük tekrar sola; 3>1 olduğu için 1'in sağına eklenir.
                              
                              [7]
                            /     \
                         [5]       [8]  
                        /                            
                    [1]
                       \
                        [3]
* Altıncı sayı (6) eklenir; Root'tan küçük sola, 6>5 olduğu için 5'in sağına eklenir.
                              
                              [7]
                            /     \
                         [5]       [8]  
                        /    \
                       /      [6]                    
                    [1]
                       \
                        [3]
* Yedinci sayı (0) eklenir; Root'tan küçük sola, 5'ten küçük tekrar sola, 0<1 olduğu için 1'in soluna eklenir.
                              
                              [7]
                            /     \
                         [5]       [8]  
                        /    \
                       /      [6]                    
                    [1]
                   /   \
                  /     [3]
                [0] 
* Sekizinci sayı (8) eklenir; Root yani 9>7 olduğu için; Root'un sağına, 9>8 olduğu için 8'in sağına eklenir.
                             
                              [7]
                            /    \
                         [5]      [8]  
                        /    \       \
                       /      [6]     [9]               
                    [1]
                   /   \
                  /     [3]
                [0] 
* Dokuzuncu sayı (4) eklenir; Root'tan küçük sola, 5'ten küçük tekrar sola; 4>1 olduğu için 1'in sağına, 4>3 olduğu için 3'ün sağına eklenir.
                              
                              [7]
                            /    \
                         [5]      [8]  
                        /    \       \
                       /      [6]     [9]               
                    [1]
                   /   \
                  /     [3]
                [0]        \
                            [4]
* Onuncu sayı (2) eklenir; Root'tan küçük sola, 5'ten küçük tekrar sola; 2>1 olduğu için 1'in sağına, 2<3 olduğu için 3'ün soluna eklenir.
                              
                              [7]
                            /    \
                         [5]      [8]  
                        /    \       \
                       /      [6]     [9]               
                    [1]
                   /   \
                  /     [3]
                [0]    /   \
                     [2]    [4]     






[Patika.dev](https://www.patika.dev/tr)
![patika logo](https://global-uploads.webflow.com/6097e0eca1e87557da031fef/609859a191abe5d64b17fed3_Patika%20logo.png)
