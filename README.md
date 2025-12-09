# 55
code 22
from itertools import product
s = 'ТИМОФЕЙ'
words = []
for w in product(s, repeat=5):
    if ('Т' in w) and w.count('Й') <= 1:
        words.append(w)
print(len(words))
