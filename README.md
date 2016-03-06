# dismathportfolio-HannahGlean
dismathportfolio-HannahGlean created by Classroom for GitHub

# WEEK 1 
<ul> 
<li> When I first heard of Discrete Mathematics(or DISMATH), I had no idea what it meant. </li>
<li> I asked my friends from higher batch and they told me that it is mostly about logic. </li>
<li> When I learned that it was all about logic, I thought it was the same kind of logic we had in high school and during the entrance exams.</li>
<li> As Sir Cabatuan further explained to us the subject, the more it became challenging. </li>
<li> After the first week, I am already expecting that DISMATH will be one of my most challenging subjects; but with hard work and commitment
I know that I will be able to pass this subject. </li>

# WEEK 2
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

<li> <b> Implication Equivalence </b>: p → q ≡ ¬p ∧ q
<li> Sir Cabatuan gave several examples concerning Logical Equivalences and it made the topic easir to understand.


# WEEK 3
<li> <b> PROPOSITIONAL LOGIC </b> deals with propositions as a whole { subject + predicate }
<li> <b> Predicate Logic </b> is concerned with their internal structure in terms of subject and predicate.
<li> <b> Quantifiers </b> indicates the generality of the open sentence in which a variable occurs.
<li> <b> Existential Quantifier ( ∃x ) </b> indicates "there exists".
<li> <b> Universal Quantifier ( ∀x ) </b> indicates "for all".
<li> <b> RULES OF INFERENCE </b> were also introduced. They are composed of:


|   **Rule of Inference**  |            **Tautology**           |          **Name**          |
|:--------------------|:------------------------------:|:----------------------:|
|       p<br>p→q<br>∴ q      |        (p ∧ (p → q)) → q       |      Modus Ponens      |
|     ¬q<br>p→q<br>∴ ¬p     |       (¬q ∧ (p → q)) → ¬p      |      Modus Tollens     |
|     p→q<br>q→r<br>∴ p→r    |  ((p → q) ∧ (q → r)) → (p → r) | Hypothetical Syllogism |
|      p∨q<br>¬p<br>∴ q      |       ((p ∨ q) ∧ ¬p) → q       |  Disjunctive Syllogism |
|       p<br>∴p ∨ q       |           p → (p ∨ q)          |        Addition        |
|       p ∧ q<br>∴ p       |           (p ∧ q) → p          |      Simplication      |
|      p<br>q<br>∴ p ∧ q     |      ((p) ∧ (q)) → (p ∧ q)     |       Conjunction      |
| p ∨ q<br>¬p ∨ r<br>∴ q ∨ r | ((p ∨ q) ∧ (¬p ∨ r)) → (q ∨ r) |       Resolution       | 

<li> Since some arguments have several variables, using the rules of inference rather than the truth table will save much time and effort.
<li> An <b> argument </b> is a sequence of statements that end with a conclusion. 
<li> <b> Validity </b> is dependent of the structure. It assures that the conclusion is true if and only if all the premises are true.
<li> A <b> fallacy </b> is a common form of incorrect reasoning.
<li> A <b> tautology </b> is a statement or proposition that is always true.

# WEEK 4
<li> The tools that can be used to prove the validity of an argument are:
1. Truth Table
2. Logical Equivalences
3. Quantifiers
4. Rules of Inference

<li> Rules of Inference were further discussed and examples were shown.
<li> Example:
Let
<li> s = "It is sunny this afternoon"
<li> c = "It is colder"
<li> w = "We will go swimming"
<li> t = "We will take a canoe trip"
<li> h = "We will be home by sunset"
<li> The premises stated were:
1. ¬s ∧ c
2. ¬s → ¬w
3. ¬w → t
4. t → h
<li> ∴ h
<li> To prove it using Rules of inference
<li> ¬s (Simplification of Premise 1)
<li> w → s
<li>  ∴ ¬w   (m.t.)
<li>    ¬w → t 
<li>     ∴ t   (m.p.)
<li>       t → h
<li>        ∴ h   (m.p)

# WEEK 5
<li> The topic this week was <b> "METHODS OF PROOFS". </b>
a. <b> DIRECT PROOF </b>
     1. Assume p is true (T).
     2. Show that q is also true (T).
     
b. <b> CONTRAPOSITION </b>
     1. Assume ¬q is true (T).
     2. Show that ¬p is also true (T).
     
c. c.1 <b> VACUOUS PROOF </b>
     Show that p is false, because p → q must be true when p is false.

   c.2 <b> TRIVIAL PROOF </b>
     Show that q is true, it follows that p → q must also be true.
    
d. <b> PROOF BY CONTRADICTION </b>
     1. Assume that the premise is not true. 
             ¬ (premise) is true.
     2. Show that 1 will end up in a contradiction.
     
e. <b> PROOF BY EQUIVALENCE </b>
     To prove a theorem that is a biconditional statement, p → q, we show that p → q and q → p are true (T).
     

# WEEK 6
<li> We further discussed the Methods of Proofs.
<li> <b> Proof by Counterexample </b> was introduced to us in the example:
    "Every positive integer is the sum of the squares of two integers."
       The counterexample given were 3, 6, 7, and 10 since they are not a sum of squares of two integers.
