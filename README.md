# dismathportfolio-HannahGlean
dismathportfolio-HannahGlean created by Classroom for GitHub

# Week 1 
<ul> 
<li> When I first heard of Discrete Mathematics(or DISMATH), I had no idea what it meant. </li>
<li> I asked my friends from higher batch and they told me that it is mostly about logic. </li>
<li> When I learned that it was all about logic, I thought it was the same kind of logic we had in high school and during the entrance exams.</li>
<li> As Sir Cabatuan further explained to us the subject, the more it became challenging. </li>
<li> After the first week, I am already expecting that DISMATH will be one of my most challenging subjects; but with hard work and commitment
I know that I will be able to pass this subject. </li>

# Week 2
<li> This week, our discussions officially started with <b>INTRODUCTION TO LOGICS AND PROOFS</b>. </li>
<li> We defined <b>proof</b> as a chain of logical deductions reading to the proposition from a base set of axioms. </li>
I have learned that:
<li> <b> Proposition </b> is a statement that is either true (1) or false (0).
<li> <b> Logical Deduction </b> is a process of reasoning from one or more statements (premises) to reach a logically certain conclusion. 
<li> <b> Axiom </b> is a statement or proposition that is regarded as being established, accepted, or self-evidently true.
<li> <b> LOGICAL CONNECTIVES </b> were also introduced to us:

| Logical Symbol  |  Logical Operator     | Shorthand | Formula                                       | Logical Expression            |
| :-------------: |:---------------------:|:---------:|:---------------------------------------------:|:-----------------------------:|
| ¬               | Negation              | not       | val(¬p) = 1 - val(p)                          | ¬p                            |
| ∧               | Conjunction           | and       | val(p ∧ q) = min(val(p), val(q))              | p ∧ q                         |
| v               | Disjunction           | or        | val(p v q) = max(val(p), val(q))              | p v q                         |
| ⊕               | Exclusive disjunction | xor       | if val(p) not equal val(q) = 1, otherwise 0   | p ⊕ q  ≡ (¬p ∧ q) v (p ∧ ¬q)  |
| →               | Conditional           | if, then  | if val(p) ≤ val(q) = 1, otherwise 0           | p → q ≡  ¬p v q               |
| ↔               | Biconditional         | iff       | if val(p) equals val(q) = 1, otherwise 0      | p ↔ q ≡ (p → q) ∧ (q → p)     |

<li> The <b> Truth Table </b> lists all possible inputs or combination of inputs with corresponding output. 
<li> We can determine the number of rows needed in a truth table by using 2^n with <b> n </b> representing the number of variables.
<li> We also discussed <b> LOGICAL EQUIVALENCES </b> which includes:

 
|  **LAW**  |  **EQUIVALENCE**  |
| :------: | :-----------------------------: |
|  _Identity Laws_  |  p ∨ F ≡ T  ;;  p ∧ F ≡ T  |
|  _Domination Laws_  |  p ∨ T ≡ T  ;;  p ∧ F ≡ F  |
|  _Negation Laws_  |  p ∨ ¬p ≡ T  ;;  p ∧ ¬p ≡ F  |
|  _Double Negation Law_  |  ¬(¬p) ≡ p  |
|  _Idempotent Laws_  |  p ∨ p ≡ p  ;;  p ∧ p ≡ p  |
| _Distributive Laws_  |  p ∨ (q ∧ r) ≡ (p ∨ q) ∧ (p ∨ r)  ;;  p ∧ (q ∨ r) ≡ (p ∧ q) ∨ (p ∧ r)  |
|  _Commutative Laws_  |  p ∨ q ≡ q ∨ p  ;;  p ∧ q ≡ q ∧ p  |
|  _Associative Laws_  |  (p ∨ q) ∨ r ≡ p ∨ (q ∨ r)  ;;  (p ∧ q) ∧ r ≡ p ∧ (q ∧ r)  |
|  _De Morgan's Laws_  |  ¬(p ∧ q) ≡ ¬p ∨ ¬q  ;;  ¬(p ∨ q) ≡ ¬p ∧ ¬q  |
|  _Absorption Laws_  |  p ∨ (p ∧ q) ≡ p  ;;  p ∧ (p ∨ q) ≡ p  |
