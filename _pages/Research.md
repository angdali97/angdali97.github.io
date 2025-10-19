---
layout: archive
title: ""
permalink: /research/
author_profile: true
---

{% include base_path %}

<h1 style="border-bottom: 0.5px solid rgba(0,0,0,0.2); padding-bottom: 4px;">
Working Papers
</h1>
**Bounding a Class of Parameters in Measurement Error Models under Data Combination**,  Job Market Paper (*Draft Coming Soon*)<br/>
[<a href="#"  onclick="visib('jmp'); return false;">Abstract</a>]

<div id="jmp" style="display: none; padding: 5px">
This paper studies measurement error models where the measurement and the true variable are observed in two different datasets that cannot be matched. A common example arises when a noisy measurement is available in survey data, while the true variable is recorded in administrative data. We consider a class of parameters that characterize the structure of measurement error and derive bounds for them by solving linear programming problems. Our framework accommodates a range of identifying assumptions, allowing for flexible correlation between the measurement error and the true variable. We apply our method to examine patterns of underreporting using two datasets on welfare benefits—one containing reported benefits and the other administrative records of actual benefits.
<br/></div>


**Assessing Measurement Error in Linear Instrumental Variables Models**<br/>
[<a href="#"  onclick="visib('assess_ME'); return false;">Abstract</a>] | [[Draft][assess_ME_draft]]

<div id="assess_ME" style="display: none; padding: 5px">
In linear regression analysis, it is common to use instruments to address measurement error in the regressor. However, bias can still arise if the measurement error correlates with either the true variable, other regressors, or the instrument. This paper develops a sensitivity analysis framework for linear instrumental variables (IV) models that accounts for such concerns. We establish bounds for the parameter of interest using a set of sensitivity parameters that restrict the consistent deviations of the measurement from the true variable.  We illustrate our methods in an empirical study that uses twins data to analyze the effect of schooling level on wages.
<br/></div>
[assess_ME_draft]:{{ site.baseurl }}{% link files/Assess_ME_draft.pdf %}

**Testing Beta Pricing Models with Latent Factors**, with Kunpeng Li, Qi Li, and Guofu Zhou<br/>
[<a href="#"  onclick="visib('test_beta'); return false;">Abstract</a>] | [<a href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5491568" target="_blank" rel="noopener noreferrer">SSRN</a>]


<div id="test_beta" style="display: none; padding: 5px">
We propose a test for assessing the validity of linear asset pricing models with latent factors. We establish the asymptotic normality of the test statistic under the null as both the cross-sectional (n) and time-series (T) dimensions grow large. To improve power against sparse alternatives, we incorporate a screening statistic. Simulations demonstrate favorable finite-sample performance. Applying our test to a broad set of anomalies, we find that a small number of latent factors cannot explain their returns. We also revisit the influential study of Giglio and Xiu (2021), which develops a novel method for extracting macro-risk premia, and show that a new extraction approach is needed to account for the more complicated pricing errors revealed by our test.
<br/></div>

**Boundary Adjusted, Polynomial Adaptive, Nonparametric Kernel Conditional Density Estimation**, with Qi Li and Jeffrey S. Racine (*Draft Available Upon Request*)<br/>
[<a href="#"  onclick="visib('bkcd'); return false;">Abstract</a>]

<div id="bkcd" style="display: none; padding: 5px">
We consider local polynomial nonparametric kernel estimation of conditional density functions g(y|x) when bounds [a,b] on the response Y may be known or unknown. When bounds are known, we use kernel functions for the response that exploit their presence, while when bounds are unknown we advocate using the empirical support [min(Y_i), max(Y_i)] in their place. A key feature of our approach is the use of data-driven methods for joint selection of the order of the approximating local polynomial, p, and the bandwidths for the response and predictors, h_y and h_x. This approach is able to automatically adjust to the presence of unknown bounds and automatically adapt the degree of the approximating polynomial and the bandwidths to the underlying data-generating process, thereby freeing the practitioner from having to select any of these key parameters in an otherwise ad hoc manner. Theoretical underpinnings are provided, and simulations along with an illustrative application indicate that this approach is particularly useful when the distribution of Y is bounded but the bounds are not known a priori, while it remains competitive with existing methods in infinite-support settings. An R package that implements these methods is available for interested readers.
<br/></div>


<h1 style="border-bottom: 0.5px solid rgba(0,0,0,0.2); padding-bottom: 4px; margin-top: 40px;">
Works in Progress
</h1>

**Tighter Gini-Frisch Bounds**


<script>
function visib(id){
  var el = document.getElementById(id);
  if (!el) return;
  el.style.display = (el.style.display === 'none' || el.style.display === '') ? 'block' : 'none';
}
</script>

<script src="https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
<script id="MathJax-script" async
  src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js">
</script>