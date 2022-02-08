# List

List is an array like data structure in python.
Unlike array, list supports heterogenous datatypes i.e. list can store other dataypes like string, numbers, dictionaries, objects and even lists.

## List operations

### Merge two lists

Two lists can be added using the + operator.

```python
a = [1,2,3]
b = [4,5,6]

c = a + b

print(c)  # [1, 2, 3, 4, 5, 6]
```

Similarly two lists can be merged using the extend() function

```python
a = [1,2,3]
b = [4,5,6]

a.extend(b)

print(b)  # [1, 2, 3, 4, 5, 6]
```

The function extend() modifies the a list.

### Append values to list

Similar to extend(), append however doesn't extract the outer layer of the appending list. It adds the list as **_it is_** to the list where it is being appended.

```python
a = [1,2,3]
b = [4,5,6]

a.append(b)

print(b)  # [1, 2, 3, [4, 5, 6]]
```

## List related functions

| Functions                | Description                                             |
| ------------------------ | ------------------------------------------------------- |
| sort()                   | Sorts the list in ascending order.                      |
| type(list)               | It returns the class type of an object.                 |
| append()                 | Adds one element to a list.                             |
| extend()                 | Adds multiple elements to a list.                       |
| index()                  | Returns the first appearance of a particular value.     |
| max(list)                | It returns an item from the list with a max value.      |
| min(list)                | It returns an item from the list with a min value.      |
| len(list)                | It gives the overall length of the list.                |
| clear()                  | Removes all the elements from the list.                 |
| insert()                 | Adds a component at the required position.              |
| count()                  | Returns the number of elements with the required value. |
| pop()                    | Removes the element at the required position.           |
| remove()                 | Removes the primary item with the desired value.        |
| reverse()                | Reverses the order of the list.                         |
| copy()                   | Returns a duplicate of the list.                        |
| range(start, stop, step) | Returns a list of numbers.                              |
