# bayesian-homework-1-solved
**TO GET THIS SOLUTION VISIT:** [Bayesian Homework 1 Solved](https://www.ankitcodinghub.com/product/bayesian-homework-1-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;98855&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Bayesian Homework 1 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
Homework 1 Data

The data in ‘NFL_pos_spending_2022.csv’ represent positional spending (in millions of dollars) in 2022 based on player salaries in the National Football League (NFL) at various positional groups (e.g., total spending for quarterbacks, running backs / full backs, wide receivers, etc) per team.

For this homework assignment, we seek to infer whether mean spending is greater for the quarterback (QB) position than for the wide receiver (WR) position in the NFL. There is a conventional understanding that the quarterback position is the most important position in American football, but one measure of value is total spending on that position. Keep in mind that there are usually many more WR individuals on a team than QB individuals, thus total spending per position includes the salaries of all individuals who play at that position.

Questions

Prepare a written response to the following, using Overleaf. The assignment shouldn’t be longer than 10 (double-spaced, excluding title page, references, and appendices). Due Thurs., Feb. 3, at the beginning of the class period. Please submit the assignment as a PDF through CANVAS.

<ol>
<li>Derive the full-conditional distribution for [σ2|y, μ] associated with the Normal- Normal-Inverseχ2 model. You will need this for Gibbs sampling.
yi ∼ N(μ,σ2) ,i = 1,…,n , μ ∼ N(μ0,σ02) ,

2−ν /2

σ2 ∼ Inverseχ2(ν) = Γ(ν/2)(σ2)−(ν/2+1) exp(−1/(2σ2)) .
</li>
<li>Construct and use an MCMC algorithm to fit Normal-Normal-Inverseχ2 model to the differences between QB and WR spending to answer the question de- scribed in the “Data” section above. Briefly describe the procedure and include the R code as an appendix. Concisely describe the model, including prior speci- fications, the algorithm, the results (including the number of MCMC iterations, visual inspection of trace plot, burn-in period if necessary, and comment on mixing).</li>
<li>Provide a graphic displaying the marginal posterior distributions for μ and σ2 resulting from the model fit to the data. Report the posterior mean and 95% equal-tailed credible interval for both μ and σ2 in a table.</li>
<li>Use the MCMC output to calculate the posterior probability that the mean difference between QB and WR spending is greater than zero. What can you infer as a result of this analysis?</li>
</ol>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
5. Would it have been more or less appropriate to obtain our desired inference by fitting the same model to the spending data from each position separately and then comparing the resulting posterior distributions for μ to infer a difference? Why?

References

<pre>https://www.spotrac.com/nfl/positional/breakdown/
</pre>
</div>
</div>
</div>
