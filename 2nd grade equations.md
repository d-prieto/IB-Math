# Second grade equations

###### tags: `math`, `IB`

## Introduction and context

Hi there, I'm David Prieto and I'm doing these classes here in markdown because I think that they are cool and I'm used to document stuff for me and for people that come after me. 

This is going to be the class about 2nd grade equations. I'm using the book from the editorial 0xford "Mathematics, Analysis and Approaches" (A A for short) of the IB diploma. 

I'm using [this](https://math.meta.stackexchange.com/questions/5020/mathjax-basic-tutorial-and-quick-reference) to write the cool mathematic stuff

## What have we seen

We are on topic of __Functions__ and we covered that there are 3 things that we _need_ to know. 

This is an equation:

$x^2 + 22 = 2$

This is a function: 


$f(x) = x^2 + 22 - 2$

And this is an inequation: (because it's not equal but it has another sign, such us $\lt , \gt, \le,  \geq$)

$x^2 + 22 > 2$


## 2nd grade equations

### The quadratic formula

The general form of a 2^nd^ grade equation is $ax^2+bx+c=0$ where $a \neq 0$. For that we have a general formula: 

$$
x = {-b \pm \sqrt{b^2-4ac} \over 2a}
$$

This is the **quadratic formula**

The solutions for a **quadratic equation** can be either **zero, one or two** within the Real numbers ($\Bbb R$). They are called **roots**

But there are _sometimes_ easier ways to solve that with this formula of the booklet. Also the book covers an exercise of demostration of this formula (added here in the extras).


### Solving by factorization

Sometimes we find quadratic equations that are easy to express (or they already expressed) like $a(x - p)(x - q) = 0$. In this case we can solve using the **zero-product property** that is that one of this 3 factors **has** to be 0. 

Since $a \neq 0$, then:

$(x-p) =0$
or 
$(x-q) =0$

Either option is valid, so we have 2 possibilities: $x_1$ and $x_2$ that in this case they are:

$x_1 = p$
$x_2 = q$

#### Developments of this

If we have $a(x-p)x=0$ is the same that saying that we have $a(x-p)(x-0)=0$ so we can know that in this case one of the **roots** is going to be zero. 

So we can solve easily any equation $ax^2+bx+c=0$ where $c=0$ because $ax^2+bx=0$ is the same as $ax(x+\frac ba)=0$

#### Finding factorizations

There are sometimes ways to see if there are "easy" factorizations from some expresions $ax^2+bx+c=0$. Let's try to go from the other side, from the factorized form to the general one. 

if we have $a(x - p)(x - q) = 0$ we can expand it like this:

$a(x - p)(x - q) = a(x^2 - xq - xp + pq) = a(x^2 -(p+q)x + pq)$

We can distribute the factor $a$ but it's easier to find this patern. For example: 

- For $x^2-5x+6$: 5 is 2+3 (p+q) and 6 is 2·3 (pq) so it can be expressed as $(x-2)(x-3)$ and the roots are **2** and **3**

- For $x^2+3x+2$: -3 is -1-2 (p+q) and 2 is -1·-2 (pq) so it can be expressed as $(x+1)(x+2)$ and the roots are **-1** and **-2**

### Rewriting equations 

~page~ ~156~

Sometimes life is hard and you don't have a nice cool equation to solve and go to do other things and they are hidden, usually with other factors. We need to convert them to terms we can solve, either with the general formula or using factorization. Usually we collect all the information in one side of the equation. 

![](https://i.imgur.com/C1QLwKJ.png)

### Quadratic equation that involves perfect squares:

~page~ ~157~

Let's get back to a simple equation of $x^2 =9$ . We can write it like $x^2 - 9= 0$ and this can be factorized like $(x-3)(x+3)=0$. So the solutions are +3 and -3, we can express it in a condensed form using $\pm$ simbol (plus-minus, "más-menos" in Spanish) $x=\pm 3$ 

This kind of equations are called **perfect square**


### Completing the square

Go to page 160 for the explanation

## 2nd grade inequations

~page~ ~169~

Inequations unlike equations usually have  _ranges_ instead of discrete solutions. 

For example 

$x^2 \geq 4$ this is going to be true when $x\geq 2$ (for example, $3^3 =9$) and when $x\leq -2$ (for example, $-3^3 =9$) so we write that the solution is 

$x\geq 2$ or $x\leq -2$

### Extras

#### Homework

1) Find the value of x using whichever method you want

* $\pi x^2 - 60=0$
* $x^2-5x+6=0$
* $x(x+5)=x(x-3)$
* $x^2-5x+6>0$ (this is an inequation, it's not a typo)
* $(x-3)^2=64$

2) We have 4 functions using the variable $t$.
* $f(t)=t^2$
* $g(t)=-2(t-3)(t+2)$
* $h(t)=2t+3$
* $j(t)=-t-2$

   a) Find the 6 six posible intersections 

    $f(t)\cap g(t)$
    $f(t)\cap h(t)$
    $f(t)\cap j(t)$
    $g(t)\cap h(t)$
    $g(t)\cap j(t)$
    $h(t)\cap j(t)$
    
    First do them analytically

    ```
    How to make the intersecton of 2 functions:
    The intersection of 2 functions are the values of the variable (t in this case) are the same. So you only need to make one funcion equal to another
    ```

    For example: 
    
    To do: $h(t)\cap j(t)$ we make  $j(t)=-t-2$ equal to $h(t)=2t+3$, so:
    
    $j(t)=h(t)$ and that means:
    $-t-2=2t+3$ then we solve for $t$

    ```
    Note: there are some intersections with 1 point, 2 points or zero points
    ```

    b) Now **draw the graphics** (horizontal axis is going to be $t$, instead of $x$) of the 4 functions and check if what you found using _pure harsh analysis_ is the same that you can find drawing these functions

* _extra point_ why are there 6 posible intersections and not 4 or 24? (not related to 2nd grade equations but related to the IB diploma)



#### Demostration of the general formula (exercise)

![](https://i.imgur.com/nUz2WKy.png)

Left column for the demostration, right column for naming the steps

![](https://i.imgur.com/We9Jfbz.png)
