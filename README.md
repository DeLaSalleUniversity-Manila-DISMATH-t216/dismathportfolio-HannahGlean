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
     
c.

   c.1 <b> VACUOUS PROOF </b>
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
       BASIS STEP: 
        <li> Specify the value of the function at zero.
       RECURSIVE STEP:
        <li> Give a rule for finding its value at an integer from its values at smaller integers. 
        
<li> Examples were given such as:
       Find f(1), f(2), f(3), f(4)
        f(0) = 3
        f(n+1) = 2f(n) + 3
        f(0+1) = 2(3) + 3 = 9
        f(1+1) = 2(9) + 3 = 21
        f(2+1) = 2(21) + 3 = 45
        f(3+1) = 2(45) + 3 = 93
        f(4+1) = 2(93) + 3 = 189
       
       Give a recursive definition of a_n, where a is a nonzero real number and n is a nonnegative integer.
        BASIS:
           0 or 1 f(0) = a^0 = 1
        INDUCTIVE/RECURSIVE:
           a^n = f(n) = f(n-1) * a
           a^1 = f(n+1) = f(n) *a
               = a^n * a
               = a^(n+1)
               
 <li> <b> Recursive Algorithms </b> solves a problem by reducing it to an instance of the same problem with smaller input.
         Examples:
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
   <br>      
    <li> <b> Venn Diagrams </b>
     
          1. UNION - A ∪ B
             - consists of all element from sets A and B
             
          2. INTERSECTION - A ∩ B
             - consists of only common elements in sets A and B
   
          3. DIFFERENCE - A - B or A \ B
             - consists of elements from sets A and B but not their intersection
             
          4. SYMMETRIC DIFFERENCE - A ∆ B
             - consists of elements from sets A and B but not their intersection
             
            </br>
            
  <li> <b> SET IDENTITIES </b> were also discussed.
     
 **SET IDENTITIES TABLE**

|  **LAW**  |  **IDENTITY**  |
| :------: | :-----------------------------: |
|  Identity Laws  |  A ⋂ U ≡ A  <br>  A ⋃ ∅ ≡ A  |
|  Domination Laws  |  A ⋃ U ≡ U  <br>  A ⋂ ∅ ≡ ∅  |
|  Idempotent Laws  |  A ⋃ A ≡ A  <br>  A ⋂ A ≡ A  |
|  Complementation Law  |  (A¯)‾ ≡ A  |
|  Commutative Laws  |  A ⋃ B ≡ B ⋃ A  <br>  A ⋂ B ≡ B ⋂ A  |
|  Associative Laws  |  A ⋃ (B ⋃ C) ≡ (A ⋃ B) ⋃ C  <br>  A ⋂ (B ⋂ C) ≡ (A ⋂ B) ⋂ C  |
|  Distributive Laws  |  A ⋃ (B ⋂ C) ≡ (A ⋃ B) ⋂ (A ⋃ C) <br>  A ⋂ (B ⋃ C) ≡ (A ⋂ B) ⋃ (A ⋂ C)  |
|  De Morgan's Laws  |  (A ⋂ B)‾ ≡ A‾ ⋃ B‾  <br>  (A ⋃ B)‾ ≡ A‾ ⋂ B‾  |
|  Absorption Laws  |  A ⋃ (A ⋂ B) ≡ A  <br>  A ⋂ (A ⋃ B) ≡ A  |
|  Complement Laws  |  A ⋃ A‾ ≡ U  <br>  A ⋂ A‾ ≡ ∅  |

<li> <b> SUBSETS </b> - A set S is a <b> <i> subset </b>  </i> of a set T (denoted S ⊆ T) if all elements of S are also elements of T.
      ex. 
      - {1,2,3} ⊆ {1,2,3,4}
      - ℕ ⊆ ℤ  (every natural  number is an integer)
      - ℤ ⊆ R (every integer is a mreal number)
      
      What are the subsets of {a,b,c}?
         - > It has eight (8) subsets:
             { {a}, {b}, {c}, {a,b}, }b,c}, {a,c}, {a,b,c}, {} }
             
 <li>> <b> POWER SET </b> - a set of all subsets
    <li> P(S) = {T|T ⊆ S}
    
 <li> <b> CARDINALITY </b> - number of elements it contains
                           - If S is a set, we denote its cardinality by writing |S| 
    
    ex.
    <li>  The cardinality of N. What is |N|?
         - There are infinitely many natural numbers.
      
    <li>  Infinite Cardinalities - alpha-null (0,1,2,3....)
    
   
