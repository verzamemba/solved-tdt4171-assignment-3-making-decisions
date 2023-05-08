Download Link: https://assignmentchef.com/product/solved-tdt4171-assignment-3-making-decisions
<br>
<h1>Decision Network</h1>

Consider a student who has the choice to buy or not buy a textbook for this course. We will model this as a decision problem with one Boolean decision node, <em>B</em>, indicating whether the student chooses to buy the book or not. Furthermore, we want two Boolean chance nodes, <em>M</em>, indicating whether the student has mastered the material in the book, and <em>P</em>, indicating whether the student passes the course. You might think that <em>P </em>would be independent of <em>B </em>given <em>M</em>, but since this course has an open-book final, having the book helps beyond improving the student’s mastery. Of course, there is also a utility node, <em>U</em>. A certain student, Geir, has an additive utility function consisting of two parts: <em>U</em><sub>1</sub>(<em>B </em>= <em>false</em>) = 0 for not buying the book and <em>U</em><sub>1</sub>(<em>B </em>= <em>true</em>) = −150 for buying it; and <em>U</em><sub>2</sub>(<em>P </em>= <em>true</em>) = 2100 for passing the course and <em>U</em><sub>2</sub>(<em>P </em>= <em>false</em>) = 0 for not passing. In other words, Geir wants to maximize <em>U </em>= <em>U</em><sub>1</sub>+<em>U</em><sub>2</sub>. Based on Geir’s gut feeling, he proposes the following probabilities:

<ul>

 <li>The probability of passing given that he buys the book and master the material in the book is 0.9.</li>

 <li>The probability of passing given that he buys the book, but does not master the material in the book is 0.4.</li>

 <li>The probability of passing given that he does not buy the book but master the material in the book is 0.7.</li>

 <li>The probability of passing given that he does not buy the book and does not master the material in the book is 0.2.</li>

 <li>The probability of mastering the material given that he buys the book is 0.9.</li>

 <li>The probability of mastering the material given that he does not buy the book is 0.65.</li>

</ul>

<strong>Problems</strong>

<ol>

 <li>Draw the decision network for this problem.</li>

 <li>Compute the expected utility of the two decision alternatives <em>B </em>= <em>true </em>(buying the book) and <em>B </em>= <em>false </em>(not buying it) (show the calculations). What should Geir do?</li>

</ol>

For this task, it is not allowed to use GeNIe and must be done by hand.

<h1>2        Decision Support System</h1>

In this task, you will create a decision support system for a decision problem of your own choice. This decision support system should help you make a decision from your every-day life. Examples of possible decision problems you may want to build a decision support system for are:

<ul>

 <li>Should I go out on Friday or stay home doing this exercise?</li>

 <li>What is the best behavior for a poker game (seen as a sequential decision problem)?</li>

 <li>Selecting your partner</li>

 <li>Choosing a destination for your next summer holidays</li>

 <li>…etc.</li>

</ul>

As you see, the decision problems used as examples here are like the ones we do all the time, but they are still fairly complex. For instance, the answers to the decision problems are not trivial before we start modeling! It is required that the decision problem you decide to model has the same property.

More specifically, the decision problem you consider can be big or small, but should involve: • At least two decisions, with explicit decision alternatives, and a non-trivial solution

<ul>

 <li>Uncertainty that you are able to structure in a model containing at least 14 variables.

  <ul>

   <li>At least half of the variables should be uncertain, and you need to quantify this uncertainty using probabilities</li>

   <li>The uncertain variables should be observed after a decision is made</li>

  </ul></li>

 <li>A way to measure the success of your decision (e.g., a preference structure or a utility function)

  <ul>

   <li>The preference structure must be represented in a way that facilitates the decisions to be made</li>

  </ul></li>

</ul>

To get a grip on how to proceed, it is recommended that you start by reading Section 16.7 in the book, consider to follow the approach outlined there, and see also the lecture slides concerning this topic. Note, however that copying the model and/or use exactly the same domain is not accepted.

<strong>Note!</strong>

It is the modeling of the decision problem that is of importance here. Hence, modeling, and not the algorithms used to make the decisions, is the focal point of this task. This also implies that there will be no need to implement the mathematics of, e.g., the maximum expected utility – principle. Instead, you can use a software package like GeNIe<a href="#_ftn1" name="_ftnref1"><sup>[1]</sup></a> to help you design your model and find what quantification is required for the model to be fully specified. If you choose to use GeNIe, you can (partly) document your work by including screenshots of the GeNIe model. Additionally, you should also report at least some of the probability tables and discuss how you were able to quantify them.

The grading for this task will be based on

<ul>

 <li>Your ability to choose a reasonable modeling representation.</li>

 <li>That you build a good model:

  <ul>

   <li>Document the model structure as well as some of the quantitative statements you have used.</li>

   <li>List and discuss assumptions you make, both in the modeling representation (e.g., BNs) and in your particular model (e.g., conditional independence assumptions you make).</li>

   <li>That you employ and describe a realistic/reasonable scheme for quantification of uncertainties (see, e.g., Exercise 16.1 in the book for a “calibration-technique”).</li>

   <li>That you employ and describe a realistic/reasonable scheme for quantification of utilities.</li>

  </ul></li>

 <li>“Report quality”. The report should be max 8 pages – a typical report will not need to be above 5 pages for this task.</li>

</ul>


