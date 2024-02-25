[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/wM4-KOzy)
# Little-o

In addition to the big-O, big-$\Omega$, and big-$\Theta$ notation that
we covered at the beginning of this class, a few other notations are sometimes
used in asymptotic analysis.  For example, "little-$o$" notation.

Prove (i.e.\ give a formal mathematical proof) that $f(n)\in o(g(n))$ implies
that $f(n)\in O(g(n))$.

Hint: The proof will be *very* short and *very* easy. You can start by
identifying the differences between the definitions of O and o.

I have started with the formal definition of $o$ below. Add your answer to this
markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$f(n)\in o(g(n)) \iff \forall c>0, \exists n_0, \forall n\ge n_0: f(n) < c g(n)$

Definition of little O : $f(n) \in o(g(n)) \iff \forall c>0, \exists n_0, \forall n\ge n_0: f(n) < c g(n)$

For all implies there exists: $\forall c>0 \implies \exists c>0 $.

< will always exist in <= : $f(n) < c g(n) \in f(n)\le c g(n)$

Definition of Big O: $f(n) \in O(g(n)) \iff \exists c>0, \exists n_0, \forall n\ge n_0: f(n)\le c g(n)$.

Proved by self implication / propositional logic: $f(n) \in o(g(n)) \implies f(n) \in O(g(n))$

If f(n) is less than c g(n), then f(n) will always be <= g(n) because if somethings less than, than those values also belong to less than or equal to. Additionally if for all constant values
the definition holds true, then that means that there will exists a value.

