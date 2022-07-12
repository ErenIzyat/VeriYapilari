\[7, 5, 1, 8, 3, 6, 0, 9, 4, 2\] dizisinin Binary-Search-Tree aşamalarını yazınız.
----------------------------------------------------------------------------------

    - root kök 7 

    - 5<7 olduğu icin 7 nin soluna eklenir.     7
                        5

    - 1<7 ve 1<5 oldugu icin 5 in soluna eklenir.   7
                        5
                    1
    - 8>7 olduğu için 7 nin sağına eklenir.     7
                        5       8
                    1
    - 3<7 3<5 ve 3>1 oldugu ıcın birin sagina   7
                        5       8
                    1
                        3
    - 6<7 oldugu ıcın 5 in sagına           7
                        5       8
                    1       6 
                        3
    - 0 1 ın soluna                 7
                        5       8
                    1       6
                0       3
    - 9 7 nin sağına ve 8 in sağına         7
                        5       8
                    1       6       9
                0       3
    - 4 ve 2 sırayla eklenırse
                            7
                        5       8
                    1       6       9
                0       3
                    2       4
