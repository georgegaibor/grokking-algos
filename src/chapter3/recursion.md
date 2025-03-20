# Recursion

<details><summary><b>What is recursion?</b></summary>

> Coding technique where a function continuously calls itself, used as the basis of many algorithms
</details>

---
<details><summary><b>What are the performance benefits of recursion?</b></summary>

> There are none, it should only be used when it makes solutions clearer

> In fact, sometimes loops are more performant
</details>

---
<details><summary><b>What are the base and the recursive case?</b></summary>

| CASE | DETAIL |
| --- | --- |
| Base Case | signals when to stop recursing |
| Recursive Case | when the function calls itself |
</details>



## CODE SAMPLE

```python
def fact(x):
    if x == 1:
        return 1
    else:
        return x * fact(x-1)
```
## Further Reading

* Tail Recursion


