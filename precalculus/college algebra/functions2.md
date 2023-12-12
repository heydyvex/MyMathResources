### function evaluation

Related [video](https://www.youtube.com/watch?v=p1sGAHulT8w&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=3&pp=iAQB)
- How to evaluate Functions
- Two kine of domains that can cause issues

first of all  $y=-7x+5$ and $f(x)=-7x+5$ are the same, $f(x)$ is going map to $y$ and
$f(x) = y$ basically and most of the time you’ll see this $f(x)$ notion.
and name of the function can be change to something else like $g(x)$ or $p(x)$.

$$
\begin{align}
& y=-7x+5\quad\textbf{is}\quad f(x)=-7x+5 \\ 
& y=\frac{3}{2}x-1\quad\textbf{is}\quad f(x)=\frac{3}{2}x-1
\end{align}
$$
#### function evaluation
So let's evaluate some function and have fun
please try other input practice more and more to get better
###### number 1
we have this function:
$$
h(x)=-2x^2+x-1
$$
what is $h(-1)$ ? 
all it want is just to take $-1$ and substitute into $x$ and evaluate it, that's it!
$$
\begin{alignat*}{}
&h(-1)=-2(~~)^2+(~~)-1\\[6pt]
&h(-1)=-2(-1)^2+(-1)-1\\[6pt]
&-4
\end{alignat*}
$$
for $-1$ it maps $-4$ so $(-1, -4)$
what about $h(x+h)$ ? well treat it just like a number
$$
\begin{alignat*}{}
&h(x+h)=-2(~~)^2+(~~)-1\\[6pt]
&h(x+h)=-2(x+h)^2+(x+h)-1\\[6pt]
&-2(x^2+2xh+h^2)+x+h-1\\[6pt]
&-2x^2-4xh-2h^2+x+h-1\\[6pt]
&-2x^2-2h^2-4xh+x+h-1
\end{alignat*}
$$
done!
###### number 2
we have this function:
$$
f(x)=\sqrt{x^2-3x}
$$
what is $f(5)$?
$$
\begin{alignat*}{}
&f(5)=\sqrt{(~~)^2 - 3(~~)}\\[6pt]
&f(5)=\sqrt{(5)^2-3(5)}\\[6pt]
&\sqrt{10}
\end{alignat*}
$$
for $5$ it maps $\sqrt{10}$ , so $(5, \sqrt{10})$
but for input $1$ and $2$ you get $\sqrt{-2}$ and this a domain issue

###### number 3
we have this function
$$
g(x)=\frac{2x+1}{x-5}
$$
what is $g(0)$ ?
$$
\begin{alignat*}{}
&g(0)=\frac{2(~~) + 1}{(~~)-5}\\[6pt]
&g(0)=\frac{2(0)+1}{0-5}\\[6pt]
&\frac{1}{-5}
\end{alignat*}
$$
for $0$ it maps $\dfrac{1}{-5}$ 
but for $5$ it maps $\dfrac{11}{0}$ and this is undefined 

##### Domain issue 
Did you realize for square roots and fractions it is possible to get output complex number or undefined? so this something that you should be aware of it.

### Finding the Domain of Functions
Related [video](https://www.youtube.com/watch?v=LvUCDcp6Z3k&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=4&pp=iAQB)
##### Domains 
Domain is the set of inputs of a Function that give a Real Number output 

Two problem areas:
- Square roots: $\sqrt{\quad}$ inside Must be Positive (cannot be negative and in that case it is Complex number )
- Denominators: $\dfrac{\quad}{(\quad)}$ Cannot equal Zero (it that case it is undefined )

##### examples
###### ex 1
Take look at this function:
$$
f(x)=\sqrt{5-4x}
$$
this is square root and according to problem areas, we need to make sure that inputs give you ==positive== square root
so we take equation inside square root and:
$$
\begin{alignat*}{}
5-4x\geq0\\[6pt]
-4x\geq-5\\[6pt]
x\leq\frac{5}{4}\\[6pt]
\end{alignat*}
$$
and we got it! as long as $x$ is $\leq\dfrac{5}{4}$ our output will be positive square root
we write:
$$
D:\Big\{x\mid x\leq\frac{5}{4}\Big\}
$$
or
$$
\left( -\infty, \dfrac{5}{4} \right]
$$
Done!

###### ex 2
the function:
$$
g(t)=\dfrac{5t}{t^3-16t}
$$
this is division and we have to make sure that denominator not to be $0$ , because it is undefined 
so we extract equation in denominator and:
$$
\begin{alignat*}{}
t^3-16t=0\\[6pt]
t(t^2-16)=0\\[6pt]
t(t+4)(t-4)=0\\[6pt]
t=0, t=4,t=-4\\[6pt]
\end{alignat*}
$$
so if input $t$ is not $0, 4, -4$ our denominator will be any number except $0$ and with this inputs our denominator is $0$ and it is undefined 
so:
$$
D:\{x\mid \text{All Real Number except:}
~~~t\neq0, t\neq4, t\neq-4 \}
$$
or:
$$
\left(-\infty,-4\right)\cup\left(-4,0\right)\cup\left(0,4\right)\cup\left(4,\infty\right)
$$
Done