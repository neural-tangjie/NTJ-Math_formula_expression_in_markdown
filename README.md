# NTJ-Math_formula_expression_in_markdown
This repository shows the math formula expression in markdown.<br></br>
1. Greek alphabet 
   |spelling|lower-case|UPPER-case|
   |---|---|---|
   |alpha|$\alpha$|$\Alpha$|
   |beta|$\beta$|$\Beta$|
   |gamma|$\gamma$|$\Gamma$|
   |delta|$\delta$|$\Delta$|
   |spsilon|$\epsilon$|$\Epsilon$|
   |eta|$\eta$|$\Eta$|
   |theta|$\theta$|$\Theta$|
   |lambda|$\lambda$|$\Lambda$|
   |mu|$\mu$|$\Mu$|
   |omega|$\omega$|$\Omega$|
   |pi|$\pi$|$\Pi$|
   |xi|$\xi$|$\Xi$|
   |tau|$\tau$|$\Tau$|
   |phi|$\phi$|$\Phi$|
   |psi|$\psi$|$\Psi$|
   |upsilon|$\upsilon$|$\Upsilon$|
   |nu|$\nu$|$\Nu$|
2. In line$f(x) = x$ formula
3. Paragraph 
$$f(x) = x$$
4. Superscript
   $$x^2$$
5. Subscript
   $$x_i$$
6. Brackets
   $$\lbrace a+x \rbrace$$
   $$
   f(x)=\begin{cases}
        1, & x>0\\
        0, & x=0\\
        -1, & x<0
    \end{cases}
    $$
    $$ \langle anglebracket \rangle $$
    $$
   f(x)=\begin{cases}
        1, & x>0\\
        0, & x=0\\
        -1, & x<0
    \end{cases}
    $$
    $$ \langle anglebracket \rangle $$
   $$
   \lceil \frac{x}{2} \rceil
   $$
   $$
   \lfloor \frac{3}{x} \rfloor
   $$
   Note: the original brackets will not be scaled, such as:
   $$
   \lbrace \sum_{i=0}^{n}i^{2}=\frac{2a}{x^2+1}\rbrace
   $$
   When you need to scale brackets, you can add \left \right
   $$\left\lbrace
   \sum_{i=0}^{n}i^{2}=\frac{2a}{x^2+2}
   \right\rbrace$$

7. Summation and integration<br>
   \sum represents the sum, subscript represents the lower limit of the sum, and superscript represents the upper limit of the sum, for example:
   $$
   \sum_i^n $$
   \int denotes integral. Similarly, subscript denotes lower limit of integral and superscript denotes upper limit of integral. For example:
   $$
   \int_{1}^{\infty}
   $$
   Similar symbols include:
   $$
   \prod_{1}^{n}\\
   \bigcup_{1}^{n}\\
   \int_{1}^{n}
   $$
8. Fraction and radical<br>
   |$$\frac{2}{3}55$$|
   $$
   \frac{2}{3}
   55
   $$
9.  Font<br>
10. Special functions and symbols<br>
    $$
    \sum_{i=0}^{n}$$ 
    $$
    \prod$$
    $$
    \lim_{x\to+\infty}$$
    $$
    x_n\stackrel{p}\longrightarrow0$$
    $\vec{a}$ $\overrightarrow{a}$
    $$
    \hat y=a\hat x+b$$
    $$
    \mathtt{X}'$$
    $$
    \overline{P}$$
    $$
    \overbrace{P+Q}$$
   $$
    \sqrt[3]{2}$$ 

11. Forms<br>
    |a|b|c|
    :----|:--:|----:
    |Align left|Center|Align right|
12. Matrix<br>
    $$
      \begin{matrix}
      1 & 2 & 3 \\
      4 & 5 & 6 \\
      7 & 8 & 9
      \end{matrix} \tag{1}$$
    $$
      \begin{pmatrix}
      1 & 2 & 3 \\
      4 & 5 & 6 \\
      7 & 8 & 9
      \end{pmatrix} \tag{1.1}$$
    $$
      \begin{bmatrix}
      1 & 2 & 3 \\
      4 & 5 & 6 \\
      7 & 8 & 9
      \end{bmatrix} \tag{1.2}$$
    $$
      \begin{Bmatrix}
      1 & 2 & 3 \\
      4 & 5 & 6 \\
      7 & 8 & 9
      \end{Bmatrix} \tag{1.3}$$
    $$
      \begin{vmatrix}
      1 & 2 & 3 \\
      4 & 5 & 6 \\
      7 & 8 & 9
      \end{vmatrix} \tag{1.4}$$
    $$
      \begin{Vmatrix}
      1 & 2 & 3 \\
      4 & 5 & 6 \\
      7 & 8 & 9
      \end{Vmatrix} \tag{1.5}$$
   $$
      \left\{
      \begin{matrix}
      1 & 2 &3 \\
      4 & 5 & 6 \\
      7 & 8 & 9
      \end{matrix} 
      \right\} \tag{2}$$
   $$
      \left[
      \begin{matrix}
      1 & 2 & 3 \\
      4 & 5 & 6 \\
      7 & 8 & 9
      \end{matrix} 
      \right] \tag{3}$$
   $$
   \begin{bmatrix}
   a_{11}&a_{12}&\cdots&a_{1n}\\
   a_{21}&a_{22}&\cdots&a_{2n}\\
   \vdots&\vdots&\ddots&\vdots\\
   a_{m1}&a_{m2}&\cdots&a_{mn}\\
   \end{bmatrix}$$
13. Formula<br>
    $$
    \begin{aligned}
    a &=b+c\\
      & = d + e + f
      \end{aligned}
   $$
14. Relational operator<br>
    $\lt$ $\le$ $\leq$ $\leqq$ $\leqslant$<br>
    $\gt$ $\ge$ $\geq$ $\geqq$ $\geqslant$<br>
    $\neq$ $\approx$ $\prec$<br>
    $\sim$ $\simeq$ $\cong$<br>
    $\because$ $\therefore$
15. Arithmetic operator<br>
    $\times$ $\div$<br> $\pm$ $\mp$ $\cdot$
16. Set operators<br>
    $\cup$ $\cap$ $\setminus$<br> 
    $\subset$ $\subseteq$ $\subsetneq$ $\supset$<br>
    $\in$ $\notin$<br>
    $\emptyset$ $\varnothing$
17. Arrow operator<br>
    $\to$ $\rightarrow$ $\Rightarrow$<br>
    $\uarr$ $\darr$<br>
    $\leftarrow$ $\Leftarrow$<br>
    $\harr$ $\hArr$
18. Other operator<br>
    $\infty$ $\partial$ <br>
    $\top$ $\bot$<br>
    $\forall$ $\exists$<br>
    $\nabla$ $\triangle$<br>
    $\parallel$ $\ell$<br>
    $\oplus$ $\bigoplus$<br>
    $\circ$ $\bullet$<br>
    $\star$ $\ast$<br>