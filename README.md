Download Link: https://assignmentchef.com/product/solved-dynamicalsystems-homework-1
<br>
When necessary, you should use a computer program that can produce pictures and plots (such as Maple, Matlab, etc). Give a short explanation of your results, if necessary with plots, etc. Kindly avoid handwritten answers; use a word-processor.

Bakground: A rst-order autonomous system in discrete time is given by the di erence equation

<em>x<sub>n</sub></em><sub>+1 </sub>= <em>f</em>(<em>x<sub>n</sub></em>)<em>,        n </em>≥ 0

We are interested in the stationary state, i.e., what happens when transients have died out.

Question 1 Iterate the function <em>f</em>(<em>x</em>) = cos<em>x </em>with arbitrary initial conditions. What happens? Follow these steps to prove that the iteration has a xed point, and compute it (perhaps numerically):

<ol>

 <li>Note that after one iteration, the system enters a closed interval <em>I </em>and never leaves this interval in the sequel. Which interval is it?</li>

 <li>Prove that <em>f</em>(<em>x</em>) is a contraction in <em>I</em>. Use, e.g., the mean value theorem of di erential calculus to estimate <em>f</em>(<em>x</em>) − <em>f</em>(<em>y</em>).</li>

 <li>Check that the interval <em>I </em>and the contraction property allow you to use Banach’s theorem and compute the xed point.</li>

</ol>

Question 2 Repeat the previous excercise with <em>f</em>(<em>x</em>) = arctan<em>x</em>. You may start with positive <em>x</em>’s to x ideas. Banach’s xed point theorem does not directly apply, because the bounds to contraction are not strictly smaller than one. There is a way around using standard analysis results: What is the limit of a monotonically decreasing sequence bounded from below?

Question 3 Show that the function  has a xed point. Hint:

√                                                                      √

<ol>

 <li>Show that if√0 <em>&lt; b </em>≤ <em>a </em>then <em>f</em>(<em>b</em>) ≥ <em>b</em>. Show also that if <em>x &gt; a </em>then <em>f</em>(<em>x</em>) <em>&gt; a</em>. This shows that there is an interval [<em>b,</em>∞) where all iterates lie after the rst iteration. Now you need to nd a good <em>b</em>.</li>

 <li>Use again the mean value theorem of di erential calculus or any othermethod you choose to estimate <em>f</em>(<em>x</em>) − <em>f</em>(<em>y</em>) inside the interval, and choose now <em>b </em>so that the map is a contraction.</li>

 <li>Check that now you can use Banach’s theorem and compute the xed point.</li>

</ol>

Question 4 Choose an arbitrary initial condition <em>x</em><sub>0 </sub>between 0 and 1 and iterate <em>f</em>(<em>x</em>) = <em>µx</em>(1 − <em>x</em>) (i.e., compute <em>x<sub>n</sub></em>) at least 200 times. Look at the values you get for iterates 201, 202 and so on and try to decide if the iterates approach some stationary value(s). Repeat this for the parameter values <em>µ </em>= 2, 2<em>.</em>9, 3<em>.</em>1, 3<em>.</em>5, 3<em>.</em>72 and 3<em>.</em>83. What happens in each case? Describe the di erences. Plot the stationary values of <em>x<sub>n </sub></em>(say the di erent outcome values for a few <em>n </em>≥ 201) against the corresponding values of <em>µ</em>. Plot just the points and not lines joining the points! An adequate <em>µ</em>-interval is from 2 to 4 with smaller stepsize near 4. Try to reason about an explanation for some of your observations. What happens in particular near <em>µ </em>= 3? (A detailed explanation will arrive in Chapters 5 and 7).

Question 5 Describe all possible behaviours for the system:

where <em>λ </em>is a real number.

The system can be integrated analytically with elementary methods (it was done in one of your courses), so start by  nding the exact solution in closed form. Then plot this solution for di erent initial conditions to support your description.