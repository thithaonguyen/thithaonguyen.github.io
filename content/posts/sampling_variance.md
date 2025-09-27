---
title: "Sampling variance vs population variance"
date: 2021-11-15T20:04:45+10:00
draft: false
katex: true
---

Population variance measures the variability of the underlying variable
$$ V(Y_i) = E(Y_i - EY_i)^2. $$

Sampling variance measures the variability of the sample mean in repeated samples
$$ V(\bar{Y}) = E(\bar{Y} - E\bar{Y})^2 = E( \bar{Y} - EY_i)^2 = \dfrac{\sigma_Y^2}{n}.$$

Sampling variance depends on sample size. More data means less dispersion of sample averages in repeated samples (Law of Large Number).

We often work with standard error of the sample mean which summarizes the variability in an estimate due to random sampling
$$ SE(\bar{Y}) = \dfrac{\sigma_Y}{\sqrt{n}} $$

t-statistics and confidence interval have little to say about whether findings are substantively large or small. Lack of statistical significance often reflects lack of statistical precision (high sampling variance).