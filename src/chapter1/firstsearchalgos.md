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
3. If middle is `equal` to `item`, return `middle`
4. If guess is too high, update upper limit
5. If guess is too low, update lower limit
6. Search again until found
7. If not found, return `null`

<details><summary><b>REMINDERS</b></summary>

> Binary search is faster than simple search as the dataset grows

</details>
