---
course: R7026R
lecture: "3"
topic: something
date: 2026-11-11
slides:
status: draft
tags:
  - lecture
---

**Question:** 
**Builds on:** [[]] · **Leads to:** [[]]

## Summary
<!-- AFTER: answer the Question in my own words, max 3 sentences -->


## Key concepts
<!-- One line each: what it is + why it matters -->
- **Term:** Controllability
- **Term:** Obersvability
-

## Notes
<!-- DURING: only what is NOT on the slides. Refer to slides as (s. 12) -->

The rank of the controllability matrix shows us if the system is controllable. The uncontrollable subspace is the nullspace in the controllability matrix. 
$$
Cont.M = [B,AB,A^{n-1}B]
$$

Full rank
## Formulas
<!-- Only what I must know. Say what each symbol means -->
$$

$$
Observability means that if we measure y (and know u). Can we recover the state x?.  

$$
\begin{bmatrix}
1 & 1  \\
1 & 1
\end{bmatrix}
$$
If a state moves on a vector slightly skewed away from the line of the null space, the vector which the state moves can be split into its two components. The shadow of the vector on the null space is not observable while the one orthogonal to the null space is completely observable. (s.29, Observability)

An example of what a sensor see on one spacecraft axis (s.31). 
Q4. Which sensor alone gives the full state a star tracker or a gyro?

Answer
$$
A = 
\begin{bmatrix}
0 & 1 \\
0 & 0
\end{bmatrix}
, bold
$$
He checks the controllability matrix of A, which 

What is the non-observable subspace?

$$
obs = \begin{bmatrix}
0 & 1 \\
0 & 0 
\end{bmatrix}
\begin{bmatrix}
x_{1} \\
0
\end{bmatrix}
$$
Measuring the derivative $\dot{y}$ does not give you $y$



(s.31)
Every noise in the system will be amplified.  Might be that weak observability results in noisy estimates while weak controllability costs large inputs.... (s.31)

Duality (Playing with the system)

Dual system = transpose everything and replace...
$$
\begin{bmatrix}
A & B \\
C & 0
\end{bmatrix}^T
= \begin{bmatrix}
A^T & C^T \\
B^T & 0
\end{bmatrix}
$$
The figure on slide 36 (lowest one, is wrong, $B^T$ should switch place with $C^T$)

## Worked example
<!-- AFTER: redo one example from the slides by hand, without looking -->
**Problem:** 

**Solution:** 


## Self-test
<!-- AFTER: 2–3 questions to quiz myself before the exam -->
- Q: 
- Q: 

## Open questions
<!-- DURING: write it down, keep listening. Tick when answered -->
- [ ] 

---
