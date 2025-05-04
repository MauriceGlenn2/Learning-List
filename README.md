# Learning-List


# Learning Python Lists 🎓🐍

This simple Python project is part of my learning journey — I'm currently exploring how to work with lists and the `random` module.

## What It Does

This script selects a random person from a list of friends to "pay the bill" — like drawing names out of a hat.

### Python Code

```python
import random

friends = ["Alice", "Bob", "Charlie", "David", "Emanuel"]
bill_pay = random.choice(friends)

print(bill_pay)
