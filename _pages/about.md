---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---


<font size="2"> I'm a Senior Research Associate (<a style="color:#d16969" href="https://www.ukri.org/what-we-do/developing-people-and-skills/epsrc/studentships/flexibility-for-funders/epsrc-doctoral-prize/">EPSRC Doctoral Prize Fellow</a>) who researches programming language theory and implementation. I'm affiliated with the <b><a style="color:#d16969" href="https://bristolpl.github.io/">Programming Languages Research Group</a></b> at the University of Bristol, School of Computer Science. Before this, I also did my PhD and MEng in Computer Science at Bristol. Some of my key interests include functional programming, types, and embedded domain-specific languages.

</font>
<br>

**Research**
<font size="2"> I'm currently looking at: <br>

<details>
        <summary>live bidirectional program modification</summary>
        <span style="color:#696969" > generating updated source code that produces a desired change to the original program's output</span>
        </details>
<details>
        <summary>bidirectional methods for composing web applications</summary>
        <span style="color:#696969"> implementing a modular framework that composes both their back-end ``models'' and front-end ``views'' in synchronisation</span>
        </details>
<details>
        <summary>program slicing techniques for data provenance </summary>
        <span style="color:#696969" > calculating the fragments of programs needed to compute specific fragments of their outputs</span>
        </details>
<details>
        <summary>Monte Carlo algorithms for property-based testing </summary>
        <span style="color:#696969" > exploiting MC notions of ``similarity'' for randomly generating program inputs that satisfy a desired property </span>
        </details>

 <!-- and techniques for embedding languages that have "non-standard" semantics (e.g. languages with linear types or that use incremental computation) -->
<br>
During my PhD, I investigated how algebraic effects and effect handlers can be used to improve the design of probabilistic programming languages. I used these techniques to implement a type-safe, modular framework for programmable inference [<b><a style="color:#d16969" href="https://min-nguyen.github.io/files/papers/haskell23.pdf">λ</a></b>], and an embedding of probabilistic models as first-class citizens [<b><a style="color:#d16969"  href="https://dl.acm.org/doi/pdf/10.1145/3547635">λ</a></b>]. <br><br>
<!-- This is implemented as an eDSL called <a href="https://github.com/min-nguyen/wasabaye">Wasabaye</a> in Haskell. <br> <br> -->

Other projects I've led include the application of recursion schemes for implementing and training neural networks [<b><a style="color:#d16969"  href="https://link.springer.com/chapter/10.1007/978-3-031-16912-0_5">λ</a></b>]; in particular, I show how neural networks can be represented as fixed-points of recursive data structures, and forward and back propagation as folds and unfolds over these structures.
<!-- This is implemented as an eDSL called <a href="https://github.com/min-nguyen/catana">Catana</a> in Haskell. -->
</font> <br>


**Papers, etc.**

 <font size="2px"><b><span style="color:#3C6BE4">Effects and Effect Handlers for
Probabilistic Programming</span></b> (<a style="color:#d16969" href="https://min-nguyen.github.io/files/papers/doctoral_thesis.pdf">pdf</a>) </font><br>
 <span style="color:#85868B">  <font size="2">M.Nguyen</font> </span><br>
 <sup>  Doctoral Thesis, 2023</sup><br>
 <font size="2px"><b><span style="color:#3C6BE4"> Effect Handlers for Programmable Inference </span></b> (<a style="color:#d16969" href="https://arxiv.org/abs/2303.01328">preprint</a>, <a style="color:#d16969" href="https://min-nguyen.github.io/files/papers/haskell23.pdf">proceedings</a>) </font><br>
 <span style="color:#85868B">  <font size="2">M.Nguyen, R.Perera, M.Wang, S.Ramsay</font> </span><br>
 <sup>  Haskell Symposium, 2023</sup><br>
 <font size="2px"><b><span style="color:#3C6BE4"> Towards
