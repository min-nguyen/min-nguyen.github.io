---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---


<font size="2"> I'm a PhD student in the <a href="https://bristolpl.github.io/">Programming Languages Research Group</a> at University of Bristol, supervised by <a href="https://mengwangoxf.github.io/">Meng Wang</a> and <a href="https://www.turing.ac.uk/people/researchers/roly-perera">Roly Perera</a>. My current research investigates the implementation and application of algebraic effects and probabilistic programming languages. My other interests include functional programming (in particular, Haskell), type-level programming, embedded domain-specific languages (eDSLs), and recursion schemes. </font>
<br>

**Research**
<font size="2"> I'm currently exploring the abstraction of algebraic effects, extensible data, and row polymorphism in probabilistic programming language design; the intention is to encode probabilistic models as first-class citizens (hence being modular and composable) whilst being simultaneously general-purpose (i.e. suitable for all forms of simulation and inference). I'm also investigating how complex inference algorithms can be modularly implemented using effect handlers as program transformations on models.  <br><br>
<!-- This is implemented as an eDSL called <a href="https://github.com/min-nguyen/wasabaye">Wasabaye</a> in Haskell. <br> <br> -->

My previous work explored a structured (categorical) approach of using recursion schemes to implement neural networks, letting compositionality be promoted in new ways. In particular, I show how neural networks can be represented as fixed-points of recursive data structures, and forward and back propagation as catamorphisms (folds) and anamorphisms (unfolds) over these structures.
<!-- This is implemented as an eDSL called <a href="https://github.com/min-nguyen/catana">Catana</a> in Haskell. -->
</font> <br>


**Papers, etc.**

 <font size="2px"><span style="color:#AA9E9D">Sep, 2022</span>     <span style="color:#3C6BE4">Folding over Neural Networks</span> (<a href="https://arxiv.org/pdf/2207.01090.pdf">paper</a>) </font><br/>
 <span style="color:#85868B">                 <font size="2">M.Nguyen, N.Wu </font> </span><br/>
 <sup>                       MPC '22</sup><br/>
 <font size="2px"><span style="color:#AA9E9D">Sep, 2022</span>     <span style="color:#3C6BE4">Modular Probabilistic Models via Algebraic Effects</span> (<a href="https://arxiv.org/pdf/2203.04608.pdf">paper</a>) </font><br/>
 <span style="color:#85868B">                 <font size="2">M.Nguyen, R.Perera, M.Weng, N.Wu </font> </span><br/>
 <sup>                       ICFP '22</sup><br/>
 <font size="2px"><span style="color:#AA9E9D">Jan, 2022</span>     <span style="color:#3C6BE4">Linked visualisations via Galois dependencies</span> (<a href="https://arxiv.org/pdf/2109.00445.pdf">paper</a>) </font><br/>
 <span style="color:#85868B">                 <font size="2">R.Perera, M.Nguyen, T.Petricek, M.Weng </font> </span><br/>
 <sup>                       POPL '22</sup><br/>
 <font size="2"><span style="color:#AA9E9D">Aug, 2021</span>     <span style="color:#3C6BE4">Composable, Modular Probabilistic Models</span> (<a href="https://min-nguyen.github.io/files/papers/icfp21-abstract.pdf">extended abstract</a>, <a href="https://min-nguyen.github.io/files/papers/icfp21-poster.pdf">poster</a>) </font><br/>
 <span style="color:#85868B">                 <font size="2">M.Nguyen, R.Perera, M.Weng </font> </span><br/>
 <sup>                       ICFP '21 Student Research Competition</sup><br/>
 <font size="2"><span style="color:#AA9E9D">Jun, 2019</span>     <span style="color:#3C6BE4">Modelling Neural Networks with Recursion Schemes</span> (<a href="https://min-nguyen.github.io/files/papers/modelling-nns-with-recursion-schemes.pdf">dissertation</a>, <a href="https://min-nguyen.github.io/files/papers/masters-thesis-poster.pdf">poster</a>) </font><br/>
 <span style="color:#85868B">                 <font size="2">M.Nguyen, N.Wu </font> </span><br/>
 <sup>                       Masters Dissertation @ University of Bristol</sup>

