---
title: ec1_ea
author: viona

---

#	QS1
1.	**`true`**
	<details>
	<summary>&shy;</summary>
	> <code>5 is a truth-function of { 1 , 2 }
	5 = Germany invaded both Poland and Czechoslovakia
	1 = Germany invaded Poland
	2 = Germany invaded Czechoslovakia</code>
	</details>

2.	**`true`**
	<details>
	<summary>&shy;</summary>
	> <code>6 is a truth-function of { 3 , 4 }
	6 = Either Germany was allied with Italy or it was allied with Japan
	3 = Germany was allied with Italy
	4 = Germany was allied with Japan</code>
	</details>

3.	**`true`**
	<details>
	<summary>&shy;</summary>
	> <code>7 is a truth-function of { 4 }
	7 = Germany was not allied with Japan
	4 = Germany was allied with Japan</code>
	</details>

4.	**`false`**
	<details>
	<summary>&shy;</summary>
	> <code>8 is a truth-function of { 3 , 4 }
	8 = Germany became allied with Japan after becoming allied with Italy
	3 = Germany was allied with Italy
	4 = Germany was allied with Japan</code>
	</details>

5.	**`false`**
	<details>
	<summary>&shy;</summary>
	> <code>9 is a truth-function of { 1 }
	9 = Germany conquered Poland
	1 = Germany invaded Poland</code>
	</details>

6.	**`true`**
	<details>
	<summary>&shy;</summary>
	> <code>10 is a truth-function of { 3 }
	10 = Italy was allied with Germany
	3 = Germany was allied with Italy</code>
	</details>

7.	**`false`**
	<details>
	<summary>&shy;</summary>
	> <code>11 is a truth-function of { 1 , 2 }
	11 = Neither Poland nor Czechoslovakia invaded Germany
	1 = Germany invaded Poland
	2 = Germany invaded Czechoslovakia</code>
	</details>

8.	**`false`**
	<details>
	<summary>&shy;</summary>
	> <code>12 = Germany was allied with Italy until Germany invaded Poland
	1 = Germany invaded Poland
	3 = Germany was allied with Italy</code></sub>

#	QS2
1.	**Y**<sub>1</sub> =
	`((A & B & ~C) ∨ (~A & B & C))`
2.	**Y**<sub>2</sub> =
	`~((A & B & C) ∨ (A & B & ~C) ∨ (A & ~B & C) ∨ (A & ~B & ~C) ∨
	(~A & B & C) ∨ (~A & B & ~C) ∨ (~A & ~B & C) ∨ (~A & ~B & ~C))`
3.	**Y**<sub>3</sub> =
	`(~A & B & ~C)`
4.	**Y**<sub>4</sub> =
	`((A & B & C) ∨ (A & B & ~C) ∨ (A & ~B & C) ∨ (A & ~B & ~C))`

#	QS3
1.	**`yes`**
2.	**`no`***`(contains non-basic conjunction: (B ∨ C))`*
3.	**`yes`**
4.	**`yes`**
5.	**`yes`**
6.	**`no`***`(contains non-basic conjunction: ∼(A&B))`*
7.	**`no`***`(contains non-basic conjunctions and non-disjunctive connective)`*

#	QS4
1. **Y**<sub>1</sub> = `(~(~A ∨ ~B ∨ C) ∨ ~(A & ~B & ~C))`
2. **Y**<sub>2</sub> = 

		~(~(A ∨ B ∨ C) ∨ ~(A ∨ B ∨ ~C) ∨ ~(A ∨ ~B ∨ C) ∨ ~(A ∨ ~B ∨ ~C) ∨ 
		~(~A ∨ B ∨ C) ∨ ~(~A ∨ B ∨ ~C) ∨ ~(~A ∨ ~B ∨ C) ∨ ~(~A ∨ ~B ∨ ~C))

3. **Y**<sub>3</sub> = `~(~A ∨ B ∨ ~C)`
4. **Y**<sub>4</sub> = `(~(~A ∨ ~B ∨ ~C) ∨ ~(~A ∨ ~B ∨ C) ∨ ~(~A ∨ B ∨ ~C) ∨ ~(~A ∨ B ∨ C))`

#	QS5
1. **Y**<sub>5</sub> = `~(~(A & ~B & C) & ~(A & ~B & ~C) & ~(~A & B & C))` 
2. **Y**<sub>6</sub> = `~(~(A & B & C) & ~(~A & ~B & ~C))`
3. **Y**<sub>7</sub> = `~(~(~A & B & C) & ~(~A & B & C) & ~(~A & ~B & C) & ~(~A & ~B & ~C))`

#	QS6

1.	**Y**<sub>8</sub> = `((((A|A)|B)|(A|A)|B))) | (((A|A)|B)|(A|A)|B))))`
	<details>
	<summary>&shy;</summary>
	> <code>(A & ~B)
	(~~A & ~B)
	~(~A ∨ B)
	~(((A|A)|B)|(A|A)|B)))
	((((A|A)|B)|(A|A)|B)))|(((A|A)|B)|(A|A)|B))))</code>
	</details>

2.	**`(A ∨ ∼B)           = ((A | (B | B)) | (A | (B | B)))`**

		1. ~B             = (B | B)                         (N)
		2. (A ∨ ∼B)       = (A ∨ (B | B))                   (S) 1
		3. (A ∨ (B | B))  = ((A | (B | B)) | (A | (B | B))) (D)
		4. (A ∨ ∼B)       = ((A | (B | B)) | (A | (B | B))) (T) 2, 3

#	QS7

1.	

		1 = (AvBv~Av~B)
		3 = (Av~B)
		4 = ((A&B)v(A&~B))
		5 = ~(A&~B)
		6 = ((~A&B)v(A&B))
		7 = ((A&B)v(~A&~B))
		9 = ~(A&B)
		10 = ((A&~B)v(~A&B))
		11 = ~B
		12 = (A&~B)
		13 = ~A
		14 = ~(Av~B)
		15 = ~(AvB)
		16 = ~(AvBv~Av~B)

2.	<code>n<sup>4</sup></code>