## Python Zodiac calculator with lists:
The code form of [[Lab6_Ex1]]

```python
animals = ["Rat", "Ox", "Tiger", "Rabbit", "Dragon", "Snake", "Horse", "Goat", "Monkey", "Rooster", "Dog", "Pig"]

birthYear = int(input("Enter your full year of birth (Ex. 2020): "))

r = (birthYear - 1900) % 12

print(f"The animal associated with your birth year of {birthYear} is {animals[r]}")
```
