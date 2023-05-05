---
title: "Reference Solutions for MA114 Final Review"
author: "Dr. Ye"
format: 
  html:
      abstract: "Those references solutions are for MA114 final review of QCC. A pdf version can be found at <https://fyeteaching.github.io/MA114RefSols/main.pdf>. Please let me know if you see any mistakes. Thank you!"
      # theme: pandoc
      header-includes: |
        <style>@import url('https://fonts.googleapis.com/css2?family=Nunito:ital,wght@0,400;0,600;0,700;1,600;1,700&display=swap');</style>
      mainfont: Nunito
      backgroundcolor: '#daffef'
      self-contained: true
      html-math-method:
        method: mathjax
        url: "https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-svg.js"
      license: CC BY-NC-SA 3.0
      comments:
        hypothesis: true
      output-file: index.html
  pdf:
      abstract: "Those references solutions are for MA114 final review of QCC. A web version can be found at <https://fyeteaching.github.io/MA114RefSols/>. Please let me know if you see any mistakes. Thank you!" 
      documentclass: article
      classoption: [12pt]
      geometry:
        - margin=0.8in
      fontfamily: libertinus
      colorlinks: true
      header-includes:
        - \usepackage{datetime}
        - \newdateformat{mydate}{\monthname[\THEMONTH], \THEYEAR}
        - \usepackage{fancyhdr}
        - \fancyhf{}
        - \pagestyle{fancy}
        - \lhead{\mydate{\today}}
        - '\rhead{Reuse: \href{https://creativecommons.org/licenses/by-nc-sa/3.0/}{CC BY-NC-SA 3.0}}'
      keep-tex: true
      output-file: main.pdf
      latex-clean: true
---

1. Using calculator to calculate, you will find that the product $AB$ is
    $$
    AB=\begin{bmatrix}22 & -20\\16 & 16\\-24 & 48\end{bmatrix}.
    $$
2. To solve for $T_1$, clearing the denominator first.
    $$
    \begin{aligned}
    S=&\frac{T_1+3 T_2}{4 T_1}\\
    4ST_1=&T_1+3 T_2\\
    4ST_1-T_1=&3 T_2\\
    (4S-1)T_1=&3 T_2\\
    T_1=&\frac{3 T_2}{4S -1}
    \end{aligned}
    $$

3. In vector forms, the vectors are
    $$\vec{A}=<60\cos(164^\circ), 60\sin(164^\circ)>\approx<-58, 17>,$$
    $$\vec{B}=<32\cos(222^\circ), 32\sin(222^\circ)>\approx<-24, -21>.$$
    Then the sum is
    $$A+B\approx <-58, 17> + <-24, -21> =  <-82,  -4>.$$
    The magnitude is $\sqrt{(-82)^2+(-4)^2} \approx 82$. Because the vector is pointing to the third quadrant, the direction is $180^\circ+\tan^{-1}\left(\frac{-4}{-82}^\circ \right)\approx 183^\circ$.

    Note if your have more significant digits in the middle steps, the angle you get may off a few degrees. But that is fine.

4. To add the radical expressions, simplifying them first.
    $$
    6 \sqrt{18}-3 \sqrt{2}+\sqrt{32}=6 \cdot 3 \sqrt{2}-3 \sqrt{2}+4 \sqrt{2} = 19 \sqrt{2}.
    $$

5. To convert units, the following unit ration will be used.
    $$1\text{ hm}=10^2 \text{ m}\quad 1\text{ m}=10^2 \text{ cm}\quad 1\text{ yd}=91.44 \text{ cm}.$$ 
    a. $2.45\text{ hm}=2.45\times 10^4\text{ cm}=24500\text{ cm}$

    b. $3.5\text{ yd}=3.5\text{ yd}\cdot\dfrac{91.44\text{ cm}}{1\text{yd}} = 320.04 \text{ cm}\approx 320\text{ cm}.$

    c. Since the right most significant of the measurement 12.3 mg is at the tenth place, the precision is 0.1 mg.

    d. The greatest possible error is half of the precision which is 0.05 mg.

