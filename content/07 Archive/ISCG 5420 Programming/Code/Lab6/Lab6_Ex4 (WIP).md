## Python Maori translation quiz ver2:
Expands on the last [[Lab6_Ex3|activity]]
```python
import random

englishWords = ["Apple", "Banana", "Orange", "Pear", "Strawberry", "Blueberry", "Pineapple", "Cherry", "Watermelon", "Grape"]

maoriWords = ["Aporo", "Panana", "Karaka", "Pea", "Rōpere", "Patatini Kikorangi", "Paināporo", "Tiere", "Merengi", "Wāina"]

word = random.randint(0, 9)
n = 1

words = []
words.append(englishWords[word])

for i in range(3):
    words.append(random.sample(englishWords, 1))

random.shuffle(words)

for i in words:
    print(f"{n}. {i}")
    n += 1

answer = input(f"Enter the english translation for {maoriWords[word]}: ").title()

try:
    if englishWords.index(answer) == word:
        print(f"You win! The answer was {englishWords[word]}")

except ValueError:
    print(f"Your answer of {answer} is incorrect, the correct answer is {englishWords[word]}")
```