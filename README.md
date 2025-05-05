# cs4ll5-assignment-2-solved
**TO GET THIS SOLUTION VISIT:** [CS4LL5 Assignment 2 Solved](https://www.ankitcodinghub.com/product/cs4ll5-assignment-2-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;95710&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS4LL5 Assignment 2 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
This assignment concerns the scenario considered in the slides, where a coin Z is tossed to choose between one of two other coins A and B. The chosen coin is then tossed N times. The whole procedure is repeated D times.From the complete data set it would be easy to determine the probabilities of Z indicating A, and for each of A and B, their probabilities of turning up heads. The hidden variable variant is where as data you just know on each trial what the N coin tosses yielded with the chosen coin, but you don’t know which coin was being tossed: the outcome on Z is hidden.

Suppose the following data set, where there are just 2 trials, and the chosen coin is tossed just 2 times (this was considered in the slides):

d Z tosses of chosen coin 1?HH 2?TT

Below there is a detailed working through of a first iteration of the EM procedure for estimating parameters applied to this. For the assignment you have to give a similar working through of the second iteration.

Suppose the following notation

</div>
</div>
<div class="layoutArea">
<div class="column">
θa θb θh|a θt|a θh|b

θt|b #(d, h) #(d, t)

</div>
<div class="column">
P(Z=a)

P(Z=b)

P (h|a) ie. the head prob of coin A P (t|a) ie. the tail prob of coin A P(h|b) ie. the head prob of coin B P (t|b) ie. the tail prob of coin B num of heads in trial d

num of tails in trial d

</div>
</div>
<div class="layoutArea">
<div class="column">
If Xd is a particular trial – ie. outcomes of the N tosses of a chosen coin – the probability of the version where the chosen coin was A is given by

P (Z = a, Xd) = P (Z = a) × P (h|a)#(d,h) × P (t|a)#(d,t) = θa × θ#(d,h) × θ#(d,t)

h|a t|a

and likewise the probability of the version where the chosen coin was B is given by

P (Z = b, Xd) = P (Z = b) × P (h|b)#(d,h) × P (t|b)#(d,t) = θb × θ#(d,h) × θ#(d,t)

</div>
</div>
<div class="layoutArea">
<div class="column">
h|b

</div>
<div class="column">
t|b

</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
From these joint probability formula can work out the conditional probabilities for the hidden variable:

d P(Z = a,Xd) P(Z=a|X) = 􏰋cP(Z=c,Xd)

d P(Z = b,Xd) P(Z=b|X) = 􏰋cP(Z=c,Xd)

In the slides we used the notation γd(Z) for this, where d is index of the data item.

On the particular data set at hand the joint probability formulae are particularly simple

P(Z=a,X1) = θa×θh2|a

P(Z=b,X1) = θb×θh2|b

P(Z=a,X2) = θa×θ2 t|a

P(Z=b,X2) = θb×θ2 t|b

</div>
</div>
<div class="layoutArea">
<div class="column">
and thus the conditional probalities are:

γ1(a) = γ1(b) = γ2(a) = γ2(b) =

To carry out an EM estimation of the parameters given the data we need some initial setting of the parameters. We will suppose this is:

θa = 1 , θb = 1 , 22

θh|a = 3, θt|a = 1 44

θh|b = 1 , θt|b = 1 22

ITERATION 1

For each piece of data have to first compute the conditional probabilities of the hidden variable given the data:

d = 1 : p(Z = A, HH) = 0.5 × 0.75 × 0.75 = 0.28125 d = 1 : p(Z = B, HH) = 0.5 × 0.5 × 0.5 = 0.125

d = 1 :→ sum = 0.40625

d = 1 :→ γ1(A) = 0.692308

d = 1 :→ γ1(B) = 0.307692

d = 2 : p(Z = A, T T ) = 0.5 × 0.25 × 0.25 = 0.03125 d = 2 : p(Z = B, T T ) = 0.5 × 0.5 × 0.5 = 0.125

d = 2 :→ sum = 0.15625

</div>
</div>
<div class="layoutArea">
<div class="column">
θ a × θ h2 | a

θ a × θ h2 | a + θ b × θ h2 | b

θ b × θ h2 | b

θ a × θ h2 | a + θ b × θ h2 | b

θa × θ2 t|a

θa×θ2 +θb×θ2 t|a t|b

θb × θ2 t|b

</div>
</div>
<div class="layoutArea">
<div class="column">
θa×θ2 +θb×θ2 t|a t|b

</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
d = 2 :→ γ2(A) = 0.2 d = 2 :→ γ2(B) = 0.8

Armed with these γ values we now treat each data item Xd as if it splits into two versions, one filling out Z as a, and with ’count’ γd(a), and one filling out Z as b, and with ’count’ γd(b).

We then go through this virtual corpus accumulating counts of certain kinds of event. For events of hidden variable being Z = a and Z = b we get

E(A) = γ1(a) + γ2(a) = 0.692308 + 0.2 = 0.892308 E(B) = γ1(b) + γ2(b) = 0.307692 + 0.8 = 1.10769

Then we need to go through the Z = a cases and count types of coin toss, and likewise for Z = b cases 􏰋

</div>
</div>
<div class="layoutArea">
<div class="column">
E(A, H) =􏰋 d γd(a)#(d, h) = (0.692308 × 2 + 0.2 × 0) = 1.38462 E(A,T)= 􏰋γd(a)#(d,t)=(0.692308×0+0.2×2)=0.4

</div>
</div>
<div class="layoutArea">
<div class="column">
d

E(B, H) =􏰋 d γd(b)#(d, h) = (0.307692 × 2 + 0.8 × 0) = 0.615385

</div>
</div>
<div class="layoutArea">
<div class="column">
E(B, T ) = d γd(b)#(d, t) = (0.307692 × 0 + 0.8 × 2) = 1.6 Then from these ’expected’ counts we re-estimate parameters

est(θa) = E(A)/2 = 0.892308/2 = 0.446154

est(θb) = E(B)/2 = 1􏰋.10769/2 = 0.553846

e s t ( θ h | a ) = E ( A , H ) /􏰋 X [ E ( A , X ) ] = 1 . 3 8 4 6 2 / ( 1 . 3 8 4 6 2 + 0 . 4 ) = 1 . 3 8 4 6 2 / 1 . 7 8 4 6 2 = 0 . 7 7 5 8 6 2

est(θ ) = E(A, T )/ 􏰋 [E(A, X)] = 0.4/(1.38462 + 0.4) = 0.4/1.78462 = 0.224138 t|a X

est(θh|b) = E(B, H)/􏰋 X [E(B, X)] = 0.615385/(0.615385+1.6) = 0.615385/2.21538 = 0.277778 est(θt|b)=E(B,T)/ X[E(B,X)]=1.6/(0.615385+1.6)=1.6/2.21538=0.722222

Note the denominator 2 in the re-estimation formula for θa. We could have written the denom- inator as E(A) + E(B), but this is 􏰋d γd(a) + 􏰋d γd(b) = 􏰋d[γd(a) + γd(b)] = 􏰋d[1] = 2

</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