Type-driven Data Science in Idris </span></b>  (<a style="color:#d16969" href="https://min-nguyen.github.io/files/papers/lafi23-abstract.pdf">abstract</a>, <a style="color:#d16969" href="https://github.com/idris-bayes">repository</a>) </font><br>
 <span style="color:#85868B">  <font size="2">O.Kammar, K.Marek, M.Nguyen, M.Steuwer, J.Walters, R.Wright </font> </span><br>
 <sup>  Languages for Inference Workshop, 2023</sup><br>
 <font size="2px"><b><span style="color:#3C6BE4">Folding over Neural Networks</span></b> (<a style="color:#d16969"  href="https://arxiv.org/pdf/2207.01090.pdf">preprint</a>, <a style="color:#d16969" href="https://link.springer.com/chapter/10.1007/978-3-031-16912-0_5">proceedings</a>) </font><br>
 <span style="color:#85868B">  <font size="2">M.Nguyen, N.Wu </font> </span><br>
 <sup>  Mathematics of Program Construction, 2022</sup><br>
 <font size="2px"><b><span style="color:#3C6BE4">Modular Probabilistic Models via Algebraic Effects</span></b> (<a style="color:#d16969" href="https://arxiv.org/pdf/2203.04608.pdf">preprint</a>, <a style="color:#d16969"  href="https://dl.acm.org/doi/pdf/10.1145/3547635">proceedings</a>, <a style="color:#d16969" href="https://github.com/min-nguyen/prob-fx">repository</a>) </font><br>
 <span style="color:#85868B">  <font size="2">M.Nguyen, R.Perera, M.Weng, N.Wu </font> </span><br>
 <sup>  International Conference on Functional Programming, 2022</sup><br>
 <font size="2px"><b><span style="color:#3C6BE4">Linked visualisations via Galois dependencies</span></b> (<a style="color:#d16969" href="https://arxiv.org/pdf/2109.00445.pdf">preprint</a>, <a style="color:#d16969" href="https://dl.acm.org/doi/pdf/10.1145/3498668">proceedings</a>, <a style="color:#d16969" href="https://github.com/explorable-viz/fluid">repository</a>) </font><br>
 <span style="color:#85868B">  <font size="2">R.Perera, M.Nguyen, T.Petricek, M.Weng </font> </span><br>
 <sup>  Principles Of Programming Languages, 2022</sup><br>
 <font size="2"><b><span style="color:#3C6BE4">Composable, Modular Probabilistic Models</span></b> (<a style="color:#d16969" href="https://min-nguyen.github.io/files/papers/icfp21-abstract.pdf">extended abstract</a>, <a style="color:#d16969" href="https://min-nguyen.github.io/files/papers/icfp21-poster.pdf">poster</a>) </font><br>
 <span style="color:#85868B">  <font size="2">M.Nguyen, R.Perera, M.Weng </font> </span><br>
 <sup>  International Conference on Functional Programming (SRC), 2021</sup><br>
 <font size="2"><b><span style="color:#3C6BE4">Composable, Modular Probabilistic Models</span></b> (<a style="color:#d16969" href="https://ifl21.cs.ru.nl/Program?action=download&upname=IFL21_Nguyen.pdf">paper</a>) </font><br>
 <span style="color:#85868B">  <font size="2">M.Nguyen, R.Perera, M.Weng </font> </span><br>
 <sup>  Implementation and Application of Functional Languages, 2021</sup><br>
<!--  <font size="2"><b><span style="color:#3C6BE4">Modelling Neural Networks with Recursion Schemes</span></b> (<a style="color:#d16969" href="https://min-nguyen.github.io/files/papers/modelling-nns-with-recursion-schemes.pdf">dissertation</a>, <a style="color:#d16969" href="https://min-nguyen.github.io/files/papers/masters-thesis-poster.pdf">poster</a>, <a style="color:#d16969"  href="https://github.com/min-nguyen/catana">repository</a>) </font><br>
 <span style="color:#85868B">  <font size="2">M.Nguyen, N.Wu </font> </span><br>
 <sup>  Masters Dissertation @ University of Bristol, 2019</sup> -->

