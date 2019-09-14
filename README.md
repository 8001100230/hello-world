Math 181 Miniproject 1: Modeling and Calculus.md
---
Math 181 Miniproject 1: Modeling and Calculus
===

**Overview:** In this miniproject you will use technological tools to turn data and into models of real-world quantitative phenomena, then apply the principles of the derivative to them to extract information about how the quantitative relationship changes. 

**Prerequisites:** Sections 1.1--1.5 in *Active Calculus*, specifically the concept of the derivative and how to construct estimates of the derivative using forward, backward and central differences. Also basic knowledge of how to use Desmos. 

---

:::info
1\. The table below gives the distance that a car will travel after applying the brakes at a given speed.
| Speed (in mi/h) 	| Distance to stop (in ft) 	|
|-----------------	|--------------------------	|
| 10              	| 5                        	|
| 20              	| 19                       	|
| 30              	| 43                       	|
| 40              	| 76.5                     	|
| 50              	| 120                      	|
| 60              	| 172                      	|
| 70              	| 234                      	|

(a) Find a function $f(x)$ that outputs stopping distance when you input speed. This will just be an approximation. To obtain this function we will first make a table in Desmos. The columns should be labled $x_1$ and $y_1$. Note that the points are plotted nicely when you enter them into the table. Click on the wrench to change the scale of the graph to fit the data better. Since the graph has the shape of a parabola we hope to find a quadratric formula for $f(x)$. In a new cell in Desmos type
\\[
y_1\sim ax_1^2+bx_1+c
\\]
and let it come up with the best possible quadratic model. Use the suggested values of $a$, $b$, and $c$ to make a formula for $f(x)$.
:::

(a)
    f(x)=0.047619x^2+0.0119048x-0.0714286






:::info
(b) Estimate the stopping distance for a car that is traveling 43 mi/h.
:::

(b) 
88.5 ft



:::info
(c\) Estimate the stopping distance for a car that is traveling 100 mi/h.
:::

(c)
477.3 ft
:::info
(d) Use the interval $[40,50]$ and a central difference to estimate the value of $f'(45)$. What is the interpretation of this value?
:::

(d) f'(45)=4.3




:::info
(e) Use your function $f(x)$ on the interval $[44,46]$ and a central difference to estimate the value of $f'(45)$. How did this value compare to your estimate in the previous part?
:::


(e)
The answer remains the same as 4.3



:::info
(f) Find the exact value of $f'(45)$ using the limit definition of derivative.
:::

(f)Here's a sample of how to write a limit using LaTeX code. $\lim_{h \to 0}\frac{f(x+h)-f(x)}{h}$







:::success
2\. Suppose that we want to know the number of squares inside a $50\times50$ grid. It doesn't seem practical to try to count them all. Notice that the squares come in many sizes.
![A 50x50 grid](https://i.imgur.com/vm5fGdC.png =300x300)

(a) Let $g(x)$ be the function that gives the number of squares in an $x\times x$ grid. Then $g(3)=14$ because there are $9+4+1=14$ squares in a $3\times 3$ grid as pictured below.
![A 3x3 grid containing 9 1x1 squares, 4 2x2 squares and 1 3x3 square](https://i.imgur.com/JGhNudW.png =405x90)
Find $g(1)$, $g(2)$, $g(4)$, and $g(5)$. 
:::

(a)g(1)=1, g(2)=5, g(4)=16+9+4+1=30, g(5)=25+16+9+4+1=55


:::success
(b) Enter the input and output values of $g(x)$ into a table in Desmos. Then adjust the window to display the plotted data. Include an image of the plot of the data (which be exported from Desmos using the share button ![A picture of a "share" icon](https://i.imgur.com/lQGRxeG.png)). Be sure to label your axes appropriately using the settings under the wrench icon ![A picture of a "grid" icon](https://i.imgur.com/rNnK775.png).
:::

(b)![](https://i.imgur.com/XjiyZLO.png)



:::success
(c\) Use a cubic function to approximate the data by entering
\\[
y_1\sim ax_1^3+bx_1^2+cx_1+d
\\]
into a new cell of Desmos (assuming the columns are labeled $x_1$ and $y_1$). Find an exact formula for $g(x)$.
:::

(c\)
f(x)=0.333333x^3+ 0.5x^2+0.166667x+0


:::success
(d) How many squares are in a $50\times50$ grid? 
:::

(d)
42924



:::success
(e) How many squares are in a $2000\times2000$ grid? 
:::

(e)
2668664333


:::success
(f) Use a central difference on an appropriate interval to estimate $g'(4)$. What is the interpretation of this value? 
:::

(f)
g'(4)=【g(4+1)-g(4-1)】/2*1= g(5)-g(3)】/2= 20.5

---

To submit this assignment click on the Publish button ![Publish button icon](https://i.imgur.com/Qk7vi9V.png). Then copy the url of the final document and submit it in Canvas.

