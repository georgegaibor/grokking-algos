# Exercises

## 2.1

`REQUIREMENTS:`

* Every element is read
* Lots of inserts
* Few reads

| Data Structure | INSERT | READ |
| --- | --- | --- |
| Array | \\(O(n)\\) | \\(O(1)\\) |
| Linked List | \\(O(1)\\) | \\(O(n)\\) |


---
<details><summary><b>ANSWER</b></summary>

> Linked Lists perform better for reads

> If reading every item LLs are faster too
</details>

## 2.2

`REQUIREMENTS:`

* Store list of orders
* Servers can add orders
* Chefs remove orders before making them

<details><summary><b>ANSWER</b></summary>

> Linked List

> Its a FIFO system accessed sequentially
</details>

## 2.3

`REQUIREMENTS:`

* Search if username is in list of usernames before login
* Binary search (needs random access)

<details><summary><b>ANSWER</b></summary>

> Sorted array

> Arrays provide random access, it needs to be sorted in order to use the binary search algorithm
</details>

## 2.4

`REQUIREMENTS:`

* suppose FB uses an `array` to store the list of users, and uses `binary search`

<details><summary><b>What would be the downsides of an array for inserts?</b></summary>

> Insertions would be slow, \\(O(n)\\)
</details>

<details><summary><b>What happens when you add new users to the array?</b></summary>

> The array would need to be sorted after each new user is added
</details>


## 2.5

`REQUIREMENTS:`

* suppose FB uses a `hybrid DS` to store information: an array of 26 linked lists, one for each letter in the alphabet

<details><summary><b>Compare this DS to arrays and linked lists</b></summary>

| Operation | Array | Linked List |
| --- | --- | --- |
| Hybrid Search | slower | faster |
| Hybrid Insert | faster | equal |
</details>
