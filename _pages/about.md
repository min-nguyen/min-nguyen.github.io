---
permalink: /
title: "About me"
layout: single
header:
 image: "lambda.png"
excerpt: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<font size="2"> <b>Senior Research Associate (<a style="color:#d16969" href="https://www.ukri.org/what-we-do/developing-people-and-skills/epsrc/studentships/flexibility-for-funders/epsrc-doctoral-prize/">EPSRC Doctoral Prize Fellow</a>) and Software Engineer</b> at the University of Bristol. I work in the field of <a style="color:#d16969" href="https://bristolpl.github.io/">programming languages</a>, especially strongly typed and functional programming which I did my PhD and MEng in at Bristol; but I'm a general enthusiast of program design and languages, and love to use all kinds of tech. My role is mainly as a development lead who implements new languages and software that enable exciting things; this could be more modular and safe approaches to data science, or new ways of doing program analysis and software testing.

</font>
<br>

**Research**
<font size="2"> Currently, I'm looking at:
<div style="line-height:25%;">
    <br>
</div>
<details>
        <summary>Lazy evaluation for bidirectional live programming</summary>
        <span style="color:#696969" > investigating <i>lazy</i> bidirectional evaluation, for generating updated source code that produces a desired change to its output.</span>
        </details>
<details>
        <summary>Bidirectional transformations for missing data in web-development</summary>
        <span style="color:#696969">  investigating a bidirectional system for synchronising <i>missing and shared data</i>, applying this to a modular framework for web development where back-end "models" may be shared between multiple front-end "views".</span>
        </details>
<details>
        <summary>Graph-based program slicing for data provenance and program analysis </summary>
        <span style="color:#696969" > investigating <i>graph-based</i> slicing techniques, for calculating the fragments of programs needed to compute specific fragments of their outputs.</span>
        </details>
<details>
        <summary>Monte Carlo algorithms for property-based testing </summary>
        <span style="color:#696969" > investigating <i>Monte Carlo notions of "similarity"</i>, for randomly generating program inputs that satisfy a desired property.</span>
        </details>

 <!-- and techniques for embedding languages that have "non-standard" semantics (e.g. languages with linear types or that use incremental computation) -->

<div style="line-height:75%;">
    <br>
</div>
For my PhD, I investigated how algebraic effect handlers can be used to improve the design of probabilistic programming languages. I used these techniques to implement a type-safe, modular framework for programmable inference [<b><a style="color:#d16969" href="https://min-nguyen.github.io/files/papers/haskell23.pdf">λ</a></b>] and for probabilistic models [<b><a style="color:#d16969"  href="https://dl.acm.org/doi/pdf/10.1145/3547635">λ</a></b>].

<!-- This is implemented as an eDSL called <a href="https://github.com/min-nguyen/wasabaye">Wasabaye</a> in Haskell. <br> <br> -->

<div style="line-height:75%;">
    <br>
</div>
Other projects I've led include exploring recursion schemes for implementing, combining, and training neural networks [<b><a style="color:#d16969"  href="https://link.springer.com/chapter/10.1007/978-3-031-16912-0_5">λ</a></b>]. I showed how neural networks can be represented as fixed-points over recursive data structures, and forward and back propagation as folds and unfolds over those structures.
<!-- This is implemented as an eDSL called <a href="https://github.com/min-nguyen/catana">Catana</a> in Haskell. -->
</font> <br>


**Papers, etc.**

 <font size="2px"><b><span style="color:#3C6BE4">
Absence-Aware Lenses: Unavailability and Unspecifiedness</span></b> </font><br>
 <span style="color:#85868B">  <font size="2">K.Matsuda, M.Nguyen, M.Wang</font> </span><br>
 <sup> In submission, 2024</sup><br>
 <font size="2px"><b><span style="color:#3C6BE4">
Lazy Bidirectional Evaluation</span></b> <!-- (<a style="color:#d16969" href="https://arxiv.org/pdf/2403.04403">preprint</a>) --> </font><br>
 <span style="color:#85868B">  <font size="2">X.Zhang, M.Nguyen</font> </span><br>
 <sup> In submission, 2024</sup><br>
 <font size="2px"><b><span style="color:#3C6BE4">
Conjugate Operators for Transparent, Explorable Research Outputs</span></b> (<a style="color:#d16969" href="https://arxiv.org/pdf/2403.04403">preprint</a>) </font><br>
 <span style="color:#85868B">  <font size="2">J.Bond, C.David, M.Nguyen, D.Orchard, R.Perera</font> </span><br>
 <sup> In submission, 2024</sup><br>
 <font size="2px"><b><span style="color:#3C6BE4">Effects and Effect Handlers for
