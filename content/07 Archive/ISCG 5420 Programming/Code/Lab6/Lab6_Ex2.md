## Python Grade calculator:
Builds on the last last [[Lab6_Ex1 Code|exercise]]
```python
AllGrades = ["D", "C-", "C", "C+", "B-", "B", "B+", "A-", "A", "A+"]
MyGrades = ["A+", "B-", "A", "C", "B-"]

S = 0

for item in MyGrades:
    S += AllGrades.index(item)

GPA = S/len(MyGrades)

print(f"GPA = {S}")
```