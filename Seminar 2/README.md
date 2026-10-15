# Seminar 01 -- Logici clasice. Logici multivaluate

## 1. Proprietăți ale logicilor

a. Care e legătura între completitudine și decidabilitate? [O logică completă este neapărat și decidabilă](https://cdn.bookey.app/files/pdf/book/en/logicomix.pdf)?
b. Este logica propozițională booleană [decidabilă](https://iep.utm.edu/propositional-logic-sentential-logic/#H7)? 
c. Dar cea multivaluată? 
d. Este logica de ordinul întâi completă? Dar [decidabilă](http://kilby.stanford.edu/~rvg/154/handouts/fol.html)? 

## 2. [Algebre Boole](https://en.wikipedia.org/wiki/Boolean_algebra_%28structure%29)

a. Arătați că următoarele rezultate sunt echivalente, pentru orice elemente a și b într-o algebră Boole:

	i. a → b = b
	ii. b → a = a
	iii. a ∨ b = 1

b. Este afirmația adevărată pentru latici reziduate? 

## 3. [Latici reziduate](https://iphils.uj.edu.pl/~t.kowalski/monograph.pdf)

a. Impunând axiome suplimentare clasei laticilor reziduate, obținem mai multe subvarietăți interesante. Considerați următoarele axiome necesare pentru obținerea unor subvarietăți de latici reziduate non-triviale (cu elemente 0, 1), pentru orice elemente a, b dintr-o latice reziduată:

	- divizibilitate: a ∧ b = a ∗ (a → b)

	- preliniaritate/reprezentabilitate: (a → b) ∨ (b → a) = 1

	- liniaritate: a ≤ b sau b ≤ a

	- idempotență: a ∗ a = a

	- involuție: ¬¬a = a.

Folosiți aceste axiome pentru a descrie:

	i. algebrele Heyting ca latici reziduate	
	ii. MV-algebrele / algebrele Łukasiewicz ca latici reziduate
	iii. algebrele Gödel ca algebre Heyting
	iv. algebrele Boole ca algebre Heyting
	v. algebrele Boole ca MV-algebre.

	

b. Arătați că pentru orice a, b, c elemente într-o latice reziduată următoarele afirmații sunt adevărate:

	i. 0 * a = 0
	ii. 1 → a = a
	iii. a ≤ b iff a → b = 1
	iv. a * b ≤ a și deci a * b ≤ a ∧ b
	v. a → b = max{c: c * a ≤ b}