**Talks**

 <font size="2"><b><span  style="color:#3C6BE4">Effects and Effect Handlers for Probabilistic Programming</span></b>  <br></font>
 <sup>   PhD Defence, Sep 2023</sup><br>
 <font size="2"><b><span  style="color:#3C6BE4">Effect Handlers for Programmable Inference</span></b>   <br></font>
 <sup>  Haskell Symposium, Sep 2023  (<a style="color:#d16969" href="https://youtu.be/c6QAjzunnf8?t=11026">video</a>)</sup><br> <!-- don't insert new line here. bloody html. -->
 <sup>  Tech Talk @ The Alan Turing Institute, May 2023 </sup><br>
 <font size="2"><b><span  style="color:#3C6BE4">Modular Probabilistic Models via Algebraic Effects</span></b>   <br></font>
 <sup>    International Conference on Functional Programming, Sep 2022  (<a style="color:#d16969" href="https://www.youtube.com/watch?v=xLgqx4DK49k">video</a>, <a style="color:#d16969" href="https://min-nguyen.github.io/files/talks/ICFP-22.pdf">slides</a>)</sup><br>
 <sup>  Programming Languages Seminar @ University of Edinburgh, May 2022 (<a style="color:#d16969" href="https://min-nguyen.github.io/files/talks/PLInG-22.pdf">slides</a>)</sup><br>
 <sup>  Tech Talk @ The Alan Turing Institute, Jan 2023</sup><br>
 <font size="2"><b><span  style="color:#3C6BE4">Folding over Neural Networks</span></b>   <br></font>
 <sup>  Mathematics of Program Construction, Sep 2022 </sup><br>
 <font size="2"><b><span  style="color:#3C6BE4">Composable, Modular Probabilistic Models</span></b>   <br></font>
 <sup>  International Conference on Functional Programming (SRC), Sep 2021 (<a style="color:#d16969" href="https://www.youtube.com/watch?v=_ODExz59p6E">video</a>, <a style="color:#d16969" href="https://min-nguyen.github.io/files/slides/ICFP-21.pdf">slides</a>)</sup><br>
 <sup>  Implementation and Application of Functional Languages,  Sep 2021 (<a style="color:#d16969" href="https://youtu.be/hLxTULZXsUQ">video</a>, <a style="color:#d16969" href="https://min-nguyen.github.io/files/talks/IFL-21.pdf">slides</a>)</sup><br>

**Work + Studies**

<font size="2"><span style="color:#AA9E9D"><b>Sep 2023 - Current</b></span> <br>
<b>EPSRC Doctoral Prize Fellow in Programming Languages</b> <br>   <em> hosted by </em> <a style="color:#d16969" href="https://cristina-david.github.io/">Cristina David</a> @ University of Bristol <br></font>
<font size="2"><span style="color:#AA9E9D"><b>Jun 2022 - Sep 2022</b></span> <br>
<b>Research Intern: Dependently typed probabilistic programming for Idris2</b> (<a style="color:#d16969" href="https://github.com/idris-bayes">repositories</a>) <br>   <em> supervised by </em> <a style="color:#d16969" href="http://denotational.co.uk/">Ohad Kammar</a> @ University of Edinburgh <br></font>
<font size="2"><span style="color:#AA9E9D"><b>Jan 2020 - Sep 2023</b></span> <br>
<b>PhD in Programming Languages</b> <br>   <em> supervised by </em> <a style="color:#d16969" href="https://mengwangoxf.github.io/">Meng Wang</a> and <a style="color:#d16969" href="https://www.turing.ac.uk/people/researchers/roly-perera">Roly Perera</a> @ University of Bristol <br></font>
<font size="2"><span style="color:#AA9E9D"><b>Sep 2016 - Oct 2020</b></span> <br>
<b>MEng in Computer Science</b> (first class) <br>   <em> supervised by </em> <a style="color:#d16969" href="https://zenzike.com/">Nicolas Wu</a> @ University of Bristol <br></font> <br>