6. Since $w$ varies directly as $x$ and the square of $y$ and inversely as $z$, there is a constant $k$ such that $w=\dfrac{kxy^2}{z}$. The number $k$ is determined by the equation
   $$18=\frac{k \cdot 4 \cdot 6^2}{12}.$$
   Solving for $k$ yields
   $$k=\frac{18 \cdot 12}{4\cdot 6^2} = \frac{3}{2}.$$
   Then when $x=3$, $y=4$, and $z=9$,
   $$w=\frac{ \frac{3}{2} \cdot 3\cdot 4^2}{9} = 8.$$

7. Note that for a positive $b$, $\sqrt{-b}=i\sqrt{b}$. Then
   $$2 \sqrt{-45}-4 \sqrt{-5} = 2 \cdot 3 \sqrt{5} ~i-4\cdot \sqrt{5} ~i = 2 \sqrt{5} ~i.$$

8. To evaluate the function at given value, plugging the value into the defining expression and simplify.
   $$f(-4)=3(-4)^2+4(-4)-18 = 14.$$

9. Since the force, $F$, varies inversely with the distant $d$, there is a number $k$ such that $F=\frac{k}{d}$. The number $k$ is determined by the equation $0.250 \text{ N}=\frac{k}{1.75 \text{ cm}}$. Solving for $k$, we get $k=0.250\cdot 1.75 \text{ N-cm}$, here the dash symbol in the unit means the product (the multiplication). Therefore, when $d=1.25 \text{ cm}$, the force is
    $$F=\frac{0.250\cdot 1.75 \text{ N-cm}}{1.25 \text{ cm}}= 0.350 \text{ N}.$$

    Note that the reason of keeping the extra zero at the end of the answer is that the least number of significant digits from the measurements is $3$.

10. The slopes of a pair of perpendicular line are negatively reciprocal to each other. Form the given slope-intercept form equation, we know the slope of the given line is $m=-\frac13$. Therefore, the slope of the perpendicular line is $m_\perp=-\frac1m=3$. Because the perpendicular line passes through $(-6, 8)$, it is defined by the point-slope form equation
    $$y=3(x-(-6))+8.$$
    Simplifying the equation yields the slope-intercept form equation
    $$y=3x+26.$$

11. The earning varies directly with the working hour by the pay scale. Denote by $M$ the earning, $H$ the working hours, and $r$ the pay scale. The relation between them is
    $$M=rH \quad \text{or} r=\frac{M}{H}.$$
    Since Isabella earns \$2400 for 80 hours working, the pay scale is $r=\frac{\$ 2400}{80 \text{ h}}= \$30/\text{h}$.
    If she works for 25 hours, she will earn
    $$25\text{ h}\cdot \$30/\text{h}=\$ 750.$$

12. Note that $i^2=-1$. Then
    $$
    \begin{aligned}
    &(8- 2~i)(6 + 3~i)\\
    =& 48 + 24~i -12~i -6~i^2\\
    =& 48 + 12 ~i - 6(-1)\\
    =& 48 + 12 ~i + 6\\
    = & 54+12~i.  
    \end{aligned}
    $$

13. The linear system can be written in the following form using matrices:
    $$
    \begin{bmatrix}
      8.4 & -1.2 \\ 3.5 & 2.6
    \end{bmatrix}
    \begin{bmatrix}
      x \\ y
    \end{bmatrix}
    =\begin{bmatrix}
      10.8 \\ 6.4
    \end{bmatrix}.
    $$
    Multiplying the inverse of the coefficient matrix, that is the $2\times 2$ appeared in the matrix equation, we will get the solution.
    $$
    \begin{bmatrix}
      x \\ y
    \end{bmatrix}
    =\begin{bmatrix}
      8.4 & -1.2 \\ 3.5 & 2.6
    \end{bmatrix}^{-1}\begin{bmatrix}
      10.8 \\ 6.4
    \end{bmatrix} \approx \begin{bmatrix}1.4 \\ 0.6\end{bmatrix}.
    $$
    That is that $x\approx 1.4$ and $y\approx 0.6$.

