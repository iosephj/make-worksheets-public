<!-- Font size for the cards HTML. Values: 100, 90, 85, 80, or 70 -->
<div class="card-size100">

<div class="front_page">

**Math 5E – Derivatives – Version 52**

**Note:** *Solve the exercises step by step.*

<!-- Insert <br> before each question, except the first on each page, without empty lines between questions -->

**1)** <span class="size70">[2p]</span> Find the derivative of $f(x)$ at $x = 4$.

<!-- Image -->
<center>![](G:/im/mat5/_i/deriv_es_52.svg)</center>

</div>

<div class="back_page">

**2)** <span class="size70">[1p]</span> Explain why the following statement is false: If a function has a zero derivative at $x_1$, then there is a local maximum or a local minimum at $x_1$.
<br>**3)** <span class="size70">[3p]</span> Differentiate $f(x) = e^{\sin(x)} \cdot \sin(e^{x})$. <br>**4)** <span class="size70">[2p]</span> Evaluate
$\lim_{x \to 0} \frac{3^{x^2} - 1 - x}{\sin(x^3)\cdot 3x}$ <br>**5)** <span class="size70">[2p]</span> Find the critical points and check whether they are local maxima or local minima for $f(x) = x^3 - 6x^2 + 9x + 1$..

</div>

</div>

<div id="solution" hidden>

**Solution**

---

**1)** <span class="size70">[2p]</span>

$f'(4) = 1$

---

**2)** <span class="size70">[1p]</span>

There could be an inflection point, which is neither a relative maximum nor a relative minimum.

---

**3)** <span class="size70">[3p]</span>

$f'(x) = e^{\sin(x)}\cos(x)\sin(e^x) + e^{\sin(x)}\cos(e^x)e^x$

---

**4)** <span class="size70">[2p]</span>

- $\lim_{x \to 0} \frac{3^{x^2} - 1 - x}{\sin(x^3),3x}$
- $= \lim_{x \to 0} \frac{3^{x^2}\ln(3),2x - 1}{\cos(x^3),3x^2,3x + \sin(x^3),3}$
- $= \lim_{x \to 0} \frac{-1}{0}$
- The limit does not exist.

---

**5)** <span class="size70">[2p]</span>

- Function: $f(x) = x^3 - 6x^2 + 9x + 1$
- Derivative: $f'(x) = 3x^2 - 12x + 9$

**Critical points**

- $3x^2 - 12x + 9 = 0$ → $x^2 - 4x + 3 = 0$ → $(x-1)(x-3) = 0$
- **x = 1** and **x = 3**

**First derivative test**

-  **$(x < 1)$:** take **$x = 0$** → $f'(0) = 9$ → positive
-  **$(1 < x < 3)$:** take **$x = 2$** → $f'(2) = -3$ → negative
-  **$(x > 3)$:** take **$x = 4$** → $f'(4) = 9$ → positive
-  **At $x = 1$:** the derivative changes from positive to negative → **local maximum**
-  **At $x = 3$:** the derivative changes from negative to positive → **local minimum**

</div>


<!-- Style definitions -->
<style>
/* Colors */
.grey1 {color: #b3b3b3;} /* my light-grey */
.grey2 {color: #999999;} /* my middle-grey */
.grey3 {color: #808080;} /* my dark-grey */
.blue1 {color: #6495ed;} /* nvim blue */
.blue2 {color: #276cdf;} /* Andrew Ng Blue */
.sky1 {color: #7dbed8;} /* nvim sky */
.sky2 {color: #27a2db;}   /* my sky */
.green {color: #81b524;} /* my green */
.red1 {color: #ec5469;} /* my coral-red */
.red2 {color: #f44336;} /* my red */
.rose {color: #ec9998:} /* nvim rose */
.gold {color: #df9d43;} /* Andrew Ng gold */
.orange1 {color: #fda556;} /* nvim orange */
.orange2 {color: #ff9505;} /*Andrew Ng orange */
.purple1 {color: #ff40ff;} /* Andrew Ng purple */
.purple2 {color: #d164d7;} /* Andrew Ng purple */
/* Font Size */
.size90 {font-size: 0.9em;}
.size85 {font-size: 0.85em;}
.size80 {font-size: 0.8em;}
.size70 {font-size: 0.7em;}
.size60 {font-size: 0.6em;}
.size50 {font-size: 0.5em;}
</style>


<!-- JS -->
<button onclick="unlock()">Access</button>
<script>
function unlock() {
  const code = prompt("Enter access code:");
  
  if (code === "sltn$") {
    document.getElementById("solution").hidden = false;
  } else {
    alert("Invalid code");
  }
}
</script>
