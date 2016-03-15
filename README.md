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

![Week1](http://images.sodahead.com/polls/001391923/jonbabypic_answer_2_xlarge.jpeg)

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
 
* That's all for now! :)