14. The takeoff point, the end of the runway, and the plane over the end of the runway forms a right triangle, where the altitude, say $a$ ft, over the length, $l=875$ ft, of the runway is the tangent of the takeoff angle $\theta=30^\circ$, that is
    $$\frac{a}{875}=\tan(30^\circ).$$
    Therefore, the altitude is
    $$a=875\tan(30^\circ) \approx 505.2\text{ ft}.$$

15. To solve the equation, first rewrite the equation into the standard form $ax^2+bx+c=0$, then apply the quadratic formula.
    $$
    \begin{aligned}
      2x^2 - 3x = & 10\\
      2x^2 - 3x -10= & 0\\
      x= &\frac{-(-3)\pm\sqrt{(-3)^2-4\cdot 2\cdot (-10)}}{2\cdot 2}\\
      = &\frac{3 \pm \sqrt{89}}{4}.
    \end{aligned}
    $$
    Therefore, the solutions are approximately $x\approx 3.1$ and $x\approx -1.6$.

16. The equation can be solved using the quadratic formula or completing the square. In question 15, you've already seen the quadratic formula. Here, we will solve it by completing the square. Note that a quadratic polynomial $ax^2+bx+c$ can be rewritten as follows
    $$ax^2+bx+c=a(x-h)^2+k,$$
    where $h=-\dfrac{b}{2a}$ and $k=ah^2+bh+c$.
    In this case, $h=-\dfrac{4}{2\cdot 1}=-2$ and $k=(-2)^2+4(-2)+29=25$.
    Then the equation can be written in the perfect square form and then solved by the square root property.
    $$
    \begin{aligned}
        x^2+4x+29=&0\\
        (x-(-2))^2+25=&0\\
        (x-(-2))^2=&-25\\
        x-(-2)=&\pm\sqrt{-25}\\
        x=&-2\pm 5 ~i.
    \end{aligned}
    $$

17. To rationalize the denominator when the denominator has two terms with a square root, multiply the conjugate of the denominator to both the numerator and denominator and then simply.
    $$
    \begin{aligned}
      \frac{4-3\sqrt{2}}{6+\sqrt{2}}
      =&\frac{(4-3\sqrt{2})(6-\sqrt{2})}{(6+\sqrt{2})(6-\sqrt{2})}\\
      =&\frac{24-4\sqrt{2}-18\sqrt{2}+3(\sqrt{2})^2}{6^2-(\sqrt{2})^2}\\
      =&\frac{30 - 22 \sqrt{2}}{34}\\
      =&\frac{15 - 11 \sqrt{2}}{17}
    \end{aligned}
    $$

18. There are different ways to simplify a complex rational expression. One way is to simplify the numerator and the denominator and then rewrite as a multiplication the numerator times the reciprocal of the denominator. Another way is to multiply the LCD to both the numerator and the denominator to clear denominators. We will take the first approach.
    $$
    \begin{aligned}
    \frac{~\frac{3}{2}+\frac{4}{x}~}{~\frac{1}{x}-\frac{2}{3x}~}
    &=\frac{~\frac{3x}{2x}+\frac{2\cdot 4}{2x}~}{~\frac{3}{3x}-\frac{2}{3x}~}\\[0.5em]
    &=\frac{~\frac{3x+8}{2x}~}{~\frac{1}{3x}~}\\[0.5em]
    &=\frac{3x+8}{2x}\cdot\frac{3x}{1}\\[0.5em]
    &=\frac{3(3x+8)}{2}\\
    &=\frac{9x+24}{2}.
    \end{aligned}
    $$

