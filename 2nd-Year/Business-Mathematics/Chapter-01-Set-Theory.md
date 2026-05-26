<div align="center">

# Chapter 1 — Set Theory

### Business Mathematics &nbsp;|&nbsp; 2nd Year BBA (Management) &nbsp;|&nbsp; National University

![Subject](https://img.shields.io/badge/Subject-Business%20Mathematics-1f6feb?style=flat-square)
![Code](https://img.shields.io/badge/Code-222609-purple?style=flat-square)
![Marks](https://img.shields.io/badge/Total%20Marks-100-orange?style=flat-square)
![Difficulty](https://img.shields.io/badge/Chapter%201-Easy-brightgreen?style=flat-square)

[Chapter List](./README.md) &nbsp;•&nbsp; [Repo Home](../../README.md)

</div>

---

## What you will learn in this chapter

- What is a Set, how to write a set
- 11 types of sets (finite, infinite, empty, equal, subset, power, universal, etc.)
- Set operations — Union, Intersection, Difference, Complement, Symmetric Difference
- Venn diagrams (visual picture of sets)
- Laws of set algebra (Commutative, Associative, Distributive, De Morgan)
- Cardinal number formulas — n(A∪B), n(A∪B∪C)
- **Survey problems** (most important — comes every year)

---

## Quick Navigation

| # | Section | Use it for |
|---|---------|------------|
| A | [Easy Explanation](#part-a--easy-explanation-story-style) | First time understanding |
| B | [Theory in Exam Style](#part-b--theory-in-exam-answer-style) | 4 broad theory questions |
| C | [Math Problems Solved](#part-c--solved-math-problems-step-by-step) | The 12-mark problems |
| D | [MCQ Bank](#part-d--mcq-bank-20-questions) | Section A |
| E | [Short Questions](#part-e--short-questions-4-marks) | Section B |
| star | [Quick Revision Card](#-quick-revision-card-night-before-exam) | Night before exam |
| books | [Books + YouTube Links](#-resources--books-and-youtube-videos) | Extra study |

---

<div align="center">

## Part A — Easy Explanation (Story Style)

</div>

### What is a Set?

> Imagine your mother's kitchen. There is a basket of **fruits** — apple, banana, mango, orange.
> There is another basket of **vegetables** — potato, onion, tomato.
>
> Each basket is a **SET**.
> Each thing inside (apple, banana...) is called a **member** or **element** of that set.

So in one easy line:

> [!TIP]
> **A SET = a collection of things grouped together.**
> Each thing inside is called an **element** or **member.**

### How do we write a set?

We use **capital letters** (A, B, C...) for the set name, and put the elements inside **curly brackets `{ }`** with commas.

| Example | Meaning |
|---------|---------|
| **A = {apple, banana, mango}** | Set A is the group of these 3 fruits |
| **B = {1, 2, 3, 4, 5}** | Set B is the group of first 5 counting numbers |
| **V = {a, e, i, o, u}** | Set V is the set of English vowels |

### How do we say "x is in the set"?

We use a special symbol **∈** (means *belongs to*) and **∉** (means *does not belong to*).

> If A = {1, 2, 3}, then —
> - **2 ∈ A** (2 belongs to A)
> - **5 ∉ A** (5 does not belong to A)

---

<div align="center">

## Part B — Theory in Exam Answer Style

</div>

> [!IMPORTANT]
> **Exam format:** Each answer = **Introduction → Definition → Body (with examples) → Conclusion.**

---

### Q1. Define Set. Discuss the methods of describing a set with examples. &nbsp; `[Marks: 5–8]`

#### Introduction
The concept of "set" is the foundation of modern mathematics. The German mathematician **Georg Cantor** (1845–1918) developed Set Theory. In Business Mathematics, we use sets to group similar items, customers, products, or ideas.

#### Definition of Set

> **Georg Cantor:**
> "A set is a well-defined collection of distinct objects."

> **In simple words:** A **set** is a group of objects which are clearly defined (we can say if a thing is in or out) and all members are different.

The three keywords:
1. **Well-defined** — we must be able to tell if a thing is inside the set or not.
2. **Distinct** — no element is repeated.
3. **Collection** — group of items.

*Example:* "The set of all students who scored above 80 in BBA exam" — this is well-defined.
*Not a set:* "The set of all good students" — "good" is not well-defined.

#### Methods of describing a set

##### 1. Roster / Tabular Method
We list **all elements** inside `{ }`, separated by commas.

| Set | Roster form |
|-----|-------------|
| First 5 natural numbers | A = {1, 2, 3, 4, 5} |
| Vowels in English | V = {a, e, i, o, u} |
| Even numbers below 10 | E = {2, 4, 6, 8} |

##### 2. Set-Builder / Selector Method
We write a **rule or property** that all elements follow.

Format: `A = { x : property of x }` — read as *"A is the set of all x such that x has the property"*.

| Description | Set-builder form |
|-------------|------------------|
| First 5 natural numbers | A = { x : x is a natural number, x ≤ 5 } |
| Vowels | V = { x : x is a vowel in English } |
| Even numbers below 10 | E = { x : x is even, x < 10 } |

#### Conclusion
The roster method is good for small sets, and the set-builder method is good for large or infinite sets. Both methods describe the same set.

---

### Q2. Discuss different types of sets with examples. &nbsp; `[Marks: 10]`

#### Introduction
Sets are classified into different types based on the number of elements, the relation between sets, and special properties. The main types of sets are discussed below.

#### Types of Sets

| # | Type | Definition | Example |
|---|------|-----------|---------|
| 1 | **Empty / Null Set** | A set with **no element** | A = { } or ∅ |
| 2 | **Singleton Set** | A set with **only one element** | A = {5} |
| 3 | **Finite Set** | A set with **countable** elements | A = {1, 2, 3, 4} |
| 4 | **Infinite Set** | A set with **uncountable / endless** elements | N = {1, 2, 3, ...} |
| 5 | **Equal Sets** | Two sets having **same elements** | A = {1,2,3}, B = {3,2,1} → A = B |
| 6 | **Equivalent Sets** | Two sets with **same number of elements** | A = {1,2,3}, B = {a,b,c} |
| 7 | **Subset (⊆)** | All elements of A are in B | A = {1,2}, B = {1,2,3} → A ⊆ B |
| 8 | **Proper Subset (⊂)** | A is subset of B but A ≠ B | A = {1,2}, B = {1,2,3} → A ⊂ B |
| 9 | **Super Set (⊇)** | B contains all elements of A | B = {1,2,3} ⊇ {1,2} |
| 10 | **Universal Set (U)** | The set of all elements under study | All NU students |
| 11 | **Power Set P(A)** | Set of **all possible subsets** of A | A = {1,2} → P(A) = {∅, {1}, {2}, {1,2}} |
| 12 | **Disjoint Sets** | Two sets with **no common element** | A = {1,2}, B = {3,4} |

#### Important Formula

> **Number of subsets of a set with `n` elements = 2 to the power n**
> *Example:* If A = {a, b, c} (n=3), then total subsets = 2³ = **8**.

#### Conclusion
Knowing the types of sets is the first step to understand set operations and Venn diagrams. These types help us solve real-life business problems like customer grouping and market segmentation.

---

### Q3. Define Set Operations. Explain Union, Intersection, Difference, and Complement with Venn diagrams. &nbsp; `[Marks: 10]`

#### Introduction
Just like we add or subtract numbers, we can also combine or compare sets. These are called **set operations**. The four main operations are Union, Intersection, Difference, and Complement.

Let A = {1, 2, 3, 4} and B = {3, 4, 5, 6} for all examples.

#### 1. Union (A ∪ B) — "OR"
**All elements of A and B together** (common items written only once).

> A ∪ B = {1, 2, 3, 4, 5, 6}

**Venn diagram:** Both circles fully shaded.

```
    A           B
  ┌────┐    ┌────┐
  │ 1  │ 3,4│ 5  │
  │ 2  │    │ 6  │
  └────┘    └────┘
   ▓▓▓ all shaded ▓▓▓
```

#### 2. Intersection (A ∩ B) — "AND"
**Only the common elements** of A and B.

> A ∩ B = {3, 4}

**Venn diagram:** Only the overlapping middle part is shaded.

#### 3. Difference (A − B) — "A minus B"
**Elements in A but NOT in B.**

> A − B = {1, 2}
> B − A = {5, 6}

**Venn diagram:** Only A's part outside the overlap.

#### 4. Complement (A' or A^c) — "everything except A"
**Elements in the universal set but NOT in A.**

> If U = {1,2,3,4,5,6,7} and A = {1,2,3}, then A' = {4, 5, 6, 7}

**Venn diagram:** Everything outside circle A.

#### 5. Symmetric Difference (A △ B) — "Either A or B but not both"
> A △ B = (A − B) ∪ (B − A) = {1, 2, 5, 6}

#### Summary Table

| Operation | Symbol | Meaning | Example (A={1,2,3,4}, B={3,4,5,6}) |
|-----------|--------|---------|-------------------------------------|
| Union | A ∪ B | All elements | {1,2,3,4,5,6} |
| Intersection | A ∩ B | Common elements | {3,4} |
| Difference | A − B | In A, not in B | {1,2} |
| Complement | A' | Outside A | depends on U |
| Symmetric Diff | A △ B | Not in both | {1,2,5,6} |

#### Conclusion
These five operations are the basic tools to work with sets and solve business problems involving grouping, surveys, and classifications.

---

### Q4. State and verify the Laws of Set Algebra. &nbsp; `[Marks: 10]`

#### Introduction
Just like algebra has rules (a+b = b+a), set theory also has rules called **laws of set algebra**. These help us simplify complex set expressions.

#### Important Laws

| # | Name | Law |
|---|------|-----|
| 1 | **Commutative Law** | A ∪ B = B ∪ A &nbsp;;&nbsp; A ∩ B = B ∩ A |
| 2 | **Associative Law** | (A ∪ B) ∪ C = A ∪ (B ∪ C) |
| 3 | **Distributive Law** | A ∪ (B ∩ C) = (A ∪ B) ∩ (A ∪ C) |
| 4 | **Identity Law** | A ∪ ∅ = A &nbsp;;&nbsp; A ∩ U = A |
| 5 | **Complement Law** | A ∪ A' = U &nbsp;;&nbsp; A ∩ A' = ∅ |
| 6 | **Idempotent Law** | A ∪ A = A &nbsp;;&nbsp; A ∩ A = A |
| 7 | **De Morgan's Law** | (A ∪ B)' = A' ∩ B' &nbsp;;&nbsp; (A ∩ B)' = A' ∪ B' |

#### Example: Verify Commutative Law
Let A = {1, 2, 3} and B = {3, 4, 5}.

- A ∪ B = {1, 2, 3, 4, 5}
- B ∪ A = {3, 4, 5, 1, 2} = {1, 2, 3, 4, 5}

Since A ∪ B = B ∪ A, the law is **verified**.

#### Conclusion
These laws help simplify complex set problems quickly, especially De Morgan's Law which is used in probability and logic.

---

<div align="center">

## Part C — Solved Math Problems (Step by Step)

</div>

> [!IMPORTANT]
> **Exam format for math problem:**
> **Given → Required → Formula → Solution (step by step) → Final Answer**

---

### Problem Type 1 — Find n(A ∪ B) using formula

#### Formula

> **n(A ∪ B) = n(A) + n(B) − n(A ∩ B)**
>
> where `n(A)` means "number of elements in A".

#### Solved Example 1
**Question:** In a class, 30 students play cricket, 25 play football, and 10 play both. How many students play either cricket or football?

**Given:**
- n(C) = 30 (cricket)
- n(F) = 25 (football)
- n(C ∩ F) = 10 (both)

**Required:** n(C ∪ F)

**Formula:** n(C ∪ F) = n(C) + n(F) − n(C ∩ F)

**Solution:**
n(C ∪ F) = 30 + 25 − 10
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; = 55 − 10
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; = **45**

**Answer:** 45 students play either cricket or football.

---

### Problem Type 2 — Survey Problem (3 Sets) — Very Important

> [!TIP]
> **This type of problem comes almost every year in NU exam.** Practice it well.

#### Formula (3-set rule)

> **n(A ∪ B ∪ C) = n(A) + n(B) + n(C) − n(A∩B) − n(B∩C) − n(A∩C) + n(A∩B∩C)**

#### Solved Example 2
**Question:** In a survey of 100 customers in a supermarket:
- 60 buy rice
- 50 buy oil
- 40 buy sugar
- 25 buy rice and oil
- 20 buy oil and sugar
- 15 buy rice and sugar
- 10 buy all three

Find: (i) How many buy at least one item? (ii) How many buy none?

**Given:**
- Total = 100
- n(R) = 60, n(O) = 50, n(S) = 40
- n(R∩O) = 25, n(O∩S) = 20, n(R∩S) = 15
- n(R∩O∩S) = 10

**Required:** (i) n(R ∪ O ∪ S) &nbsp; (ii) Customers buying nothing.

**Formula:**
n(R ∪ O ∪ S) = n(R) + n(O) + n(S) − n(R∩O) − n(O∩S) − n(R∩S) + n(R∩O∩S)

**Solution:**
n(R ∪ O ∪ S) = 60 + 50 + 40 − 25 − 20 − 15 + 10
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; = 150 − 60 + 10
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; = **100**

So 100 customers buy at least one item.

(ii) Customers who bought nothing = Total − n(R ∪ O ∪ S) = 100 − 100 = **0**

**Answer:** (i) 100 customers buy at least one item. (ii) 0 customers buy none.

---

### Problem Type 3 — Find Power Set

#### Solved Example 3
**Question:** If A = {a, b, c}, find the power set P(A) and number of subsets.

**Solution:**
Number of subsets = 2³ = **8**

P(A) = { ∅, {a}, {b}, {c}, {a,b}, {a,c}, {b,c}, {a,b,c} }

**Answer:** P(A) has 8 subsets as shown above.

---

### Problem Type 4 — Verify De Morgan's Law

#### Solved Example 4
**Question:** Let U = {1,2,3,4,5,6,7,8}, A = {1,2,3,4}, B = {3,4,5,6}.
Verify (A ∪ B)' = A' ∩ B'.

**Solution:**

**LHS = (A ∪ B)'**
A ∪ B = {1, 2, 3, 4, 5, 6}
(A ∪ B)' = U − (A ∪ B) = {7, 8}

**RHS = A' ∩ B'**
A' = U − A = {5, 6, 7, 8}
B' = U − B = {1, 2, 7, 8}
A' ∩ B' = {7, 8}

**Since LHS = RHS = {7, 8}, De Morgan's Law is verified.**

---

### Problem Type 5 — Find missing value (reverse problem)

#### Solved Example 5
**Question:** In a survey, 70 like tea, 50 like coffee, and 20 like both. If everyone likes at least one drink, find the total number of people.

**Given:** n(T) = 70, n(C) = 50, n(T ∩ C) = 20

**Formula:** n(T ∪ C) = n(T) + n(C) − n(T ∩ C)

**Solution:**
n(T ∪ C) = 70 + 50 − 20 = **100**

Since everyone likes at least one drink, total people = n(T ∪ C) = 100.

**Answer:** 100 people in total.

---

### Practice Problems (try yourself)

> [!NOTE]
> Try these alone first. Then check the answer hidden below each one.

**P1.** In a class of 50, 30 play cricket, 25 play football, 8 play both. How many play neither?
<details><summary>Show answer</summary>n(C∪F) = 30 + 25 − 8 = 47. Neither = 50 − 47 = <b>3</b>.</details>

**P2.** A = {1,2,3,4,5}, B = {2,4,6,8}. Find A∪B, A∩B, A−B, B−A.
<details><summary>Show answer</summary>A∪B = {1,2,3,4,5,6,8}; A∩B = {2,4}; A−B = {1,3,5}; B−A = {6,8}.</details>

**P3.** If a set has 5 elements, how many subsets does it have?
<details><summary>Show answer</summary>2⁵ = <b>32</b> subsets.</details>

**P4.** In a survey of 200 people, 120 read newspaper A, 80 read newspaper B, 50 read both. How many read at least one? How many read none?
<details><summary>Show answer</summary>n(A∪B) = 120 + 80 − 50 = 150. None = 200 − 150 = <b>50</b>.</details>

---

<div align="center">

## Part D — MCQ Bank (20 Questions)

</div>

| # | Question | a) | b) | c) | d) |
|---|----------|----|----|----|----|
| 1 | Set theory was developed by | Newton | **Cantor** | Euler | Fisher |
| 2 | A set is a collection of | similar items | numbers only | **distinct objects** | letters only |
| 3 | The symbol "∈" means | not equal | **belongs to** | empty | universal |
| 4 | A set with no element is | finite | **empty** | singleton | universal |
| 5 | A set with one element is | empty | **singleton** | finite | infinite |
| 6 | If A = {1,2,3}, B = {3,2,1}, then | A ≠ B | A ⊂ B | **A = B** | A ∩ B = ∅ |
| 7 | Number of subsets of a set with 4 elements | 8 | **16** | 32 | 4 |
| 8 | A ∪ B means | common | **all together** | difference | complement |
| 9 | A ∩ B means | all together | **common** | difference | complement |
| 10 | If A = {1,2}, B = {2,3}, then A ∩ B = | {1,2,3} | {1,3} | **{2}** | ∅ |
| 11 | If A = {1,2}, B = {2,3}, then A ∪ B = | {2} | {1,3} | **{1,2,3}** | ∅ |
| 12 | A − B means | common | **A minus B** | A plus B | complement |
| 13 | (A ∪ B)' = | A' ∪ B' | **A' ∩ B'** | A ∩ B | A ∪ B |
| 14 | (A ∩ B)' = | **A' ∪ B'** | A' ∩ B' | A ∪ B | ∅ |
| 15 | n(A ∪ B) = | n(A) + n(B) | **n(A) + n(B) − n(A∩B)** | n(A) − n(B) | n(A) × n(B) |
| 16 | A ∩ A = | ∅ | U | **A** | 2A |
| 17 | A ∪ ∅ = | ∅ | **A** | U | A' |
| 18 | A ∪ A' = | A | A' | ∅ | **U** |
| 19 | If A = {x: x is a vowel in English}, then n(A) = | 4 | **5** | 6 | 26 |
| 20 | A and B are disjoint sets means | A = B | A ⊆ B | **A ∩ B = ∅** | A ∪ B = ∅ |

<details>
<summary><b>Show all answers (click to open)</b></summary>

**1-b, 2-c, 3-b, 4-b, 5-b, 6-c, 7-b, 8-b, 9-b, 10-c, 11-c, 12-b, 13-b, 14-a, 15-b, 16-c, 17-b, 18-d, 19-b, 20-c**

</details>

---

<div align="center">

## Part E — Short Questions (4 marks each)

</div>

> [!NOTE]
> Format: **Definition + 1 example + 1 line note** = full 4 marks.

1. Define a set with example.
2. What is a finite set and an infinite set?
3. What is an empty set and a singleton set?
4. What is the difference between equal and equivalent sets?
5. Define subset and super set.
6. What is a power set? If A = {1,2}, find P(A).
7. What is union and intersection of sets?
8. State De Morgan's laws.
9. Define disjoint sets with example.
10. Write the formula for n(A ∪ B) and n(A ∪ B ∪ C).

---

<div align="center">

## Quick Revision Card (Night Before Exam)

</div>

> [!IMPORTANT]
> Read this one-page summary the night before exam — you can answer 80% of questions.

| Topic | Key Point |
|-------|-----------|
| Inventor | **Georg Cantor** |
| Set notation | Capital letter, elements in `{ }` |
| Element symbol | **∈** (belongs to), **∉** (not belongs) |
| Two methods | Roster (list) and Set-builder (rule) |
| Total subsets | **2 to the power n** for `n` elements |
| Empty set | { } or ∅, has 0 elements |
| Singleton set | only 1 element |
| Equal sets | same elements |
| Equivalent sets | same number of elements |
| Subset (⊆) | all of A is in B |
| Universal set (U) | full set under study |

### Important Formulas

| Operation | Formula |
|-----------|---------|
| **Union (2 sets)** | n(A ∪ B) = n(A) + n(B) − n(A ∩ B) |
| **Union (3 sets)** | n(A∪B∪C) = n(A)+n(B)+n(C) − n(A∩B) − n(B∩C) − n(A∩C) + n(A∩B∩C) |
| **Number of subsets** | 2 to the power n |
| **De Morgan I** | (A ∪ B)' = A' ∩ B' |
| **De Morgan II** | (A ∩ B)' = A' ∪ B' |

### Memory Tricks

> **Trick 1 — Symbol meaning:**
> ∪ looks like a **U**p cup → **U**nion (combines all).
> ∩ looks like an **n** **n**arrow → i**n**tersection (only common).

> **Trick 2 — De Morgan's law (flip):**
> *Move the dash inside, flip the symbol.*
> (A ∪ B)' → A' **∩** B' (∪ becomes ∩)
> (A ∩ B)' → A' **∪** B' (∩ becomes ∪)

> **Trick 3 — 3-set formula sign pattern:**
> **+ + + − − − +** (three plus, three minus, one plus)

---

<div align="center">

## Resources — Books and YouTube Videos

</div>

> All links below are free and open. If a link breaks, copy the title and search on Google.

### Recommended Books (PDF / Free Read)

| Book | Author | Type | Link |
|------|--------|------|------|
| Business Mathematics (most-used in NU) | D. C. Sancheti & V. K. Kapoor | Reference (Indian classic) | [Internet Archive search](https://archive.org/search?query=business+mathematics+sancheti+kapoor) |
| An Introduction to Business Mathematics | F. Reichel & H. K. Wickramasinghe | Free PDF | [ResearchGate](https://www.researchgate.net/publication/338477453_An_Introduction_to_Business_Mathematics) |
| Business Mathematics (Open textbook) | BCIT (Creative Commons) | Free online book | [Pressbooks BC Campus](https://pressbooks.bccampus.ca/businessmathematics/) |
| Business Math: A Step-by-Step Handbook | J. Olivier | Free open textbook | [Open Textbook Library — UMN](https://open.umn.edu/opentextbooks/textbooks/642) |

### YouTube — English (Concept Building)

| Topic | Channel | Link |
|-------|---------|------|
| Sets — Introduction | Khan Academy | [Watch](https://www.khanacademy.org/math/algebra-home/alg-basic-eq-ineq/alg-sets-introduction) |
| Union & Intersection | Khan Academy | [Watch](https://www.khanacademy.org/math/engageny-alg2/alg2-4/alg2-4a-venn-probability-rules/v/intersection-and-union-of-sets) |
| Venn Diagrams | Khan Academy | [Watch](https://www.khanacademy.org/math/7th-grade-matatag/x065dcf1640354e81:2nd-quarter/x065dcf1640354e81:sets/v/visualising-set-operations-using-venn-diagrams) |
| Set Operations Full Lecture | Organic Chemistry Tutor | [YouTube search](https://www.youtube.com/results?search_query=organic+chemistry+tutor+sets+union+intersection) |

### YouTube — Bangla (NU BBA Friendly)

> Click these search links — the top results are usually Bangladeshi tutors explaining for NU/HSC students.

| Search this on YouTube | Why |
|------------------------|-----|
| [Set Theory Business Mathematics Bangla](https://www.youtube.com/results?search_query=set+theory+business+mathematics+bangla) | Set theory in Bangla |
| [Set Theory NU BBA 2nd Year](https://www.youtube.com/results?search_query=set+theory+NU+BBA+2nd+year) | NU-specific tutorials |
| [Venn Diagram Bangla tutorial](https://www.youtube.com/results?search_query=venn+diagram+bangla+tutorial) | Venn diagram visual lessons |
| [Business Mathematics Chapter 1 Bangla](https://www.youtube.com/results?search_query=business+mathematics+chapter+1+bangla) | Chapter-wise Bangla notes |
| [Set Union Intersection Bangla](https://www.youtube.com/results?search_query=set+union+intersection+bangla) | Operations in Bangla |

### Practice & Reference Sites

- [GeeksforGeeks — Set Operations](https://www.geeksforgeeks.org/maths/set-operations/) — clean explanations + practice problems
- [BYJU'S — Venn Diagrams](https://byjus.com/maths/venn-diagrams/) — easy beginner-friendly notes
- [Online Math Learning — Venn & Subsets](https://www.onlinemathlearning.com/venn-diagrams.html) — video lessons + examples

---

<div align="center">

### Chapter 1 complete

[← Back to Chapter List](./README.md) &nbsp;•&nbsp; **Next:** Chapter 2 — Number System & Logarithms →

</div>
