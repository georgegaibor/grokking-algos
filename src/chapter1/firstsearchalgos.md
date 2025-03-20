# Simple Search and Binary Search


## Simple Search

* Stupid Search / Brute Force
* Eliminates elements one by one
* Complexity: \\( O(n)\\)

## Binary Search

* `INPUT`: sorted list of elements
* Eliminates at least half of the elements every iteration

### LOGIC
Searching for `item`

1. Define `lower` and `upper` limit to section the search
2. Calculate `middle` based on limits
3. If middle is `equal` to `target`, return `middle`
4. If guess is too high, update upper limit
5. If guess is too low, update lower limit
6. Search again until found
7. If not found, return `null`


```python
def binary_search(array, target):
    left = 0
    right = len(array) - 1

    while (left <= right):
        mid = (right + left) // 2

        if array[mid] == target:
            return mid
        elif array[mid] < target: 
            left = mid + 1
        else:
            right = mid - 1

    return -1
```

<details><summary><b>REMINDERS</b></summary>

> Binary search is faster than simple search as the dataset grows

> `COMPLEXITY:` \\(O(log(n))\\)

</details>