19. The conversion factor between degree and radian is $180^\circ=\pi \text{ rad}$.
    Therefore,
    $$330^\circ = 330^\circ\cdot\frac{\pi \text{ rad}}{180^\circ}= \frac{11\pi}{6} \text{ rad}\approx 5.8 \text{ rad}.$$
    $$\frac{5\pi}{3}\text{ rad}=\frac{5\pi}{3}\text{ rad}\cdot\frac{180^\circ}{\pi \text{ rad}}= 300^\circ.$$

20. Let $f(x)=-x^2-4 x+12$.
      a) The axis of symmetry is $x=-\frac{b}{2a}=-\frac{-4}{2(-1)} = -2$.
      b) The coordinates of the vertex is $\left(-\frac{b}{2a}, f\left(-\frac{b}{2a}\right)\right)$. Since $-\frac{b}{2a}=-2$ and $f(-2)=-(-2)^2-4(-2)+12 = 16$. The vertex is $(-2, 16)$.
      c) The coordinates of the $y$-intercept is $(0, c)=(0, 12)$.
      d) To get thhe coordinates of the $x$-intercepts, solve the equation $f(x)=0$ first.
          $$
          \begin{aligned}
          -x^2-4 x+12=&0\\
          x^2+4 x-12=&0\\
          (x - 2) (x + 6)=&0\\
          x - 2 = 0 \quad\text{or}&\quad x + 6=0\\
          x = 2 \quad\text{or}&\quad x = -6.
          \end{aligned}
          $$
          Therefore, the $x$-intercepts are $(2, 0)$ and $(-6, 0)$.

21. Since $\angle C=90^{\circ}$, the triangle is a right triangle. The side $AC$ is the opposite side of the angle $\angle B$. The side $AB$ is the hypotenuse as it's in the opposite of the right angle $\angle C$. Then side $BC$ is the adjacent side to the angle $\angle B$. From the definition of trigonometric functions, we know that
    $$\sin(\angle B)=\frac{AC}{AB}\qquad \tan(\angle B)=\frac{AC}{BC}$$
    which yields two equations
    $$\sin(42^\circ)=\frac{32}{AB}\qquad \tan(42^\circ)=\frac{32}{BC}.$$
    Solving the equations (flipping and clearing the denominator) yields
    $$AB=\frac{32}{\sin(42^\circ)}\approx 47.8 \text{ cm}\qquad BC=\frac{32}{\tan(42^\circ)}\approx 35.5 \text{ cm}.$$

22. a) $\theta=\sin^{-1}(0.436) \approx 0.451$. 
    b) $\cos 240^{\circ}=-\cos(240^\circ-180^\circ)-\cos(60^\circ)=-\frac{1}{2}$.
    c) $\tan\left(\frac{5\pi}{6}\right)=-\tan\left(\pi-\frac{5\pi}{6}\right)=-\left(\frac{\pi}{6}\right) = - \frac{\sqrt{3}}{3}\approx -0.577$.

23. The angle $120^\circ$ is $120^\circ\cdot\frac{\pi}{180^\circ}=\frac{2\pi}{3}$ radian. Then the length of the arc is $s=r\theta=12\cdot\frac{2\pi}{3}=8\pi\approx 25.1$ inches. The area of the sector is $A=\frac{1}{2}r^2\theta=\frac{1}{2}\cdot12^2\cdot \frac{2\pi}{3} = 48 \pi \approx 150.8$ square inches.

24. a) The amplitude of $y=-3\sin(2x)$ is $|-3|=3$. The period is $\frac{2\pi}{2}=\pi$. The graph is shown as follows.
    ![](y=-3sin(2x).png){width=80%}
    
    b) The amplitude of $y=4\cos\left(\frac{\pi x}{3}\right)$ is $|4|=4$. The period is $\frac{2\pi}{\frac{\pi}{3}}=6$. The graph is shown as follows.
    ![](y=4cos(pix3).png){width=60%}
    
