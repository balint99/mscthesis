# Master's thesis project at Radboud University Nijmegen.

I studied normalization for the simply typed lambda calculus. The goal of the thesis was to give an overview and comparison of different *reduction-free* normalization techniques.
Reduction-freeness means that the proofs do not mention any notion of term-reduction, and do not make use of term-rewriting systems.
Instead, we define normal forms inductively, and show that every term is convertible (in the equational theory of lambda calculus) to a normal form.

We consider three normalization proofs for the simply typed lambda calculus. The first one is a modification of Tait's [[1]](#Tait) proof employing *logical predicates*, i.e. a family of 
type-indexed predicates on lambda terms defined inductively on types. The second one is a version of *normalization by evaluation*, originally invented by Berger and Schwichtenberg [[2]](#nbe),
which provides a *normalization function* that computes the normal form of a given term by evaluating it in a suitable model. The third proof is a categorical reconstruction
of normalization by evaluation using the *Artin-gluing* construction, building heavily Fiore's [[3]](#gluing) work.
The main message of the thesis is that there are close structural analogies between these three proofs.

## References

<a id="Tait">[1]</a>
William W. Tait.
Intensional interpretations of functionals of finite type I.
The Journal of Symbolic Logic, 32(2):198-212, 1967.

<a id="nbe">[2]</a>
Ulrich Berger and Helmut Schwichtenberg.
An inverse of the evaluation functional for typed lambda-calculus.
In Proceedings of LICS '91, pp. 203-211, 1991.

<a id="gluing">[3]</a>
Marcelo Fiore.
Semantic analysis of normalisation by evaluation for typed lambda calculus.
In Proceedings of PPDP '02, pp. 26-37, 2002.
