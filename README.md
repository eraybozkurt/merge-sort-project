# merge-sort-project


Merge Sort Project


[16,21,11,8,12,22] -> Merge Sort

- Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
- Big-O gösterimini yazınız.

ANSWER

Önce sayıları ortadan ikiye böleceğiz. 

```
[16,21,11]       [8,12,22]
```

```
[16,21]  [11]    [8,12]    [22]
```

```
[16]   [21]   [11]   [8]    [12]    [22]
```

Burda bölme işlemi bitti, şimdi küçükten büyüğe doğru sıralayacağız. 

```
[8,  11,  12,  16,  21,  22 ] 
```

ANSWER 2 
```
Best case    : O(n*logn)
Average case : O(n*logn)
Worst case   : O(n*logn)
```
