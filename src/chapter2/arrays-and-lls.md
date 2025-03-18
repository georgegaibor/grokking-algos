# How memory works

* Computers are like giant set of drawers, each with its own address

![Storing Item in Memory](images/storing-item.svg)


# Arrays

<details><summary><b>How are items stored?</b></summary>

> Contiguosly
</details>

---
<details><summary><b>What if you are out of space?</b></summary>

> Items relocate to fit
</details>

---
<details><summary><b>Why is adding items slow?</b></summary>

> The array need to relocate for every new one
</details>

---
<details><summary><b>How to work around this?</b></summary>

> Ask for more memory than needed
</details>

---

<details><summary><b>What are the downsides?</b></summary>

> 1. If the extra is unused it's wasted

> 2. You may need more still
</details>


# Linked Lists

<details><summary><b>How are items stored?</b></summary>

> Anywhere in memory
</details>

---
<details><summary><b>How are items grouped?</b></summary>

> Their memory addresses are linked using pointers

> `POINTERS:` bit of memory that stores memory addresses
</details>


# Arrays vs Linked Lists

| Feature | Arrays | Linked Lists | Notes |
| --- | --- | --- | --- |
| Access | Random and Sequential | Sequential |
| Read | \\(O(1)\\) | \\(O(n)\\) | Arrays can use `caching`
| Insert | \\(O(n)\\) | \\(O(1)\\) | For LLs insertion and deletion are constant time operations if the element can be instantly accessed, like first and last
| Delete | \\(O(n)\\) | \\(O(1)\\) |

---
<details><summary><b>What is caching?</b></summary>

> Reading memory in chunks
</details>
