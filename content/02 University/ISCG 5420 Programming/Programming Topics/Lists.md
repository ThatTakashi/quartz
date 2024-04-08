# What is a List?:
> [!tip]
> `[1, 2, 3]`
> An example of a list

Lists are able to hold multiple data types

# List methods:
### Length:
```python
len(list)
```

### Concatenation:
```python
list1 = [1, 2, 3]
list2 = [3, 2, 1]
list3 = list1 + list2
print(list3)

>> [1, 2, 3, 3, 2, 1]
```

### Membership:
```python
list1 = [1, 2, 3]
if 3 in list1:
	print("3 is in the list")

>> "3 is in the list"
```

### Sort:
```python
list1 = ['a', 'c', 'b']
list1.sort() = ['a', 'b', 'c']
print(list1)

>> ['a', 'b', 'c']
```

### Occurrence of Elements:
```python
list1 = [1, 2, 3]
total = list1.count(2)
print(total)

>> 1
```

# Index:
- Each element of a list has a unique position number or index
- Starts counting from 0