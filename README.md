# Crispy-engine-2
# Trying to write Python code that predicts the next three numbers in a limited sequence.

import random

numb = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20]

results = random.choices(numb, k=3)

print(results)

# The latest pattern of numbers has been (3,14,11) (4,16,1) (17,2,15) (18,19,2)
# There can only be three numbers at a time adding up to a sum between 6 and 57
# More often than not, the pattern will be 2 evens and an odd or 2 odds and an even.
