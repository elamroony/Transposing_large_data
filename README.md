# Transposing_large_data

Transposing a data set is the process that create a new data file in which the rows and columns in the original data file are transposed so that rows become columns and columns become rows. ITranspose creates a new file contains the transposed data. User can chose the format of the output file, either:
```
0: No spaces.
1: A space.
2: A tab.
```


**Input file**:
-----------------------------------------------------------
```
12AFKP
34BGLQ
56CHMR
78DWNS
90EZOT
```
-----------------------------------------------------------

**Output file (0)**:

-----------------------
```
13579
24680
ABCDE
FGHWZ
KLMNO
PQRST
```
-----------------------------------------------------------

Output file (1):

-----------------------
```
1 3 5 7 9
2 4 6 8 0
A B C D E
F G H W Z
K L M N O
P Q R S T
```
-----------------------------------------------------------

**Output file (2)**:

-----------------------
```
1	3	5	7	9
2	4	6	8	0
A	B	C	D	E
F	G	H	W	Z
K	L	M	N	O
P	Q	R	S	T
```
-----------------------------------------------------------
