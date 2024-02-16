---
layout: default
title: Ackley function
grand_parent: Benchmark
parent: Mathematical Functions
has_children: false
has_toc: true
nav_order: 4
---

<!--Don't delete ths script-->
<script src = "https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
<script id = "MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
<!--Don't delete ths script-->

```python
of_ackley = ackley(x_ackley, None)
```

<p align="justify">
The Griewank function has many widespread local minima, which are regularly distributed.
</p>

Equation
{: .label .label-blue}

<!--

f(x) = -\alpha \ exp \left( \sqrt[-b ]{\frac{1}{d}\sum*{i}^{d} x*{2}^{i}} \right ) -exp \left ( \frac{1}{d} \sum*{d}^{i=1} \cos (cx*{i}) \right ) + \alpha + exp(1)

-->

<img src="imagens/benchmarks/ackley2.png" alt="Ackley 2 equation">

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
        <td>A list or array containing the values for the dimensions of the input. This represents the point in the input space for which the Ackley function is being evaluated.</td>
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
        <td>The output value of the Ackley function evaluated at the input coordinates x.</td>
        <td>float</td>
    </tr>
</table>

Example 1
{: .label .label-blue }

```python
# Data
x_ackley = [0, 0]

# Call function
of_ackley = ackley(x_ackley, None)

# Output details
print("of_best ackley: of = {:.4f}".format(of_ackley))
```