<li> It is sometimes hard to determine what method should one use for a certain argument but having many examples and reading further for each of the methods helps.

<li> We started tackling <b> MATHEMATICAL INDUCTION </b>.
   Methods used are:
     1. SUBSTITUTION
     2. DIRECT PROOF
     
   BASIS: 
     Show P(1) or P(0) to be true.
       DIRECT PROOF
         a. Assume P(k) ≡ T
         b. Show P ( k + 1 ) ≡ T
         
# WEEK 7
<li> <b> Summation </b> was tackled. 
<li> The notation for a_m , a_m+1 , … , a_n is:
      <li> ∑_(i=m)^n▒a_i , ∑_(i=m)^n▒a_i  , ∑_(1≤i≤n)▒a_i , or ∑_( a ∈ S)▒a
             where <b>i</b> = index of summation
<li> <b> Recursive/Inductive Definition</b>
  <li> BASIS STEP: 
        <li> Specify the value of the function at zero.
  <li> RECURSIVE STEP:
        <li> Give a rule for finding its value at an integer from its values at smaller integers. 
<li> Examples were given such as:
   <li> Find f(1), f(2), f(3), f(4)
        f(0) = 3
        f(n+1) = 2f(n) + 3
        f(0+1) = 2(3) + 3 = 9
        f(1+1) = 2(9) + 3 = 21
        f(2+1) = 2(21) + 3 = 45
        f(3+1) = 2(45) + 3 = 93
        f(4+1) = 2(93) + 3 = 189
   <li> Give a recursive definition of a_n, where a is a nonzero real number and n is a nonnegative integer.
        BASIS:
           0 or 1 f(0) = a^0 = 1
        INDUCTIVE/RECURSIVE:
           a^n = f(n) = f(n-1) * a
           a^1 = f(n+1) = f(n) *a
               = a^n * a
               = a^(n+1)
 <li> <b> Recursive Algorithms </b> solves a problem by reducing it to an instance of the same problem with smaller input.
 <li> Examples:
   <li> What is the recursive algorithm for computing n!?
             factorial (n = nonnegative integer) {
                if (n == 0)
                    return 1;
                else 
                    return n*factorial
                               (n-1);
             }
   <li> Give a recursive algorithm for computing a^n, where a is a nonzero real number and n is a nonnegative integer.
             power (a | a ≠ 0)
                     a ∈ R ;
                     n ∈ N ;
                if (n == 0)
                     return 1;
                else
                     return power (a, n-1) * a
 <li> <b> Program Correctness </b> is necessary to show that the program always gives the correct output.
      <li> <b> Partial Correctness </b> 
                1. <i> Initial Assertion (p) </i> - gives the properties that the input values must have
                2. <i> Final Assertion (q) </i> - gives properties that the output of the should have, if the program did what was intended
      <li> <b> Hoare Triple p{S}q </b> is said to be partially correct with respect to the inital assertion p and the final assertion q if whenever p is true for the input value of S and S terminates, then q is true for the output values of S. 
      
               <b> Rules of Inference </b>
                   <li> COMPOSITION RULE
                            p {S_1} q
                            q {S_2} r
                           -----------------
                           ∴ p {S_1, S_2} r
                   <li> CONDITIONAL STATEMENT
                            (p ^ condition) {S} q
                            (p ^ ¬condition) → q
                           -----------------------
                            ∴ p {if condition then S} q
                              Case I: condition ≡ T ( p ^ condition) {S}q
                              Case II: condition ≡ F (p ^ ¬condition)
                   <li> IF-ELSE STATEMENT
                            (p ^ condition) {S_1} q
                            (p ^ ¬condition) {S_2} q
                           -------------------------------------
                            ∴ p {if condition then S_1 else S_2} q
 <li> <b> Representations of Functions as Power Series </b>
          ∑_(n=0)^∞▒a_(x  )  x^n
             <li> Example:
                 1 + r + r^2 + r^3 + ... = 1/1-r
                   for r < 1
                   f(x) = 1/1-x = ∑_(n=0)^∞▒x_(n  ) = 1 + x + x^2 +...
                   
                  
                  1/1+x = 1 - x + (-x)^2 + (-x)^3 ... + (-x)^n
                        = 1 - x^2 + x^4 - x^6
                        
# WEEK 8
 <li> <b> INTRODUCTION TO SET THEORY </b>
    <li> We defined <b> set </b> as an unordered collection of distinct objects, which may be anything (including other sets)
    <li> Order does not matter in a set.
  <li> ∅ and {∅} are NOT EQUAL! Since it is an empty set, there should not be any element inside the set.
      Just like how 3 an {3} are NOT EQUAL. 
            3 is a number while {3} is a set containing a number.
    <li> <b> Set Builder Notation </b>
         { x | some property x satisfies }
     
     <li><b> Venn Diagrams </b>
          1. UNION - A ∪ B
          2. INTERSECTION - A ∩ B
          3. DIFFERENCE - A - B or A \ B
          4. SYMMETRIC DIFFERENCE - A ∆ B
          
          
