# Dict to save amino acid count
count_base = {}

# Counting amino acid amout
with open('rosalind_dna.txt', 'r') as file:
    s = file.read()
    s = s.upper()
    for base in s:
        if base in 'ACGT':
            if base not in qtde_base.keys():
                count_base[base] = 1
            else:
                count_base[base] = counnt_base[base] + 1

# Printing amino acid amount in request format
for base in sorted(qtde_base):
    print(f'{qtde_base[base]}', end=' ')

### Other way to solve the problem (Using count function) ###

with open('rosalind_dna.txt', 'r') as file:
    s = file.read()
    s = s.upper()
    A = s.count('A')
    C = s.count('C')
    G = s.count('G')
    T = s.count('T')
print(f'{A} {C} {G} {T}')