Probabilistic Programming</span></b> (<a style="color:#d16969" href="https://min-nguyen.github.io/files/papers/doctoral_thesis.pdf">pdf</a>) </font><br>
 <span style="color:#85868B">  <font size="2">M.Nguyen</font> </span><br>
 <sup style="line-height:0px"><a style="color:#d16969" href="https://www.cambridge.org/core/journals/journal-of-functional-programming/article/phd-abstracts/C41D7C267EF388A0FE5AA4CA3DED640E">PhD Abstract</a> in Journal of Functional Programming, 2024 </sup><br style="margin-top: 0">
 <sup style="line-height:0px">PhD Thesis, 2023</sup><br>
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

**Some Talks**

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

**Work & Studies**

<font size="2"><span style="color:#AA9E9D"><b>2023 - Present</b></span> <br>
<b>Senior Research Associate (EPSRC Doctoral Prize Fellow) in Programming Languages</b> <br>   <em> hosted by </em> <a style="color:#d16969" href="https://cristina-david.github.io/">Cristina David</a> @ University of Bristol <br></font>
<font size="2"><span style="color:#AA9E9D"><b>Jun - Sep 2022</b></span> <br>
<b>Research Intern: Dependently typed probabilistic programming for Idris2</b> (<a style="color:#d16969" href="https://github.com/idris-bayes">repositories</a>) <br>   <em> supervised by </em> <a style="color:#d16969" href="http://denotational.co.uk/">Ohad Kammar</a> @ University of Edinburgh <br></font>
<font size="2"><span style="color:#AA9E9D"><b>2020 - 2023</b></span> <br>
<b>PhD in Programming Languages</b> <br>   <em> supervised by </em> <a style="color:#d16969" href="https://mengwangoxf.github.io/">Meng Wang</a> and <a style="color:#d16969" href="https://www.turing.ac.uk/people/researchers/roly-perera">Roly Perera</a> @ University of Bristol <br></font>
<font size="2"><span style="color:#AA9E9D"><b>2015 - 2019</b></span> <br>
<b>MEng in Computer Science</b> (first class) <br>   <em> supervised by </em> <a style="color:#d16969" href="https://zenzike.com/">Nicolas Wu</a> @ University of Bristol <br></font> <br>

**Teaching**
<font size="2">
<span style="color:#AA9E9D"><b>2019 - Present</b></span> <br>
<b>Seminars and guest lectures</b> to the <a style="color:#d16969" href="https://bristolpl.github.io/">Programming Languages Research Group</a> and CS undergraduates @ University of Bristol. <br>
<span style="color:#AA9E9D"><b>2017 - Present</b></span> <br>
<b>Teaching</b> in CS: <a style="color:#d16969" href="https://plrg-bristol.github.io/ATiPL/">Advanced Topics in Programming Languages</a> (4th year), <a style="color:#d16969" href="https://www.bris.ac.uk/unit-programme-catalogue/UnitDetails.jsa;jsessionid=4895129B4D3B9CE9252E3430588DFD92?ayrCode=17%2F18&unitCode=COMS22201">Language Engineering</a> (2nd year), and <a style="color:#d16969" href="https://www.bris.ac.uk/unit-programme-catalogue/UnitDetails.jsa?ayrCode=23%2F24&unitCode=COMS10016">Functional Programming</a> (1st year)  @ University of Bristol. <br>
<span style="color:#AA9E9D"><b>2023</b></span> <br>
<b>Supervisor</b> for a 2nd year CS student in their research internship, on <i>"Typed Functional Programming for Automatic Differentiation and Inference"</i> @ University of Bristol. <br>
<span style="color:#AA9E9D"><b>2021</b></span> <br>
<b>Supervisor</b> for a 4th year CS student in their masters dissertation, on <i>"Deep Learning Architectures As Pure Functions"</i> @ University of Bristol. <br>
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

**Funding & Awards**

<font size="2">
<span style="color:#AA9E9D">2023</span> <span><i>ESPRC Doctoral Prize Fellowship Award</i></span><br>
<span style="color:#AA9E9D">2021</span> <span><i>1st Place: ICFP Graduate Research Competition, ACM</i></span><br>
<span style="color:#AA9E9D">2020</span> <span><i>EPSRC Doctoral Training Partnership Studentship Award</i></span><br>
<span style="color:#AA9E9D">2019</span> <span><i>Best Machine Learning Thesis, Bloomberg Award, University of Bristol</i></span><br>
<span style="color:#AA9E9D">2018</span> <span><i>Best Third Year Group Project, Graphcore Award, University of Bristol</i></span><br>
<span style="color:#AA9E9D">2017</span> <span><i>Top Ten Achieving CS Students, Netcraft Award, University of Bristol</i></span>
</font><br>
