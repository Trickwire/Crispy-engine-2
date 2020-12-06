# Crispy-engine-2
# Trying to write code that predicts the next three numbers in a limited sequence.

import random

numb = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20]

results = random.choices(numb, k=3)

print(results)
