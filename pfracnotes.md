Encoding:           UTF-8  
LaTeX Input:        mmd-article-header  
Title:              Partial fractions expansions  
Subtitle:           Review and further development for Laurent series and residues
Affiliation:        The College of Idaho  
Date:               1 April 2013  
base header level:  2  
LaTeX Mode:         article  
Font theme:         structurebold  
Color theme:        crane  
Theme:              Szeged  
LaTeX Input:        mmd-article-begin-doc 
LaTeX Footer:       mmd-memoir-footer 

Let us find the partial fractions decomposition of 
<!-- \[
R(z) = \frac{z^2 + 4}{(z-2)(z-3)^2}.
\] -->
The denominator is already factored and its degree exceeds that of the numerator. The PF expansion takes the form indicated in Theorem 2 of section 3.1:
<!-- \[
\frac{z^2 + 4}{(z-2)(z-3)^2} = \frac{A^{(1)}_{0}}{z-2} + \frac{A^{(2)}_{0}}{(z - 3)^2} + \frac{A^{(2)}_{1}}{z - 3}
\]
 -->
Multiplying by \\( z - 2 \\) and taking a limit, we find that
<!-- \[
A^{(1)}_{0} = \lim_{z \to 2} (z - 2) R(z) = 8.
\] -->
To find \\( A^{2}_{0} \\) the process is similar:
<!-- \[
A^{(2)}_0 = \lim_{z \to 3} (z - 3)^2 R(z) = 13.
\] -->
Finally, to find \\( A^{(2)}_{1} \\), we add another step of differentiating. Observe that the \\( z \\)-derivative of \\( (z-3)^2 R(z) \\) is
<!-- \[
\frac{d}{dz} \left( (z-3)^2 R(z) \right) = \frac{d}{dz} \left( \frac{A^{(1)}_{0} (z-3)^2}{z-2} \right) + A^{(2)}_{1}}.
\] -->
Taking the limit of each side as \\( z \to 3 \\), we find that \\( A^{(2)}_{1} \\) is equal to
<!-- \[
\lim_{z \to 3} \frac{2z(z-2) - (z^2 + 4)}{(z-2)^2} = \frac{2 \cdot 3 \cdot 1 - 13}{1^2} = -7.
\] -->

- this is a rigged example, often the coefficients are fractional
- don't be alarmed if coefficients are sometimes 0
- analogy to factored form for zeroes.
- how do zeroes and poles behave under differentiation
- problem 4 
- residues
- problems 19, 20, 21
