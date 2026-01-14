<!-- Font size for the cards HTML. Values: 100, 90, 85, 80, or 70 -->
<div class="card-size80">


<div class="front_page">

**Math 1st Year – Test 5 – Version 53**


**Note:** Solve each question step by step. No cell phones or calculators are allowed. You need at least 70% correct to pass the test.

<!-- Insert <br> before each question, except the first on each page, without empty lines between questions -->

**1)** <span class="size70">[2p]</span> Calculate the area and perimeter of figure 1 with $r = 10 m$. 
<br>**2)** <span class="size70">[2p]</span> Calculate the area of figure 2 with $b = 6 m$ and $h = 3 m$.
<br>**3)** <span class="size70">[2p]</span> Calculate the sides 'a' and 'b' and the perimeter of figure 3.
<br>**4)** <span class="size70">[2p]</span> A small garden has the shape of figure 4. You want to fence it, placing a post every 1 meter. How many fence posts do you need to buy?
</div>

<div class="back_page">

**5)** <span class="size70">[2p]</span> A small greenhouse has the shape of figure 4. You want to replace the plastic covering the roof. How many square meters of plastic do you need to cover the whole area?

<center>![](G:/cfr/mat1/_i/prueba5_53.svg){width=270px}</center>


</div>

</div>


<div id="solution" hidden>

**Solution**

---

**1)** <span class="size70">[2p]</span> 

**Circle with r = 10 m**

- Area (Circle): $A = \pi r^2 = 3.1416 \cdot 10^2 = 3.1416 \cdot 100 \approx 314.16 , \text{m²}$
- Perimeter (circumference): $P = 2 \pi r = 2 \cdot 3.1416 \cdot 10 \approx 62.83 , \text{m}$

**Answer:** Area ≈ 314.16 m², Perimeter ≈ 62.83 m

---

**2)** <span class="size70">[2p]</span>

**Triangle with b = 6 m, h = 3 m** 

- Area: $A = \frac{b \cdot h}{2} = \frac{6 \cdot 3}{2} = \frac{18}{2} = 9 , \text{m²}$

**Answer:** Area = 9 m²

---

**3)** <span class="size70">[2p]</span> 

- $a = 3 - 2 = 1 \text{m}$
- $b = 2.5 - 1.5 = 1 \text{m}$
- Perimeter:
   + Adding each side: $3 + 2.5 + 2 + 1 + 1.5 + 1 = 11 \text{m}$
   + Another way: $3 \cdot 2 + 2.5 \cdot 2 = 6 + 5 = 11 \text{m}$

**Answer:** Perimeter = 11 m

---

**4)** <span class="size70">[2p]</span> 

- Perimeter: $8 + 3 + 6 + 3.5 = 20.5 \text{m}$
- If I have to place a fence post every 1 meter, that is the same as dividing the perimeter by 1, which gives: $20.5 ≈ 20$

**Answer:** You need to buy 20 fence post

---

**5)** <span class="size70">[2p]</span>

- We split the land into two known shapes, a triangle and a rectangle:
   + Triangle area: $A1 = \frac{b \cdot h}{2} = \frac{(8-6) \cdot 3}{2} = \frac{6}{2} = 3 \text{m²}$
   + Rectangle area: $A2 = b \cdot h = 6 \cdot 3 = 18 \text{m²}$
   + Total area: $A1 + A2 = 18 + 3 = 21 \text{m²}$
- Another way is to use the trapezoid area formula

**Answer:** Yu need 21 square meters of plastic

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
