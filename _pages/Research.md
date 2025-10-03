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
**Bounding a Class of Parameters in Measurement Error Models under Data Combination**,  *Job Market Paper* <br/>
[<a href="#"  onclick="visib('jmp'); return false;">Abstract</a>] | Draft Coming Soon

<div id="jmp" style="display: none; padding: 5px">
Validation data that includes both the measurements and the true values provides an effective way to address measurement error. However, obtaining this data can be challenging due to issues related to data collection and matching. This paper studies measurement error models when the measurement and the true value are observed in two different datasets that cannot be matched. We consider a class of parameters that are essential for understanding (non-classical) measurement error and derive their bounds by solving linear programming problems. Our framework allows for an extensive set of identifying assumptions, ensuring flexible structures for the measurement error. We demonstrate our approach using two unmatched datasets: one with reported welfare benefits and the other with actual benefits.
<br/></div>


**Assessing Measurement Error in Linear Instrumental Variables Models**<br/>
[<a href="#"  onclick="visib('assess_ME'); return false;">Abstract</a> ] | [[Draft][assess_ME_draft]]

<div id="assess_ME" style="display: none; padding: 5px">
In linear regression analysis, it is common to use instruments to address measurement error in the regressor. However, bias can still arise if the measurement error correlates with either the true variable, other regressors, or the instrument. This paper develops a sensitivity analysis framework for linear instrumental variables (IV) models that accounts for such concerns. We establish bounds for the parameter of interest using a set of sensitivity parameters that restrict the consistent deviations of the measurement from the true variable.  We illustrate our methods in an empirical study that uses twins data to analyze the effect of schooling level on wages.
<br/></div>

[assess_ME_draft]:{{ site.baseurl }}{% link files/Assess_ME_draft.pdf %}

**Testing Beta Pricing Models with Latent Factors**, *with Kunpeng Li, Qi Li, and Guofu Zhou*<br/>
[<a href="#"  onclick="visib('test_beta'); return false;">Abstract</a> ] |[[SSRN]](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5491568)

<div id="test_beta" style="display: none; padding: 5px">
We propose a test for assessing the validity of linear asset pricing models with latent factors. We establish the asymptotic normality of the test statistic under the null as both the cross-sectional (n) and time-series (T) dimensions grow large. To improve power against sparse alternatives, we incorporate a screening statistic. Simulations demonstrate favorable finite-sample performance. Applying our test to a broad set of anomalies, we find that a small number of latent factors cannot explain their returns. We also revisit the influential study of Giglio and Xiu (2021), which develops a novel method for extracting macro-risk premia, and show that a new extraction approach is needed to account for the more complicated pricing errors revealed by our test.
<br/></div>

**Boundary Adjusted, Polynomial Adaptive, Nonparametric Kernel Conditional Density Estimation**, *with Qi Li and Jeffrey S. Racine* <br/>
Draft upon request


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