# WEEK 9 

 - <b> FUNCTIONS </b>
    - Let A and B be sets. A function from A to B is an assignment of exactly one element of B to each element A.
    - They are also called MAPPINGS or TRANSFORMATIONS. <br>
    - f: A to B </br> <br>
       - A: domain </br>
       - B: co-domain
      
        - Range - actually occuring values 
        - IMAGE 
             - If _f(a) = b_, _b- is the image of _A_. 
             - The range of _f_ is the set of all images of elements of _a_. 
             
    - <b> TYPES OF FUNCTIONS: </b>
        - <i> ONE - TO - ONE FUNCTION (INJECTIVE) </i> - It never assigns the same value to two different domain elements.
         - ex. f = { (a,4), (b,5), (c,1), (d,3) }
          - <i> note: f = { (a,4), (b,5), (c,1), (d,3) } is NOT THE SAME with f = { (4,a), (5,b), (1,c), (3,d) }
        - No value in the range is used by more than one value in the domain.
         - ex. f: ℤ to ℤ
               f(x) = x^2 
                   <i> The function is one-to-one! </i>
        - <i> ONTO FUNCTION (SURJECTIVE) </i> - function have equal range and codomain.
        - <i> ONE-TO-ONE CORRESPONDENCE (BIJECTIVE) </i> - function is both ONE-TO-ONE and ONTO.
        
        - FUNCTION OR NOT?
           -  f = { (a,2), (b,1), (c,2), (d,3), (4), (5) }
               - FUNCTION BUT NEITHER ONE-TO-ONE NOR ONTO!
           - f: y = sqrt(x)
               - FUNCTION! In programming, we limit the output to positive only.
               
     - <b> ALGORITHM </b>
            - a finite set of precise instructions for performing a computation or for solving a problem.
         - <i> PROPERTIES OF ALGORITHM </i>
           - INPUT - has input values from a specified set 
           - OUTPUT - solution to the problem 
           - DEFINITENESS - defined precisely 
           - CORRECTNESS - produce the correct output values 
           - FINITENESS - produce the desired output
           - EFFECTIVENESS - perform exactly and in a finite amount of time 
           - GENERALITY - applicable for all problems of the desired form
           
              - ex. - Input: ({a1, a2, a3,..,an} ∈ , Z)
              - Output: largest 8
              - Pseudocode
            
                > max = a1; </br>
                > for i: 2 to n { </br>
                >   if(max < ai) </br>
                >       max = ai} </br>
           
     - <b> PSEUDOCODE </b>
            - the high-level description of an algorithm that uses the structural convention
            - intended for human reading
          - PRECONDITIONS - describe valid input
          - POSTCONDITIONS - conditions that the output should satisfy
          
       - <b> SEARCHING ALGORITHMS </b>
          - The problwem of locating an element in an ordered list.
          - Locate an element x in a list of distinct elements a1, a2,... an, or determine that it is not in the list
            - x - element that is searched. Therefore, it is included in the input.
            - ouput: location, i; loc = i if found, loc = -1 if not found
      
                > i=0 </br>
                > while(i < n and x!=a1) </br>
                >   i=i+1 </br>
                > if i < n then loc = i </br>
                > else loc = -1 </br>
# WEEK 10
            
       - <b> BINARY SEARCH PSEUDOCODE </b> 
          - comparison of the middle values of a list until the desired output is found.
          
       - <b> SORTING ALGORITHMS </b>  
          - problem of assorting elements into increasing order
          - 
       - <b> BUBBLE SORT </b>
          - compares the first two elements then interchanging them if they are in the incorrect order
          
       - <b> INSERTION SORT </b>
          - compares the second element with the first and inserts it before the first element if it is less
          - Otherwise, it is inserted after the first element.

       - <b> GREEDY ALGORITHMS </b> 
          - selects the best choice at each step, instead of considering all sequences that may lead to an optimal solution
          - applied in optimization problems where a solution to the given problem either minimizes or maximizes the value of some parameter
       - <b> The Complexity of Algorithm </b> and <b> BIG-O NOTATION </b> were introduced.
       
# WEEK 11
  - <b> BIG-O NOTATION </b>
     - upper-bound notation
     - f(x) is less than or equal to C(g(x))
     
  - <b> GROWTH OF FUNCTIONS </b>
     - often described using Big-O Notation
     - definition: Let f and G be functions from R to R; f(x) is O(G(x)) if there are constants C and k.
     - WITNESSES: C and k
      > ex. Show that 7x^2 is O(x^3)
        > 7x^2  ≤ C (x^3)
        > ln = 2
        > 7(2^2) = C (2^3)
        > 28 = 8C
        > C = 3.5 and k = 2
   
   - <b> BIG-OMEGA and BIG-THETA NOTATION </b>
       - Big-O Notation does not provide a lower bound for the size of f(x)
          - For LOWER bounds, we use <b> BIG-OMEGA notation </b>
          - For LOWER and UPPER bounds, we use <b> BIG-THETA notation </b>
           
   - <b> ALGORITHM TIME COMPLEXITY </b>
        - can be expressed in terms of the number of operations used by the algorithm when the input has a particular size
        - the number of comparisons will be used as a measure of time complexity of the algorithm, because comparisons are the basic operations used.
  
   - <b> DIVISION and MODULO OPERATOR </b> 
        - Let a be an integer and d a positive integer. Then there are unique integers q and r, with 0 ≤ r < d, such that a = dq + r
        - q = a div d
        - r = a mod d
           - note: d - divisor, a - dividend, q - quotient, and r - remainder
         > ex. What are the quotient and remainder when 101 is divided by 11?
           > 101 div 11 = 9
           > 101 mod 11 = 2
         > ex. What is the quotient and remainder when -11 is divided by 3?
           > -11 div 3 = -4
           > -11 mod 3 = 1, since r cannot be negative.
         - APPLICATIONS:
             - Cryptology - the study of secret messages
 
