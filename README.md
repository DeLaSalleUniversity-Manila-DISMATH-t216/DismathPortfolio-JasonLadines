# DismathPortfolio-JasonLadines

#Week 1 
##(June 9, 2016)
On our first day of meeting, we were oriented about the course Discrete Mathematics. We also started with the first topic which is the proposition. A proposition is a declarative statement that is either true or false.

For our first exercise, each of us were given a question to be answered. The question that was asked to me was how to make the statement "x+9=11" a proposition. That statement is not a proposition since it can be true or false depending on the value of x. I was able to answer the questions by adding "...if x=2" to the statement. The statement "x+9=11 if x=2" is now a proposition since the statement becomes true.

We ended our first day of meeting with choosing a time and day schedule for our classes.

##(June 14, 2016)
LEAP Day (No Classes)

#Week 2 
##(June 16, 2016)
Our next meeting was the start of our official lesson. On this day, we discussed more about propositions. This included the different operations that can be used with the propositional variables. The following are the operations that can be used on propositional variables:

| Operation             | Logical Equivalent | Symbol | Definition                                       |
|-----------------------|--------------------|--------|--------------------------------------------------|
| Negation              | NOT                | ¬      | If p is T, ¬p is F                               |
| Conjunction           | AND                | ∧      | p ∧ q is T if p and Q is T                       |
| Disjunction           | OR                 | ∨      | p ∨ q is T if any of p or q or both is T         |
| Exclusive Disjunction | XOR                | ⊕      | p ⊕ q is only one of p or q is T                 |
| Conditional           |                    | →      | p → q is F if p is T and q is F                  |
| Biconditional         |                    | ↔      | p ↔ q is T if p and q have the same truth values |

In addition to these operations that can be used on propositions, we were also taught about the other forms that is related to conditional statements. These are:

| Operation      | Expression |
|----------------|------------|
| Converse       | q → p        |
| Contrapositive | ¬q → ¬p      |
| Inverse        | ¬p → ¬q      |

As a closing remarks for the first chapter of the book, some of us were asked some questions. I was asked the question, "What is the Bitwise OR of 01 and 11?" I was able to answer the question in which the answer is 10.

To test if we learned from the class today, each and every on of us answered some questions from the Chapter 1 Questions found in the book. The questions that I was able to asnwer are:

8.) Let p and q be the propositions:
p: I bought a lottery ticket this week.
q: I won the million dollar jackpot.
Express each of these propositions as an English sentence.
d.) p ∧ q
Answer: I bought a lottery ticket this week and won the million dollar jackpot.

11.) Let p and q be the propositions:
p: It is below freezing.
q: It is snowing
Write these propositions using p and q and logical connectives (including negotations).
c.) It is not below freezing and it is not snowing.
Answer: ¬p ∧ ¬q

13.) Let p and q be the propositions:
p: You drive over 65 milers per hour.
q: You get a speeding ticket.
Write these propositions using p and q and logical connectives (including negotations).
b.) You drive over 65 miles per hour, but you do not get a speeding ticket.
Answer: p ∧ ¬q

15.) Let p, q, and r be the propositions:
p: Grizzly bears hae been seen in the area.
q: Hiking is safe on the trail.
r: Berries are ripe along the trail.
b.) Grizzly bears have not been seen in the area and hiking on the trail is safe, but berries are ripe along the trail.
Answer: ¬p ∧ q ∧ r 
f.) Hiking is not safe on the trail whenever grizzly bears have been seen in the area and berries are ripe along the trail.
Answer: (p ∧ r) → ¬q

17.) Determine whether each of these conditional statements is true or false.
c.) If 1 + 1 = 3, then 2 + 2 = 5.
Answer: True

19.) For each of these sentences, determine whether an inclusive or. or an exclusive or, is intended. Explain your answer.
d.) You can pay using U.S. dollars or euros.
Answer: Either, since it depends on the rules in each country.

21.) For each of these sentences, state what the sentence means if the logical connective or is an inclusive or (that is, a disjunction) versus an exclusive or. Which of these meaning of or do you think is intended.
a.) To take discrete mathematics, you must have taken calculus or a course in computer science.
Answer: Inclusive-OR

25.) Write each of these propositions in the form "p if and only if q" in English.
c.) You get promoted only if you have connections, and you have connections only if you get promoted.
Answer: You get promoted if and only if you have connections.

