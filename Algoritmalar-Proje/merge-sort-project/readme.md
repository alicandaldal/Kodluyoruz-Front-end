# Merge Sort Projesi

## İstenilenler
<br>
Proje 2

**[16,21,11,8,12,22]** -> Merge Sort

1. Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
2. Big-O gösterimini yazınız.

<br>

## Çözümler

<br>

```
Başlangıç: [16,21,11,8,12,22]

  Aşama 1:                    [16,21,11,8,12,22]             
  Aşama 2:              [16,21,11]           [8,12,22]
  Aşama 3:            [16]   [21,11]       [8]   [12,22]
  Aşama 4:         [16]   [21]   [11]    [8]   [12]   [22] 
  Aşama 5:            [16]   [11,21]       [8]   [12,22]
  Aşama 6:              [11,16,21]           [8,12,22]
  Aşama 7:                    [8,11,12,16,21,22]
```

```
 O(nlog(n))
```