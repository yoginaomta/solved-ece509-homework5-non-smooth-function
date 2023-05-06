Download Link: https://assignmentchef.com/product/solved-ece509-homework5-non-smooth-function
<br>
<ol>

 <li>Consider the following non-smooth function on the real line:</li>

</ol>

<em>f</em>(<em>x</em>) = max!

Describe the subdifferential <em>∂f</em>(<em>x</em>) at every point <em>x </em>∈R.

<ol start="2">

 <li>Prove or disprove: the subdifferential <em>∂f</em>(<em>x</em>) of a convex function is a convex set at every <em>x </em>∈R.</li>

 <li>Recall the subdifferential for the nuclear norm for an <em>n</em><sub>1 </sub>× <em>n</em><sub>2 </sub>matrix <em>X</em>.</li>

</ol>

<h1>∂$X$” = #UV <sup>T </sup>+ W : UW = <strong>0</strong>,WV = <strong>0</strong>,$W$ ≤ 1$</h1>

In the expression above, <em>X </em>has rank <em>r </em>and its SVD is <em>X </em>= <em>U</em><strong>Σ</strong><em>V <sup>T</sup></em>, where <em>U </em>is <em>n</em><sub>1 </sub>× <em>r</em>, <strong>Σ </strong>is <em>r </em>× <em>r </em>and <em>V </em>is <em>n</em><sub>2 </sub>× <em>r</em>. Recall that

<em>x</em><sup>+ </sup>= prox<em><sub>t</sub></em>!<em>c</em><em><sub>dot</sub></em>!<em>!</em>(<em>X</em>) = argmin

<em>Z</em>

if and only if

<em>X</em>−<em>X</em><sup>+ </sup>∈ <em>t∂</em>’’<em>X</em><sup>+</sup>’’<em>“</em>

Show that we can compute the prox operator above by singular value thresholding:

<em>X</em> max(<em>σ<sub>i</sub>t,</em>0)<em>.</em>

1