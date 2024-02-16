---
layout: default
title: Michalewicz function
grand_parent: Benchmark
parent: Mathematical Functions
has_children: false
has_toc: true
nav_order: 8
---

<!--Don't delete ths script-->
<script src = "https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
<script id = "MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
<!--Don't delete ths script-->

```python
result = michalewicz(x=x, none_variable=None)
```

<p align="justify">
    The Michalewicz function has d! local minima, and it is multimodal. 
    The parameter m defines the steepness of they valleys and ridges; 
    a larger m leads to a more difficult search.
</p>

Equation
{: .label .label-blue}
<img src="imagens/benchmarks/michal2.png" alt="Michalewicz equation">

Input variables
{: .label .label-yellow }

<table style = "width:100%">
    <thead>
      <tr>
        <th>Name</th>
        <th>Description</th>
        <th>Type</th>
      </tr>
    </thead>
    <tr>
        <td><code>x</code></td>
        <td>This is a list or array representing the input vector to the Michalewicz function. It is the point at which the function is evaluated.</td>
        <td>Py list </td>
    </tr>
</table>

Output variables
{: .label .label-yellow }

<table style = "width:100%">
    <thead>
      <tr>
        <th>Name</th>
        <th>Description</th>
        <th>Type</th>
      </tr>
    </thead>
    <tr>
        <td><code>of</code></td>
        <td>It represents the result of evaluating the Michalewicz function at the given input x.</td>
        <td>float</td>
    </tr>
</table>