29.) How many rows appear in a truth table for each of these compound propositions?
b.) (p ∨ ¬r) ∧ (q ∨ ¬s)

##Assigment No. 1:

31.) Construct a truth table for each of these compound propositions.
d.) p ∨ q) → (p ∧ q)  

| p | q | p ∨ q |  p ∧ q  | (p ∨ q) → (p ∧ q)  |
|---|---|-------|---------|--------------------|
| T | T | T     | T       | T                  |
| T | F | T     | F       | F                  |
| F | T | T     | F       | F                  |
| F | F | F     | F       | T                  |

33.) Construct a truth table for each of these compound propositions.
e.) (p ↔ q) ⊕ (¬p ↔ ¬r)

| p | q | r | ¬p | ¬r | p ↔ q | ¬p ↔ ¬r | (p ↔ q) ⊕ (¬p ↔ ¬r) |
|---|---|---|----|----|-------|---------|---------------------|
| T | T | T | F  | F  | T     | T       | F                   |
| T | T | F | F  | T  | T     | F       | T                   |
| T | F | T | F  | F  | F     | T       | T                   |
| T | F | F | F  | T  | F     | F       | F                   |
| F | T | T | T  | F  | F     | F       | F                   |
| F | T | F | T  | T  | F     | T       | T                   |
| F | F | T | T  | F  | T     | F       | T                   |
| F | F | F | T  | T  | T     | T       | F                   |

35.) Construct a truth table for each of these compound propositions.
f.) (¬p ↔ ¬q) ↔ (p ↔ q)

| p | q | ¬p | ¬q | ¬p ↔ ¬q | p ↔ q | (¬p ↔ ¬q) ↔ (p ↔ q) |
|---|---|----|----|---------|-------|---------------------|
| T | T | F  | F  | T       | T     | T                   |
| T | F | F  | T  | F       | F     | T                   |
| F | T | T  | F  | F       | F     | T                   |
| F | F | T  | T  | T       | T     | T                   |

#Week 3 
##(June 21,2016)
On this day, we started discussing about the Chapter 1.3 of the book. As an introduction, Sir asked us if we know about some laws that pertains to logical equivalences. The first questions was asked to me. The questions was if i know how to define the associative property. I was able to answer the question by showing the equivalence, "(p ∧ q) ∧ r = p   ∧ (q  ∧  r)."

We started the discussion by explaining about Tautology, Contradiction and Contingency. I was able to describe each of them when Sir asked about them. Tautology is a compound proposition which is always true. Contradiction is a compound proposition which is always false. Contingency is a compound proposition which is neither a tautology nor a contradiction. In addition to this, the logical operators which are considered as natural partners for tautology and contradiction are given. OR is a natural partner of tautology and AND is a natural partner of contradiction.

To continue the discussion about the laws involved in logical equivalences, we were asked about the logical equivalent of a conditional statement, p → q, using logical operators AND, OR or NOT. Together with Lea, we were able to answer its logical equivalent which is ¬p  ∨ q.   

After the question, we formally discussed about the laws involved with logical equivalences between propositions. The laws and their logical equivalences are as follows:

| Law                 | Equivalence                                                     |
|---------------------|-----------------------------------------------------------------|
| Identity Law        | p ∧ T = p; p ∨ F = p                                             |
| Domination Law      | p ∨ T = T ;p ∧ F = F                                             |
| Idempotent Law      | p ∨ p = p ;p ∧ p = p                                             |
| Double Negation Law | ¬(¬p) = p                                                       |
| Commutative Law     | p ∨ q = q ∨ p ;p ∧ q = q ∧ p                                     |
| Associative Law     | (p ∨ q) ∨ r = p ∨ (q ∨ r); (p ∧ q) ∧ r = p ∧ (q ∧ r)             |
| Distribute Law      | p ∨ (q ∧ r) = (p ∨ q) ∧ (p ∨ r); p ∧ (q ∨ r) = (p ∧ q) ∨ (p ∧ r) |
| De Morgan's Law     | ¬(p ∧ q) = ¬p ∨ ¬q;  ¬(p ∨ q) = ¬p ∧ ¬q                          |
| Absorption Law      | p ∨ (p ∧ q) = p; p ∧ (p ∨ q) = p                                 |
| Negation Law        | p ∨ ¬p = T; p ∧ ¬p = F                                           |