**Talks**

 <font size="2"><span style="color:#AA9E9D">Sep, 2022</span>     <span  style="color:#3C6BE4">Folding over Neural Networks</span> (<a href="https://min-nguyen.github.io/files/slides/MPC-22.pdf">slides</a>) <br/></font>
 <sup>                      MPC '22</sup><br/>
 <font size="2"><span style="color:#AA9E9D">Sep, 2022</span>     <span  style="color:#3C6BE4">Modular Probabilistic Models via Algebraic Effects</span> (<a href="https://min-nguyen.github.io/files/slides/ICFP-22.pdf">slides</a>) <br/></font>
 <sup>                      ICFP '22</sup><br/>
 <font size="2"><span style="color:#AA9E9D">May, 2022</span>     <span  style="color:#3C6BE4">Modular Probabilistic Models via Algebraic Effects</span> (<a href="https://min-nguyen.github.io/files/slides/PLInG-22.pdf">slides</a>) <br/></font>
 <sup>                      PLInG Seminar @ University of Edinburgh</sup><br/>
 <font size="2"><span style="color:#AA9E9D">Sep, 2021</span>     <span  style="color:#3C6BE4">Composable, Modular Probabilistic Models</span> (<a href="https://www.youtube.com/watch?v=_ODExz59p6E">video</a>, <a href="https://min-nguyen.github.io/files/slides/ICFP-21.pdf">slides</a>) <br/></font>
 <sup>                      ICFP '21 Student Research Competition</sup><br/>
 <font size="2"><span style="color:#AA9E9D">Sep, 2021</span>     <span  style="color:#3C6BE4">Composable, Modular Probabilistic Models</span> (<a href="https://youtu.be/hLxTULZXsUQ">video</a>, <a href="https://min-nguyen.github.io/files/slides/IFL-21.pdf">slides</a>) <br/></font>
 <sup>                      IFL '21</sup><br/>


**Work**

<font size="2"><span style="color:#AA9E9D">Jun '22 - Sep '22</span> <br>
Research Intern: <span style="color:#3C6BE4">Dependently typed probabilistic programming for Idris2</span> (<a href="https://github.com/idris-bayes">repositories</a>) <br>   <em> with </em> <a href="http://denotational.co.uk/">Ohad Kammar</a> @ University of Edinburgh <br/></font> <br>

**Teaching**
<font size="2">
<span style="color:#AA9E9D">2019 - 2022</span> <br>
I give seminar talks and guest lectures to the <a href="https://bristolpl.github.io/">Programming Languages Research Group</a> and undergraduates @ University of Bristol. <br>
<span style="color:#AA9E9D">2020 - 2021</span> <br>
Main advisor for a 4th year CS student in their masters dissertation: "Deep Learning Architectures As Pure Functions" @ University of Bristol. <br>
<span style="color:#AA9E9D">2017 - 2020</span> <br>
Teaching assistant for the <a href="https://www.bris.ac.uk/unit-programme-catalogue/UnitDetails.jsa?unitCode=COMS10016">Functional Programming</a>, <a href="https://www.bris.ac.uk/unit-programme-catalogue/UnitDetails.jsa;jsessionid=4895129B4D3B9CE9252E3430588DFD92?ayrCode=17%2F18&unitCode=COMS22201">Language Engineering</a>, and <a href="https://www.bristol.ac.uk/unit-programme-catalogue/UnitDetails.jsa;jsessionid=523DFF5AD0E44080C9EBAD20F58B9DAE?ayrCode=20%2F21&unitCode=COMSM0066">Advanced Topics in Programming Languages</a> units @ University of Bristol.
</font> <br>

**Awards**

<font size="2">
<span style="color:#AA9E9D">2021</span> <span style="color:#AE3C33"><i>ACM Student Research Competition, 1st Place (ICFP '21)</i></span><br>
<span style="color:#AA9E9D">2019</span> <span style="color:#AE3C33"><i>Bloomberg Award - Best Machine Learning Paper, University of Bristol</i></span><br>
<span style="color:#AA9E9D">2018</span> <span style="color:#AE3C33"><i>Graphcore Award - Best Group Project, University of Bristol</i></span><br>
<span style="color:#AA9E9D">2017</span> <span style="color:#AE3C33"><i> Netcraft Award - Top Ten Achieving CS Students, University of Bristol</i></span>
</font><br/>