**Teaching**
<font size="2">
<span style="color:#AA9E9D"><b>2023</b></span> <br>
<b>Supervisor</b> for a 2nd year CS student in their research internship, on <i>"Typed Functional Programming Techniques for Probabilistic Programming"</i> @ University of Bristol. <br>
<span style="color:#AA9E9D"><b>2020 - 2021</b></span> <br>
<b>Supervisor</b> for a 4th year CS student in their masters dissertation, on <i>"Deep Learning Architectures As Pure Functions"</i> @ University of Bristol. <br>
<span style="color:#AA9E9D"><b>2019 - Current</b></span> <br>
<b>Seminars and guest lectures</b> to the <a style="color:#d16969" href="https://bristolpl.github.io/">Programming Languages Research Group</a> and CS undergraduates @ University of Bristol. <br>
<span style="color:#AA9E9D"><b>2017 - Current</b></span> <br>
<b>Teaching assistant</b> for the CS units <a style="color:#d16969" href="https://plrg-bristol.github.io/ATiPL/">Advanced Topics in Programming Languages</a> (4th year), <a style="color:#d16969" href="https://www.bris.ac.uk/unit-programme-catalogue/UnitDetails.jsa;jsessionid=4895129B4D3B9CE9252E3430588DFD92?ayrCode=17%2F18&unitCode=COMS22201">Language Engineering</a> (2nd year), and <a style="color:#d16969" href="https://www.bris.ac.uk/unit-programme-catalogue/UnitDetails.jsa?ayrCode=23%2F24&unitCode=COMS10016">Functional Programming</a> (1st year)  @ University of Bristol.
</font> <br>


<!-- **Other talks**

 <font size="2"><span style="color:#AA9E9D">Oct, 2021</span>     <span  style="color:#3C6BE4">Effects for Less - Alexis King</span> (<a href="https://min-nguyen.github.io/files/slides/effects-for-less">slides</a>, <a href="https://www.youtube.com/watch?v=0jI-AlWEwYI&t=1012s">original talk</a>) <br></font>
 <sup>                      Guest Lecture: Advanced Topics in PL @ University of Bristol</sup><br>
 <font size="2"><span style="color:#AA9E9D">Mar, 2021</span>     <span  style="color:#3C6BE4">Extensible Effects: An Alternative to Monad Transformers - Kiselyov, Oleg, et al.</span> (<a href="https://min-nguyen.github.io/files/slides/extensible-effects.pdf">slides</a>, <a href="https://legacy.cs.indiana.edu/~sabry/papers/exteff.pdf">original paper</a>) <br></font>
 <sup>                      PL Seminar @ University of Bristol</sup><br>
 <font size="2"><span style="color:#AA9E9D">Nov, 2020</span>     <span  style="color:#3C6BE4">First Class Type Families - Li-yao Xia</span> (<a href="https://github.com/min-nguyen/first-class-families/blob/main/FirstClassFamilies.hs">demo</a>, <a href="https://hackage.haskell.org/package/first-class-families">original library</a>) <br></font>
 <sup>                      PL Seminar @ University of Bristol</sup><br>
 <font size="2"><span style="color:#AA9E9D">Aug, 2020</span>     <span  style="color:#3C6BE4">A Theory of Changes for Higher-Order Languages - Cai, Yufei, et al.</span> (<a href="https://github.com/min-nguyen/first-class-families/blob/main/incremental-computation.pdf">slides</a>, <a href="https://inc-lc.github.io/resources/pldi14-ilc-author-final.pdf">original paper</a>) <br></font>
<sup>                      PL Seminar @ University of Bristol</sup><br> -->

**Awards**

<font size="2">
<span style="color:#AA9E9D">2023</span> <span><i>ESPRC Doctoral Prize Fellowship Award for the proposal "Robust, Reusable Computational Models via Typed Functional Programming"</i></span><br>
<span style="color:#AA9E9D">2021</span> <span><i>1st Place in the ICFP ACM Student Research Competition</i></span><br>
<span style="color:#AA9E9D">2019</span> <span><i>Best Machine Learning Dissertation, Bloomberg Award, University of Bristol</i></span><br>
<span style="color:#AA9E9D">2018</span> <span><i>Best Third Year Group Project, Graphcore Award, University of Bristol</i></span><br>
<span style="color:#AA9E9D">2017</span> <span><i>Top Ten Achieving CS Students, Netcraft Award, University of Bristol</i></span>
</font><br>


