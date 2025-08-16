---
layout: archive
title: ""
permalink: /research/
author_profile: true
---

{% include base_path %}

<h2 style="border-bottom: 0.5px solid #ccc; padding-bottom: 4px;">
Working Papers
</h2>

**Bounding a Class of Parameters in Measurement Error Models under Data Combination**,  *Job Market Paper* <br/>
[<a href="#"  onclick="visib('jmp'); return false;"><em>Abstract</em></a>] 

<div id="jmp" style="display: none; padding: 5px">
Validation data that includes both the measurements and the true values provides an effective way to address measurement error. However, obtaining this data can be challenging due to issues related to data collection and matching. This paper studies measurement error models when the measurement and the true value are observed in two different datasets that cannot be matched. We consider a class of parameters that are essential for understanding (non-classical) measurement error and derive their bounds by solving linear programming problems. Our framework allows for an extensive set of identifying assumptions, ensuring flexible structures for the measurement error. We demonstrate our approach using two unmatched datasets: one with reported welfare benefits and the other with actual benefits.
<br/></div>


**Assessing Measurement Error in Linear Instrumental Variables Models**,  *Submitted* <br/>
[<a href="#"  onclick="visib('assess_ME'); return false;"><em>Abstract</em></a> ] | [<em>[Draft][assess_ME_draft]</em>]

<div id="assess_ME" style="display: none; padding: 5px">
  In linear regression analysis, it is common to use instruments to address measurement error in the regressor. However, bias can still arise if the measurement error correlates with either the true variable, other regressors, or the instrument. This paper develops a sensitivity analysis framework for linear instrumental variables (IV) models that accounts for such concerns. We establish bounds for the parameter of interest using a set of sensitivity parameters that restrict the consistent deviations of the measurement from the true variable.  We illustrate our methods in an empirical study that uses twins data to analyze the effect of schooling level on wages.
<br/></div>

[assess_ME_draft]:{{ site.baseurl }}{% link files/Assess_ME_draft.pdf %}


<h2 style="border-bottom: 0.5px solid #ccc; padding-bottom: 4px;">
Works in Progress
</h2>
**Tighter Gini-Frisch Bounds**


<script>
function visib(id){
  var el = document.getElementById(id);
  if (!el) return;
  el.style.display = (el.style.display === 'none' || el.style.display === '') ? 'block' : 'none';
}
</script>
