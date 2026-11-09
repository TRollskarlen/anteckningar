---
course: R7026R
lecture: "1"
topic: Introduction and review of classical control
date: 2026-11-09
slides: 1-61
status: draft
tags:
  - lecture
  - R7026R
---

**Question:** 
**Builds on:** [[Lecture ]] · **Leads to:** [[Lecture ]]

## Summary
<!-- AFTER: answer the Question in my own words, max 3 sentences -->


## Key concepts
<!-- One line each: what it is + why it matters -->
- **Laplace Transformation**: Turns nasty differential equations into simpler algebra.
- 

## Notes
<!-- DURING: only what is NOT on the slides. Refer to slides as (s. 12) -->
The goal of "reglerteknik" is to be able to predict and correct system behaviour without manual intervention. To do this we need to be able to describe the actions of the system mathematically. This always comes in the form of differential equations. 

While they are complicated as they are, having to deal with multiple at the same time doesn't make things easier. To counter this issue we use the Laplace transformation.  

Problem: Physics gives us differential solution. 
$$
\ddot{y} + 2\dot{y} +3y = 6u
$$
Solution: Laplace transformation. Derivatives in the time domain becomes multiplication is the Laplace domain (s-domain).
$$
\dot{y} \rightarrow sY(s),\quad \ddot{y} \rightarrow s^2Y(s)
$$
Ex: Lecture 1 (s.29)
$$ 
\ddot y + a_1\dot y + a_2 y = b_0\ddot u + b_1\dot u + b_2 u
$$
Using Laplace on every term gives us: 

$$
s^2Y + a_{1}sY + a_{2}Y = b_{0}s^2U + b_{1}sU + b_{2}U
$$
Factor out Y and U from their respective side and the divide Y with U and it will give you what is called the transfer function. 
$$
G(s) = \frac{Y(s)}{U(s)} = \frac{b_{0}s^2 + b_{1}s + b_{2}}{s^2 + a_{1}s + a_{2}}
$$
The transfer function is the "instructions" to how the input becomes the output. Best of all is when you connect several blocks in series, instead of having to solve new differential equations, you now only need to multiply the transfer functions in the Laplace plane making it so much fucking easier. The course assumes the systems are LTI (Linear Time-Invariant). Linear = double the input = double the output. Time invariant = the system will behave the same today as tomorrow. Knowing the transfer function allows you to calculate the input or output of a system, given that you now the other. 

Now, while I know the transfer function, how will that help me tell how the system will behave? 

The answer to that is the poles and zero inside $G(s)$. 



## Formulas
<!-- Only what I must know. Say what each symbol means -->
$$
isko
$$
where 

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
[[R7026R Overview]]