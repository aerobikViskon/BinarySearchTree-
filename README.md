# Binary Search Tree - Proje 3

## Verilen Dizi:
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2]

## Binary Search Tree Aşamaları:

1. **Başlangıç:**  
   İlk eleman 7, ağacın kökü (root) olur.  
   - Root: 7

2. **İkinci Eleman:**  
   5 sayısı 7'den küçük olduğu için 7'nin soluna yerleşir.  
   - Root: 7  
   - Sol: 5

3. **Üçüncü Eleman:**  
   1 sayısı 7'den küçük, 5'ten de küçük olduğu için 5'in soluna yerleşir.  
   - Root: 7  
   - Sol: 5  
   - 5'in Solu: 1

4. **Dördüncü Eleman:**  
   8 sayısı 7'den büyük olduğu için 7'nin sağına yerleşir.  
   - Root: 7  
   - Sol: 5  
   - 5'in Solu: 1  
   - Sağ: 8

5. **Beşinci Eleman:**  
   3 sayısı 7'den küçük, 5'ten küçük ama 1'den büyük olduğu için 1'in sağına yerleşir.  
   - Root: 7  
   - Sol: 5  
   - 5'in Solu: 1  
   - 1'in Sağı: 3  
   - Sağ: 8

6. **Altıncı Eleman:**  
   6 sayısı 7'den küçük, 5'ten büyük olduğu için 5'in sağına yerleşir.  
   - Root: 7  
   - Sol: 5  
   - 5'in Solu: 1  
   - 1'in Sağı: 3  
   - 5'in Sağı: 6  
   - Sağ: 8

7. **Yedinci Eleman:**  
   0 sayısı 7'den, 5'ten ve 1'den küçük olduğu için 1'in soluna yerleşir.  
   - Root: 7  
   - Sol: 5  
   - 5'in Solu: 1  
   - 1'in Solu: 0  
   - 1'in Sağı: 3  
   - 5'in Sağı: 6  
   - Sağ: 8

8. **Sekizinci Eleman:**  
   9 sayısı 7'den büyük, 8'den de büyük olduğu için 8'in sağına yerleşir.  
   - Root: 7  
   - Sol: 5  
   - 5'in Solu: 1  
   - 1'in Solu: 0  
   - 1'in Sağı: 3  
   - 5'in Sağı: 6  
   - Sağ: 8  
   - 8'in Sağı: 9

9. **Dokuzuncu Eleman:**  
   4 sayısı 7'den küçük, 5'ten küçük ama 1'den büyük, 3'ten büyük olduğu için 3'ün sağına yerleşir.  
   - Root: 7  
   - Sol: 5  
   - 5'in Solu: 1  
   - 1'in Solu: 0  
   - 1'in Sağı: 3  
   - 3'ün Sağı: 4  
   - 5'in Sağı: 6  
   - Sağ: 8  
   - 8'in Sağı: 9

10. **Onuncu Eleman:**  
    2 sayısı 7'den küçük, 5'ten küçük, 1'den büyük ve 3'ten küçük olduğu için 3'ün soluna yerleşir.  
    - Root: 7  
    - Sol: 5  
    - 5'in Solu: 1  
    - 1'in Solu: 0  
    - 1'in Sağı: 3  
    - 3'ün Solu: 2  
    - 3'ün Sağı: 4  
    - 5'in Sağı: 6  
    - Sağ: 8  
    - 8'in Sağı: 9


