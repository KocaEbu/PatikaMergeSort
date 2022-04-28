# PatikaMergeSort
## Veri Yapıları ve Algoritmalar - 2
### Proje 2
* [16,21,11,8,12,22] -> Merge Sort yapma işlemi.
1. Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
2. Big-O gösterimini yazınız.


# Solution :
1.  * İlk Adım [16,21,11],[8,12,22] 
    * İkinci Adım [16] [21,11] , [8] [12,22]
    * Üçüncü Adım [16] [21] [11] , [8] [12] [22]
    * Dördüncü Adım [11,16,21] , [8,12,22]
    * Beşinci Adım [8,11,12,16,21,22]

2. Big-O = nlogn dolayısıyla Big-O = 6log6
