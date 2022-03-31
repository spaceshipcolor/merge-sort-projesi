# Merge Sort Projesi

## [16,21,11,8,12,22] 
### Soru 1) Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

```
                [16,21,11,8,12,22]
               /                 \
     [16,21,11]                  [8,12,22]
       /     \                     /     \
  [16,21]   [11]               [8,12]   [22]
   /  \       |                 /  \      |
[16] [21]   [11]              [8] [12]  [22]
 \    /       |                \   /      |
[16,21]     [11]               [8,12]   [22]
     \      /                     \      /
    [11,16,21]                  [8,12,22]
            \                    /
               [8,11,12,16,21,22]
```
### Soru 2) Big-O gösterimini yazınız.

* 2^x=n 
* x=logn
* Time Complexity: O(n)
* Big-O= O(nlogn)

                    