\[16,21,11,8,12,22\] -\> Merge Sort
-----------------------------------

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
--------------------------------------------------------

    - Diziyi ikiye bölerek yeniden yazıyoruz                16  21  11  8   12  22          
    Sol ve sağdaki dizileri tekrar ikiye böluyoruz.         16  21  11          8   12  22      
    Tek eleman kalana kadar bir kez daha bölüyoruz.     16  21      11          8       12  22  
                        16      21      11          8       12      22


    Bölme işlemi bitikten sonra, tek elemanlı dizilerimizi ikili ikili birleştiriyoruz. Sıralı dizi elde edinceye kadar bu işleme devam ediyoruz.
                            16      21      11          8       12      22
    ikili ikili ikili sıralayarak birleştiriyoruz.      16  21      11          8       12  22  
    Tekrar ikili ikili sıralayarak birleştiriyoruz.         11  16  21          8   12  22      
    Son birleştirmede dizimizi elde ediyoruz.               8   11  12  16  21  22  

    ## Big-O gösterimini yazınız.

O(nlogn) \`\`\`