To test if we learned from the class today, each of us answered some questions from the Chapter 1.3 Questions found on the book. The questions that I was able to asnwer are:

7.) Use De Morgan's laws to find the negation of each of the following statements.
d.) Ibrahim is smart and hard working.
Answer: Ibrahim is not smart or not hard working.

15.) Determine whether (¬q ∧ (p  → q))  → ¬p is a tautology.
Answer: True

| p | q | ¬p | ¬q | p → q | ¬q ∧ (p → q) | (¬q ∧ (p → q)) → ¬p |
|---|---|----|----|-------|--------------|---------------------|
| T | T | F  | F  | T     | F            | T                   |
| T | F | F  | T  | F     | F            | T                   |
| F | T | T  | F  | T     | F            | T                   |
| F | F | T  | T  | T     | T            | T                   |

The final topic we discussed for the day was about quantifiers. Quantifiers is an important element for propositions since it gives the range of elements in which a proposition is applicable. There are two types of quantifiers which are universal quantifiers and existential quantifiers.

The universal quantifier is defined as, "P(x) for all values of x in the domain." It is represented by an inverted A, ∀. The ∀xP(x) is a universal quantifier that denotes the universal quantification of P(x). It is read as "for all xP(x)" or "for every xP(x)." To prove that a universal quantifier is false for a certain P(x), a counterexample is needed. 

The existential quantifier is defined as, "There exists an element x in the domain such that P(x)." It is represented by an inverted E, ∃. The ∃xP(x) denotes the existential quantification of P(x).

To end the class, some of us were asked questions about quantifiers. I was asked the question, what is the equivalent of ¬(∀xP(x)). Answer: ∃x¬P(x). The answer means that a universal quantification of a P(x) is false if there exists a false element.

##(June 23, 2016)
We started the meeting by reviewing about the last topic discussed during the previous meeting which were about universal and existential quantifiers. After the review, we proceeded to answering the Chapter 1.4 questions. The questions that I was able to answer are:

5.) Let P(x) be the statement "x spends more than five hours every weekday in class," where the domain for x consists of all students. Expresseach of these quantifications in English.
b.) ∀xP(x)
Answer: All students spend more than five hourse every weekday in class.

7.) Translate these statements into English, where C(x) is "x is a comedian" and F(x) is "x is funny" and the domain consists of all people.

a.) and b.) Explanation between the difference of ∀x((C(x) →  F(x))  and ∀x((C(x) ∧ F(x)) .
Answer: Both of the statements can be translated into one statement, "All comedians are funny," and they are both still correct. The difference between them is that the statement in a.)  ∀x((C(x) →  F(x))  can be interpreted on two more ways. Since a conditional statement is true when p is T when q is T and when q is F, the statement can also be true if C(x) is F and F(x) is true or false. On the other hand, since the statement in b.) ∀x((C(x) ∧ F(x)) is using a logical operator AND, the statement can only be true if p is T and q is T.

d.) ∃x(C(x) ∧ F(x)) 
Answer: Some comedians are funny.

11.) Let P(x) be the statement "x = x^2." If the domain consists of integers, what are these truth values?
c.) P(2)
Answer: False

13.) Determine the truth value of each of these statements if the domain consists of all integers.
d.) ∀n(3n <= 4n)
Answer: False

17.) Suppose that the domain of the propositional function P(x) consists of integers 0, 1, 2, 3, and 4. Write out each of these propositions using disjunctions, conjunctions, and negations.
c.) ∃x¬P(x)
Answer: Negation and Disjunction

After we answered the questions on Chapter 1.4, we were given a reading assignment about Chapter 1.5 Nested Quantifiers.

To further test our knowledge about what we have learned so far, we were asked some questions from Chapter 1.5. The questions that was asked to me was:

1.) Translate these statements into English, where the domain for each variable consists of all real numbers.
c.) ∀x∀y∃z(xy = z)
Answer: For all x and for all y, there exists a z such that xy is equal to z.

As a proof that we did our reading assignment, we were given another assignment which is to answer question numbers 5 to 9 in Chapter 1.5.

