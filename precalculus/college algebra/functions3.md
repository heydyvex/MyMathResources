### Operations of Functions
Related [video](https://www.youtube.com/watch?v=7N_-G4usp6Q&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=5&pp=iAQB)
- how to do operation on functions
- find set of domain first then evaluate

Let's take look at two functions
$$
\begin{alignat*}{}
f(x)=\frac{2x+3}{3x-2},\quad g(x)=\frac{4x}{3x-2}
\end{alignat*}
$$
Ok, these functions are fraction, this means we cannot have $\dfrac{(\quad) }{0}$, and zero is not allowed [[functions2]] 
so let's find the input that give us zero denominator 
$$
\begin{alignat*}{}
3x-2=0\\[4pt]
3x=2\\[4pt]
x=\frac{2}{3}
\end{alignat*}
$$
so set of Domain:
$$
D:\{x\mid x\neq\frac{2}{3}\}
$$
#### Operations
##### ex 1
###### Addition 
$$
\begin{alignat*}{}
(f+g)(x)=\frac{2x+3}{3x-2}+\frac{4x}{3x-2}\\[6pt]
\frac{6x+3}{3x-2},\quad D:\{x\mid x\neq\frac{2}{3}\}\\[6pt]
\end{alignat*}
$$
done, remember our Domain and the exception going to stick function for ever, no matter what

###### Subtraction
$$
\begin{alignat*}{}
(f-g)(x)=\frac{2x+3}{3x-2}-\frac{4x}{3x-2}\\[6pt]
\frac{-2x+3}{3x-2},\quad D:\{x\mid x\neq\frac{2}{3}\}
\end{alignat*}
$$
same as addition Domain would be that

###### Multiplication 
$$
\begin{alignat*}{}
(f\cdot g)(x)=\left(\frac{2x+3}{3x-2} \right)\left(\frac{4x}{3x-2}\right)=
\frac{8x^2+12x}{(3x-2)(3x-2)}\\[10pt]
\frac{8x^2+12x}{(3x-2)^2},\quad D:\Big\{x\mid x\neq\frac{2}{3}\Big\}
\end{alignat*}
$$
if you wondering why we did not distribute denominator, because Prof Leonard said it is better to be factored we can graph it easier and give us a vertical line and it is also best practice [video](https://youtu.be/7N_-G4usp6Q?list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&t=482)
###### Division
$$
\begin{alignat*}{}
(f/g)(x)=\frac{\dfrac{2x+3}{3x-2}}{\dfrac{4x}{3x-2}}=
\frac{2x+3}{3x-2}\cdot\frac{3x-2}{4x}\\[10pt]
\frac{2x+3}{4x},\quad D:\Big\{x\mid x\neq\frac{2}{3},~~x\neq0\Big\}
\end{alignat*}
$$
and  we have new domain $x$ can’t be used as input because of our new denominator and if you wondering why still the previous domain still cannot be input, because we $f(x)$ and $g(x)$ need that and they need to give a proper denominator that is not zero also division is depend on these functions
##### ex 2
we have these functions:
$$
f(x)=\sqrt{x+3},\quad g(x)=\frac{5}{x}
$$
let's find the domains and remember square root must be ==positive or zero== and denominator must ==not== be ==zero==
$$
\begin{alignat*}{}
f(x)=\sqrt{x+3}~~\longrightarrow~~ x+3\geq0,\quad D:\{x\mid x\geq-3\}\\[6pt]
g(x)=\frac{5}{x}~~\longrightarrow~~ x=0,\quad D:\{x\mid x\neq0\}
\end{alignat*}
$$
###### Operations 
$$
\begin{alignat*}{}
(f+g)(x)=\sqrt{x+3}+\frac{5}{x}\quad D:\{x\mid x\geq-3,x\neq0\}\\[10pt]
(f-g)(x)=\sqrt{x+3}-\frac{5}{x}\quad D:\{x\mid x\geq-3,x\neq0\}\\[10pt]
(f\cdot g)(x)=\frac{5}{x}\sqrt{x+3}\quad D:\{x\mid x\geq-3,x\neq0\}\\[10pt]
(f/g)(x)=\frac{\sqrt{x+3}}{\dfrac{5}{x}}=\frac{x\sqrt{x+3}}{5}\quad D:\{x\mid x\geq-3,x\neq0\}\\[10pt]
\end{alignat*}
$$
### Vertical line test
Related [video](https://www.youtube.com/watch?v=7j6kh8Z2H90&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=6&pp=iAQB)
- how to test a function with vertical line test

We use Vertical line test to test a function to determine whether it is a function or not, what do we mean it's a function or not? it means function give us only one output for an input or not.

![[simple-coordinate-plane.png]]

x-axis are inputs and y-axis are outputs, in another word horizontal is for inputs and vertical line for outputs 

![[Horizontal Vertical.png]]

how to test a function to determine whether it is one or not?
using vertical line test, this is how:

![[function and not function.png]]

if you draw a vertical line along the y-axis and vertical line touch more that one point on graph, it is not a function because you're getting two outputs for that, as you see in the picture.

more examples:

![[Vertical Line Test.jpg]]

![[vertical line test2.jpeg]]

Done!