---
title: "P-Hacking"
date: 2021-11-15T20:04:45+10:00
draft: false
katex: true
---

P-value is the probability of witnessing an event at least as extreme as our result. The smaller the p-value, the more evidence there is to reject \\(H_0\\). Reduce p-value if you want to be extra-sure that you have good evidence to reject \\(H_0\\).

### p-hacking
1. collect a bunch of data
2. test a bunch of different things and look for p-values <0.05
3. claim strong evidence for the things that have p-values <0.05
$$ P(\text{at least one of the $S_i$ has a p-value below significance}|H_0) = 1 - P(\text{none}|H_0) = 1- 0.95^{20} \approx 0.642.$$
    
    Thus it is very likely to make false claims this way.

### Good statistics research
1. form a hypothesis, then
2. collect data, then
3. perform a hypothesis test: if p<0.05, reject \\(H_0\\)