The last topic we discussed during this meeting was about rules of inference. Rules of inference is a basic tool in order to establish the truth value of a statement. It is used to deduce new statements from other statements to create a new valud argument. Note that in mathematics, proofs are defined as valid arguments that establishes the truth value of mathematical statements. It is an argument since it is a sequence of statements that ends up with a conclusion. It is valid since the conclusion must follow the truth of the preceding statement which is the argument or premise.

The rules of inference that discussed about are:

| Name                   | Tautology                      |
|------------------------|--------------------------------|
| Modus ponens           | (p ∧ (p → q)) → q              |
| Modus tollens          | (¬q ∧ (p → q)) → ¬p            |
| Hypothetical syllogism | ((p → q) ∧ (q → r)) → (p → r)  |
| Disjunctive syllogism  | ((p ∨ q) ∨ ¬p) → q             |
| Addition               | p → (p ∨ q)                    |
| Simplification         | (p ∧ q) → p                    |
| Conjunction            | ((p) ∧ (q)) → (p ∧ q)          |
| Resolution             | ((p ∨ q) ∧ (¬p ∨ r)) → (q ∨ r) |

We ended the class with each of us giving a statement which is equivalent to a specific rule of inference. In my case, I was asked to make an example of simplication in English. The example I gave was, "If Lea is intelligent and kind, then Lea is intelligent." which is equivalent to (p ∧ q) → p.

##Assignment No. 2:
###Chapter 1.5

5.) Let W(x,y) mean that student x has visited website y, where the domain for x consists of all students in your school and the domain for y consists of all websites. Express each of these statements by a simple English sentence.
d.) ∃y(W(Ashok Puri, y) ∧ W(Cindy Yoon, y))
Answer: There exists a website which Ashok Puri and Ciny Yoon has visited.

7.) Let T(x,y) mean that student x likes cuisine y, where the domain for x consists of all students at your school and the domain for y consists of all cuisines. Express each of these statements by a simple English sentence.
e.) ∃x∃z∀y(T(x,y)  ↔  T(z,y))
Answer: There exists two students at your school who likes the same group of cuisines.

9.) Let L(x,y) be the statement "x loves y", where the domain for both x any consists of all people in the world. Use quantifiers to express each of these statements.
f.) There is somebody whom no one loves.
Answer: ∃x∀y¬L(y,x)

###Chapter 1.6
35.) Determine whether this argument, taken from Kalish and Montague [KaMo64], is valid.
      If Superman were able and willing to prevent evil,he would do so. If Superman were unable to prevent evil, he would be impotent; if he were unwilling to prevent evil, he would be malevolent. Superman does not prevent evil. If Superman exists, he is nether impotent nor malevolent. Therefore, Superman does not exist.
      
      Answer:
      Let: x be the domain Superman.
	      A(x) - x is able to prevent evil
	      W(x) - x is willing to prevent evil
	      P(x) - x prevents evil
	      I(x) - x is impotent
	      M(x) - x is malevolent
	      E(x) - x exists
      So, the statements can be written as:
      A. (A(x) ∧ W(x)) → P(x)
      B. ¬A(x) → I(x)
      C. ¬W(x) → M(x)
      D. ¬P(x)
      E. E(x) → (¬M(S) ∧ ¬I(S))
      Solution:
      Using Modus tollens on A and D,
      ¬P
      (A ∧ W) → P
      = ¬(A ∧ W)
      Using De Morgan's law on ¬(A ∧ W),
      = ¬(A ∧ W) 
      = ¬A ∨ ¬W 
      Using Commutative law on ¬A ∨ ¬W,
      = ¬W ∨ ¬A -- F.
      Converting B to its logical equivalent,
      ¬A → I
      =  A ∨ I -- G.
      Converting C to its logical equivalent,
      ¬W → M
      = W ∨ M -- H.
      Using Resolution on F and H,
      W ∨ M
      ¬W ∨ ¬A
      = M ∨ ¬A 
      Using Commutative law on M ∨ ¬A,
      ¬A ∨ M -- I.
      Using Resolution on G and I,
      A ∨ I
      ¬A ∨ M
      = I ∨ M
      Using De Morgan's law on  I ∨ M,
      I ∨ M 
      = ¬(I ∨ M) 
      = ¬I ∧ ¬M
      Using Modus tollens on  ¬I ∧ ¬M,
      ¬(¬I ∧ ¬M)
      E → (¬I ∧ ¬M)
      = ¬E
      Finals Answer:
      Argument is VALID.
