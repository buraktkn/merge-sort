# Sorting Algorithm: Merge Sort

## Problem
Dizi: **[16, 21, 11, 8, 12, 22]**

---

## Merge Sort Aşamaları

### 1. Diziyi Parçalama (Divide)
Dizi, her adımda iki alt diziye bölünür:
1. **[16, 21, 11, 8, 12, 22]**  
   -> **[16, 21, 11]** ve **[8, 12, 22]**

2. **[16, 21, 11]**  
   -> **[16]**, **[21, 11]**  
   **[21, 11]** -> **[21]**, **[11]**

3. **[8, 12, 22]**  
   -> **[8]**, **[12, 22]**  
   **[12, 22]** -> **[12]**, **[22]**

### 2. Birleştirme ve Sıralama (Conquer and Combine)
Alt diziler sıralanarak birleştirilir:
1. **[21]** ve **[11]** -> **[11, 21]**  
   **[16]** ve **[11, 21]** -> **[11, 16, 21]**

2. **[12]** ve **[22]** -> **[12, 22]**  
   **[8]** ve **[12, 22]** -> **[8, 12, 22]**

3. Son birleştirme:  
   **[11, 16, 21]** ve **[8, 12, 22]** -> **[8, 11, 12, 16, 21, 22]**

---

## Sonuç
Sıralı dizi: **[8, 11, 12, 16, 21, 22]**

