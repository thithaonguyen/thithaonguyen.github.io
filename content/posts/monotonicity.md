---
title: "Monotonicity"
date: 2022-03-15T20:04:45+10:00
draft: false
katex: true
---

Question: [Test] Show that if a relation is complete, transitive and satisfies the independence axiom, then it satisfies the monotonicity property.

Answer: 
Without loss of generality, assume $$ p \succ q $$. We need to show that for any probability a and b,
$$ ap + (1-a) q \succ bp + (1-b) q $$ iff $ a >b $

Rewrite the left hand side as $$ (a-b)p + bp + (1-a) q$$.
Rewrite the right hand side as $$ (a-b)p + bp + (1-a)q $$.

Then the indepence axiom implies the inequality.