# Selection Sort

* In-place comparison sorting algorithm
* `COMPLEXITY`: \\(O(n^2)\\)


`LOGIC:`

1. `TWO POINTERS`, minimum/maximum and current item
2. For every number, check every number after and compare
3. If smaller/bigger update minimum/maximum pointer
4. Swap positions as needed

`CODE`:

```python
def selection_asc_sort(list):
    n = len(list)
    for i in range(n-1):
        min_index = i
        
        for j in range(i+1, n):
            if(list[j] < list[min_index]):
                min_index = j
        
        if min_index != i:
            list[i], list[min_index] = list[min_index], list[i]
            
        
            
    return list
```