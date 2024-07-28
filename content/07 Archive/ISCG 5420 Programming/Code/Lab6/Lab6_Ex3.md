## Maori word translation quiz ver1:
Builds on the list concepts learnt in [[Lists]]
```python
import random

englishWords = ["Apple", "Banana", "Orange", "Pear", "Strawberry", "Blueberry", "Pineapple", "Cherry", "Watermelon", "Grape"]

maoriWords = ["Aporo", "Panana", "Karaka", "Pea", "Rōpere", "Patatini Kikorangi", "Paināporo", "Tiere", "Merengi", "Wāina"]

word = random.randint(0, 9)

answer = input(f"Enter the english translation for {maoriWords[word]}: ").title()

try:
    if englishWords.index(answer) == word:
        print(f"You win! The answer was {englishWords[word]}")

except ValueError:
    print(f"Your answer of {answer} is incorrect, the correct answer is {englishWords[word]}")
```