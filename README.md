# dismathportfolio- ImanSM
Don Santamaria's Dismath Portfolio

##  Welcome to my DISMATH Portfolio 
![Welcome](http://namiboise.org/wp-content/uploads/2015/10/welcome.jpg)
### Week 1:
* It's the start of a new journey, and a new subject was introduced. A jolly and happy professor introduced us this new subject called **DISMATH**(Discrete Mathematics). His Name is Sir **Melvin Cabatuan**.

* From his introduction I realized this subject wouldn't be the typical "Solve this using that" or "Integrate that with this". It is a rather unique subject which tests our capability to *think deeper and outside the box*.

* Topics to be covered include: constructing proofs, logical equivalences, rules of inferences, algorithm pseudocodes, etc. These topics sound so complicated already, so I did some advanced study on the first few topics.

* DISMATH deals only with **mathematical truth**. So I guess I have to forget all other truths while in this class.

* I learned(more) about propositions, propositional logic and logical operators. I also learned proving via truth table. This one is quite easy, but it could get complicated if there are many variables. There were also new symbols introduced, each corresponding to a logical operator. Refer to table.

| Logical Symbol  |  Logical Operator | Shorthand | Formula | Logical Expression |
| :-----: |:-------:|:-----:| :-------: | :-------: |
| ¬ |Negation | not | val(¬p) = 1 - val(p) | ¬p |
| ∧ | Conjunction | and | val(p ∧ q) = min(val(p), val(q)) | p ∧ q |
| v | Disjunction | or | val(p v q) = max(val(p), val(q)) | p v q |
| ⊕ | Exclusive disjunction | xor | if val(p)  not equal val(q) = 1 , otherwise  0|  p ⊕ q  ≡ (¬p ∧ q) v (p ∧ ¬q) |
| → | Conditional | if, then | if val(p)  ≤ val(q) = 1 , otherwise  0  | p → q ≡  ¬p v q |
| ↔ | Biconditional | iff | if val(p) equals val(q) = 1 , otherwise  0 |  p ↔ q ≡ (p → q) ∧ (q → p) |

*(c) Sir Melvin*

* Overall, week 1 was quite challenging. I began to realize that this subject must not be taken lightly. On to week 2. 

![Week1](https://s-media-cache-ak0.pinimg.com/736x/d5/b9/2e/d5b92eaaf8712c78966fd71c8cc7a83b.jpg)

###Week 2:
*Dismath just keeps getting more complicated. I learned about logical equivalences. These equivalences are like a set of laws and identities. For example, in trigonometry sin(x) = 1/csc(x), then p ∧ p = p. Quite cool. Here is the full list:

| Name  |  Logical Equivalences |
| :-----: |:-------:|
| Identity Laws |  p v F = p |
                | p ∧ T = p |
| Domination Laws | p v T = T |
                  | p ∧ F = F |
| Negation Laws | p v ¬p = T |
                | p ∧ ¬p = F |
| Double Negation | ¬(¬p) = p |
| Idempolent Laws | p v p = p |
                  | p ∧ p = p |
| Commutative Laws | p v q = q v p |
                   | p ∧ q = q ∧ p |
| Associative Laws | (p v q) v r = p v (q v r) |
                   | (p ∧ q) ∧ r = p ∧ (q ∧ r) |
| Distributive Laws | p v (q r) = (p v q)  (p v r) |
                    | p ∧ (q v r ) = (p ∧ q) v (p ∧ r)
| DeMorgan's Laws | ¬(p ∧ q) = ¬p v ¬q |
                  | ¬(p v q) = ¬p ∧ ¬q |
| Absorption Laws | p v (p ∧ q) = p |
                  | p ∧ (p v q) = p |

* We also learned how to prove logical statements using logical equivalences. Very useful when you can't apply the truth table. But then again, you need to be good at logic and you should've memorized the table above. Sad.

* To spice up this week Sir Melvin gave us an assignment about superman! I then discovered a horrible truth, that the man of steel doesnt exist...logically speaking.

* We also dealt with other things like *Predicate logic* and *Propositional logic*

* Then we started with quanitifiers, namely:

1. Existential Quantifier (∃x)
         " There exist " - if and only if P(x) is true for at least one value of x in the domain.
2. Universal Quantifier (∀x)
         " For All " -  property is true for all values of a variable in a particular domain.

* Week 2 was nice, but I miss week 1 since it was less complicated. Oh well, better get used to this. Week 3 here i come!!

RIP Superman :(

![RIP](http://static.comicvine.com/uploads/scale_medium/8/83392/1641112-35817_4571_39991_1_superman_the_man_of_super.jpg)

###Week 3

* New week new topic. I learned about the *rules of inference*.

* Had enough of tables? Oh wait. There's more!

|         Name         |   Rule of Inference  |            Tautology           |
|:--------------------:|:--------------------:|:------------------------------:|
|    Modus Ponens      |      p, p→q ∴q       |        (p ∧ (p → q)) → q       |
|      Modus Tollens   |     ¬q, p→q ∴ ¬p     |       (¬q ∧ (p → q)) → ¬p      |
|Hypothetical Syllogism|     p→q, q→r ∴p→r    |  ((p → q) ∧ (q → r)) → (p → r) |
|Disjunctive Syllogism |      p∨q, ¬p ∴q      |       ((p ∨ q) ∧ ¬p) → q       |
|      Addition        |       p ∴p ∨ q       |           p → (p ∨ q)          |
|      Simplication    |       p ∧ q ∴p       |           (p ∧ q) → p          |
|       Conjunction    |      p, q ∴p ∧ q     |      ((p) ∧ (q)) → (p ∧ q)     |
|      Resolution      | p ∨ q, ¬p ∨ r ∴q ∨ r | ((p ∨ q) ∧ (¬p ∨ r)) → (q ∨ r) |

* Sir Melvin also introduced to us methods of proof.

* The First one is Direct Proof.
- I. **Direct Proof**.
- Steps:
  *   1. Assume *p* is True.
  *   2. Show that *q* is also True.

* I also learned how to define an odd and even number.
      1.Odd number, 2k+1, where k is an integer
      2.Even number, 2k, where k is an integer
* 3 weeks and we already have 3 tables to memorize. Oh well, guess we just have to keep studying. I can't find an image to discribe this week so let's leave it at that.

###Week 4

*This week was all about methods of proofs Oh come on.
- II. **Proof by Contraposition**.
- Steps:
  *   1. Assume *¬q* is True
  *   2. Show that *¬p* is also True.
- III. **Vacuous Proof**.
- Which is basically ¬p → (p→q)
- Steps:
  *   1. Show that *¬p* is True **OR** *p* is False.
  *   2. *p→q* is True when *¬p* is **OR** *p* is False.
- IV. **Trivial Proof**
- Basically, q → (p→q)
- Steps:
  *   1. Show that *q* is True.
  *   2. p→q is therefore True when *q* is True.
- V. **Proof by Contradiction**
- Prove that the premises will end up FALSE or in Contradiction
- Steps:
  *   1. Assume **ALL PREMISES** to be FALSE.
  *   2. Show that these premises will end up in a Contradiction.

*Here again I thought I knew all the basic concepts about math, but I just learned what a rational number is. To define:
      1.The real number *r* is *rational* if there exist integers p and q with q≠0 such that **r = p/q**. Otherwise, it is an *irrational number*.
      2. Q = {a/b | a, b ∈ ℤ} where b≠0, a & b have no common factor other than ±1
      
* Wow, there are so many ways to prove stuff. Can this help prove satoru's innocence? I guess not. But it can help me prove other things especially questions during the quiz.
Satoru-san Will I be able to memorize all this for quiz 1? Satoru-san doesnt approve.

![REVIVAL](https://i.ytimg.com/vi/WJqgDeKoWEU/maxresdefault.jpg)

###Week 5
- VI. **Proof by Equivalence** (Biconditionals):
  - P ↔ Q ≡ (P → Q) ∧ (Q → P)
  - Steps:
    - Show P → Q is True.
    - Show Q → P is True.
  - *Substitution* is not considered a proof.
- VII, **Mathematical Induction**:
  - Steps:
    1. Show P(1) or P(0) to be True.
    2. Assume P(k) is True.
    3. Show P(k+1) to be True.

###Week 6

*Last few topics before quiz 1. Complicated.

- I. **Summation**
  - The notation for sum of am, am+1, ..., an is ∑ai=m ai where i is the index of summation.
    -   Example: ∑ai=m = 1 + 2 + 3 + ... + n

- II. **Recursive/Inductive definition**
  - Basis step: Specify the value of the function at zero
  - Recursive step: Give a rule for finding its value at an integer from its values at smaller integers
    - Example: Find f(1), f(2), f(3), f(4) of the following recursive function.
- III. **Recursive algorithms**

  - It solves a problem by reducing it to an instance of the same problem with smaller input.
  - Recall that: Algorithm - finite set of precise instructions for performing a computation/solving a problem.
    -Examples: Give a recursive algorithm for n!
- IV. **PROGRAM CORRECTNESS**
  - Definition: We need proof to show that the program always gives the correct output.
    - *PROGRAM VERIFICATION*
      - Proof of correctness of programs
      - Uses the rules of inference and various proof techniques including mathematical induction
      - It is said to be correct if it produces the correct output for every possible input
    - *PARTIAL CORRECTNESS*
      - Two propositions are used to specify what it means for a program to produce the correct output:
      - Initial Assertion - p - gives the properties that the input values must have
      - Final Assertion - q - gives the properties that the output of the program should have, if the program did what it was told
 
* NOTE:(1 absence) - Missed topics
* It's quiz time, and i'm ready to suffer.

![Q1](http://www.myenglishteacher.eu/blog/wp-content/uploads/2014/10/quiz-1.jpg)

###Week 7

*As expected, Quiz 1 was hell, what more for quiz 2? Sad la.

*New week, new topics. Move on.

- I. **SET THEORY**
  - A set is an unordered collection of distinct objects, which may be anything (including other sets).
  - Ex: {ims,iman,food,Don,Emmanuel} 
  - Set Notation: curly braces with commas separating out the elements
  - {iman, iman, iman, food, sleep} is equal to {iman,food,sleep}
  * Empty set:  { } = ∅
  * Set Builder Notation 
  * {x | some property x satisfies}

* Question: Is ∅ = {∅}? 
* Answer: Lol NOPE

- II. **Venn Diagrams**

* Venn Diagrams, like those in high school.
* 
### Week 8:

* **ALGORITHMS**
    - A finite set of precise instructions for performing a computation or for solving a problem.
    - **Properties of Algorithms**: </br>
        ⇾ _Input_ - has input values from a specified set </br>
        ⇾ _Output_ - solution to the problem </br>
        ⇾ _Definiteness_ - defined precisely </br>
        ⇾ _Correctness_ - produce the correct output values </br>
        ⇾ _Finiteness_ - produce the desired output </br>
        ⇾ _Effectiveness_ - perform exactly and in a finite amount of time </br>
        ⇾ _Generality_ - applicable for all problems of the desired form
* **PSEUDOCODE**
    - high - level desciption of an algorithm that uses the structural conventions of a programming language 
    - intended for human reading
    - **Preconditions** - describe valid input
    - **Postconditions** - conditions that the output should satisfy

* Sir Melvin also said something about Google's algorithm. Pretty cool.

![Google](http://searchengineland.com/figz/wp-content/seloads/2014/09/google-blueg-algorithm-seo-ss-1920.jpg)



### Week 9:

- For this week, we discussed the types of algorithm procedures that we can use when writing a pseudocode

* **SEARCHING ALGORITHMS** </br>
    ↳ Problem of locating an algorithm in an ordered list
    - **Binary Search** - comparing the middle values of a list then repeated until the desired output is found.

* **SORTING ALGORITHMS** </br>
    ↳ Problem of assorting elements into increasing order
    - **Bubble Sort** - compares the first two elements then interchanging them if they are in the incorrect order.
    - **Insertion Sort** - compares the second element with the first and inserts it before the first element if it is less. Otherwise, it is inserted after the first element.

* **GREEDY ALGORITHMS** </br>
    ↳ Algorithms that make what seems to be the "best" choice at each step.

- We also started on the **Growth of Functions** (Big-O Notation)

*Nope no image here*

### Week 10:

- We resume the discussion on the Growth of Functions.

* **Big-O Notation**
    - Let _f_ and _g_ be functions from R-R; _f(x)_ is _O(g(x))_ if there are constants _C_ and _k_ such that: </br>
        |f(x)| ≤ C|g(x)| </br>
    whenever _x > k_.

* **Big-Omega and Big-Theta Notation**
    - Big-O Notation does not provide a lowerbound for the size of f(x). </br>
        ↳ **Big-Omega** (Big-Ω) - lower bound </br>
        ↳ **Big-Theta** (Big-Θ) - both upper and lower bound


### Week 10:

- We resume the discussion on the Growth of Functions.

* **Big-O Notation**
    - Let _f_ and _g_ be functions from R-R; _f(x)_ is _O(g(x))_ if there are constants _C_ and _k_ such that: </br>
        |f(x)| ≤ C|g(x)| </br>
    whenever _x > k_.

* **Big-Omega and Big-Theta Notation**
    - Big-O Notation does not provide a lowerbound for the size of f(x). </br>
        ↳ **Big-Omega** (Big-Ω) - lower bound </br>
        ↳ **Big-Theta** (Big-Θ) - both upper and lower bound

### Week 11: HOLY WEEK


### Week 12:

* **Graph Theory**
    - Easiest coverage for the quiz
    - _Degree_ - number of degrees at a node/vertex
    - _Handshaking Theory_ - 2e = ∑deg(v)
    - _Path_ - sequence of edges travelling from vertex to vertex along the edges
    - _Euler Circuit_ - passess through every edge and goes back to starting point
    - _Euler Path_ - simple path containing every edge of the graph
    - _Hamilton Path_ - passes through every vertex
    - _Hamilton Circuit_ - passes through every vertex then goes back to the starting point
    - _Matrices of Graphs_ - 1 for adjacent; 0 for non-adjacent
    - _Incidence of Matrices_ - Matric between vertices and edges
    - _Isomorphism of Graphs_ - "rubberband"

* **Planar Graph**
    - no edges cross in a graph
    - _Euler's Formula_ - regions = edges - vertices + 2
    - _Euler's Characteristic_ - ℵ = regions - |edges| + |vertices| = 2

* **Homeomorphic Graphs**
    - can be obtained from the same graph by a sequence of elementary subdivisions
        - _Elementary Subdivision_ - everything is planar graph
    - _Kuratowski's Theorem_ - nonplanar if and only if it contains a subgraph homeophobic to K<sub>3,3</sub> and K<sub>5</sub>

*** QUIZ 3


*** Week 13:
- Last week of lessons before finals!

* **Graph Coloring**
    - assignment of a color to each vertex of the graph so that no two adjacent vertices are assigned the same color
    - _Four Color Theorem_ - the chromatic number of a planar graph is no greater than four

* **Trees**
    - connected undirected graph with no simple circuits
    - data structure that emulates a heirarchical tree structure with a set of linked notes
    - used to construct efficient algorithms for locating an item in a set
    - _Forest_ - multiple trees
    - _Rooted Tree_ - a tree in which one vertex has been designated as the root and every edge
        - leaves - nodes that do not have children
        - ancestors - nodes on top
        - descendants - children/grandchildren
    - _Subtree_
    - _M-ary tree_ - if every internal vertex has no more than m children
        - an m-ary tree with m = 2 is called a _binary tree_

* **Modeling Computation**
    - _Language and Grammars_
        - Grammars - used to generate the words of a language and to determine whether a word is in a language
        - Compiler - reads a program written in a source language and translate it into an equivalent program in a target language.
        - Formal Language - automatic translation of one language to another
            - well defined set of rules

* **Alphabet & String**
    - common way to talk about words, numbers, etc.

* **Automata Theory**
    - studies the law of computation
    - Finite Automata - simplest model of automata
        - initial state
        - final/acceptance state
        - dead/stuck state
        - transition

* **Lexical Analysis**
    - process where the stream of characters making up the source program into a sequence of "words" that make up the source code.

* **Finite State Machine**
