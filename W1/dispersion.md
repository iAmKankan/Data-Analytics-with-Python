### Index:
### 🔲 $\large{\color{Purple}\underline{\textrm{Measures of Dispersion:}}}$
* **Measures of variability** describe the **spread** or the <ins><b>Dispersion</ins></b> of a set of data.
* Reliability of measure of <ins><b>Central Tendency</b></ins> is the <ins><b>Dispersion</ins></b>
* To compare dispersion of various samples

The **reliability** of measure of <ins><b>Central Tendency</b></ins> is the <ins><b>Dispersion</ins></b> because many times the <ins><b>Central Tendency</b></ins> will **mislead**. So the **reliability** of that <ins><b>Central Tendency</b></ins> is calculated by or identified by its **corresponding dispersion**.

It is used to compare **dispersion** of various samples that is why whenever you plot the data you not only show the **mean** you have to show the **central tendency** also because the **reliability of mean is explained by dispersion**.

#### Example
<p align="center">
 <img src="https://github.com/iAmKankan/Data-Analytics-with-Python/assets/12748752/8b871807-6584-4d67-a656-986ae20d5488" width=50%/>
  <br>
  <ins><b><i> Variability </i></b></ins> 
</p>

* The first **two rows** is no variability in cash flow **mean** is same.
* The second one is **variability in cash flow** see there is a lot of variability in the second one but the mean is same.
*  If you look at only the mean it look like same when you look at only the mean the mean value same but when you look at see the left hand side the second dataset is having more variability.
*  The quality of the mean is explained by its variability that is nothing but dispersion.

### $\large{\color{Purple}\underline{\textrm{Measures of Variability or Dispersion:}}}$

#### Common Measures of Variability
1. Range
2. Inter-quartile range
3. Mean Absolute Deviation
4. Variance
5. Standard Deviation
6. Z scores
7. Coefficient of Variation

### $\large{\color{Purple}1.\ \underline{\textrm{Range: Ungrouped Data}}}$  
* The **difference** between the **largest** and the **smallest values** in a set of data.
* Simple to compute
* Ignores all data points except the two extremes
* Example:  $\large{\color{Purple}Range = (Largest - Smallest) = (48 - 35) = 13}$

<div align="center">
 <b> 
   
| | | | |
|:---:|:---:|:---:|:---:|
|35   |41  | 44 |45|
| 37|41|44|46|
|37|43|44|46|
|39|43|44|46|
|40|43|44|46|
|40|43|45|48|
| | | | |

 </b>
</div>

Suppose there is ungroup of data is there see this one you have to find out the range. The range is nothing but the difference between the largest and the smallest value in a set of data. It is very simple to compute. The problem here is it ignores all data points except the two extremes. So the range is the largest value is 48 in this data set the smallest value is 35. 48- 35 = 13 you see that only the two values are taken care in between the values is not taken into consideration for finding the range.

### $\large{\color{Purple}2.\ \underline{\textrm{Quartile:}}}$  
* <ins><b>Measures of central tendency</ins></b> that **divide a group of data** into <ins><b>four subgroups</ins></b>.
* <b>Q<sub>1</sub>: <ins>25%</ins></b> of the data set is **below the first quartile**.
* <b>Q<sub>2</sub>: <ins>50%</ins></b> of the data set is **below the second quartile**.
* <b>Q<sub>3</sub>: <ins>75%</ins></b> of the data set is **below the third quartile**.
* <b>Q<sub>1</sub></b> is to the <ins><b>25<sup>th</sup> percentile</ins></b>.
* <b>Q<sub>2</sub></b> is located at <ins><b>50<sup>th</sup> percentile</ins></b> and <ins><b>equals to the median</ins></b>.
* <b>Q<sub>3</sub></b> is equal to the <ins><b>75<sup>th</sup> percentile</ins></b>
* <ins><b>Quartile values</ins></b> are not necessarily members of the dataset.


<p align="center">
 <img src="https://github.com/iAmKankan/Data-Analytics-with-Python/assets/12748752/45807d12-85ee-4794-ab16-be04ab0dc220" width=40%/>
  <br>
  <ins><b><i> Quartiles and its positions </i></b></ins> 
</p>

#### Example:
 $\large{\color{Purple}\textrm{Ordered array: } 106, 109, 114, 116, 121, 122, 125, 129 }$
 
 * $\large{\color{Purple}Q_1: \hspace{55pt} i^{th} = \dfrac{25}{100} \times (8) = 2 \hspace{25pt}  Q_{1} = \dfrac{109 + 114}{2} = 111.5}$
 * $\large{\color{Purple}Q_1: \hspace{55pt} i^{th} = \dfrac{50}{100} \times (8) = 4 \hspace{25pt}  Q_{2} = \dfrac{116 + 121}{2} = 118.5}$
 * $\large{\color{Purple}Q_1: \hspace{55pt} i^{th} = \dfrac{75}{100} \times (8) = 6 \hspace{25pt}  Q_{3} = \dfrac{122 + 125}{2} = 123.5}$

We have arranged the data in the **ascending order**. First we got to find out the <b>Q<sub> 1</sub></b>
* <b>Q<sub> 1</sub></b> as we know it is the <b>25<sup>th</sup> percentile</b> , So, lets findout the location of the <b>25<sup>th</sup> percentile</b>.
   * First you have to find out the location index **i** for that $\large{\color{Purple}i = \dfrac{25}{100} \times (8) = 2}$ . Since the 2 is the even number, we have to find out <ins><b>that position plus the next position and its average</ins></b>. <b>2<sup>nd</sup></b> = **109**, <b>3<sup>rd</sup></b> = **114**
   * So, $\large{\color{Purple}Q_{1} = \dfrac{109 + 114}{2} = 111.5}$

 * <b>Q<sub> 2</sub></b> as we know it is the <b>50<sup>th</sum> percentile</b> , So, lets findout the location of the <b>50<sup>th</sum> percentile</b>.
   * First you have to find out the location index **i** for that $\large{\color{Purple}i = \dfrac{50}{100} \times (8) = 4}$ . Since the 4 is the even number, we have to find out <ins><b>that position plus the next position and its average</ins></b>. <b>4<sup>th</sup></b> = **116**, <b>5<sup>th</sup></b> = **121**
   * So, $\large{\color{Purple}Q_{2} = \dfrac{116 + 121}{2} = 118.5}$

 * <b>Q<sub> 3</sub></b> as we know it is the <b>75<sup>th</sum> percentile</b> , So, lets findout the location of the <b>75<sup>th</sum> percentile</b>.
   * First you have to find out the location index **i** for that $\large{\color{Purple}i = \dfrac{75}{100} \times (8) = 6}$ . Since the 6 is the even number, we have to find out <ins><b>that position plus the next position and its average</ins></b>. <b>6<sup>th</sup></b> = **122**, <b>7<sup>th</sup></b> = **125**
   * So, $\large{\color{Purple}Q_{3} = \dfrac{122 + 125}{2} = 123.5}$

### $\large{\color{Purple}2.1. \ \underline{\textrm{Inter-Quartile range:}}}$  
* Range of values between the **first quartile** and **third quartile**
* Range of the "**middle half**"
* Less influenced by **extremes**
$$\Large{\color{Purple}\textit{Inter-Quartile range} = Q_3 - Q_1}$$
* As we know  <b>Q<sub> 3</sub></b> is <b>75<sup>th</sup> percentile</b>  <b>Q<sub>1</sub></b> is the <b>25<sup>th</sup> percentile</b> so range of values between the **first and third quartile** is called <ins><b>interquartile range</ins></b>.
* It is a range of middle of the data set.
* Why we are using quartile range because it is the less influenced by the **extreme values**.
* Because when we collect the data set we are not going to consider at very low values at the same time very high values. So the middle values which is not affected by extremes that is taken for further calculation .For that purpose we are using **interquartile range**.

### $\large{\color{Purple}3.\ \underline{\textrm{Deviation from the mean:}}}$  
### $\large{\color{Purple}\textrm{Example:}}$
* $\large{\color{Purple}\textrm{Given dataset: } 5,9,16,17,18 }$
* Let's findout the Mean $\large{\color{Purple}\mu = \dfrac{\sum X}{N}= \dfrac{65}{5}=13}$
*  $\large{\color{Purple}\textrm{Deviation from the mean: } \dfrac{\sum X - \mu}{N}}$
* $\large{\color{Purple}\textrm{Results: } \[-8,-4,3,4,5 \]}$

#### Explanetion:
<b><ins>First</ins></b>: findout the mean from the dataset. which is **13**.

<p align="center">
 <img src="https://github.com/iAmKankan/Data-Analytics-with-Python/assets/12748752/c22acb95-acd3-497a-8d23-9189f61a74da" width=50%/>
  <br>
  <ins><b><i> </i></b></ins> 
</p>

<b><ins>Next</ins></b>: Subtract the mean from each and every elements of the dataset.
   *  $\large{\color{Purple}(5-13)=-8}$ (negative deviation)
   *  $\large{\color{Purple}(9-13)=-4}$    
   *  $\large{\color{Purple}(16-13)=3}$  (positive deviation)
   *  $\large{\color{Purple}(17-13)=4}$     
   *  $\large{\color{Purple}(18-13)=5}$    

<b><ins>Finally</ins></b>: We got $\large{\color{Purple}\[ -8,-4,3,4,5 \] =0}$

Suppose if we want to add the deviations in general it will become **0**. That is why we should go for **mean absolute deviation**.

### $\large{\color{Purple}3.1.\ \underline{\textrm{Mean Absolute Deviation:}}}$  

<div align="center">
 
|$\large{\color{Purple}X}$| $\large{\color{Purple}X - \mu}$ | $\large{\color{Purple} \mid X - \mu \mid }$|
|:----:|:----:|:---:|
|5|-8|+8|
|9|-4|+4|
|16|+3|+3|
|17|+4|+4|
|18|+5|+5|
| | $\large{\color{Blue}0}$| $\large{\color{Blue}24}$|

</div>

$$\Large{\color{Purple}\begin{matrix*}[c]
M.A.D &=& \dfrac{\sum \mid X - \mu \mid}{N}\\
 &=& \dfrac{24}{5}\\
  &=& 4.8\\
\end{matrix*}}$$

### $\large{\color{Purple}4\ \underline{\textrm{Population Variance:}}}$  
There was a problem in the **mean absolute deviation**.

<div align="center">
 
|$\large{\color{Purple}X}$| $\large{\color{Purple}X - \mu}$ | $\large{\color{Purple}(X - \mu )^2 }$|
|:----:|:----:|:---:|
|5|-8|+8|
|9|-4|+4|
|16|+3|+3|
|17|+4|+4|
|18|+5|+5|
| | $\large{\color{Blue}0}$| $\large{\color{Blue}130}$|

</div>

$$\Large{\color{Purple}\begin{matrix*}[c]
\sigma^2 &=& \dfrac{\sum ( X - \mu )^2}{N}\\
 &=& \dfrac{130}{5}\\
  &=& 26.0\\
\end{matrix*}}$$

<ins><b>Population Variance:</ins></b> It is the average of the **squared deviation** from the **arithmetic mean**. 
* We have used the **Mean Absolute Deviation** to avoid the result becoming zero **0** by the presents of negetive values in the diviations list.
* Now we are going to square it, the squaring of the deviation having some advantage.
  * **One advantage** is we can remove the **negative sign**,
  * **second one** is the deviation is less when you square it. **For example:** **- 4** square is **16**, **- 8** square is **64**. So, more deviation gives more squared value. (<ins><b>It is giving higher penalty for higher deviation values</ins></b>)

### $\large{\color{Purple}5.\ \underline{\textrm{Population Standerd Deviation:}}}$  
* Square root of the Variance.
  
<div align="center">
 
|$\large{\color{Purple}X}$| $\large{\color{Purple}X - \mu}$ | $\large{\color{Purple}(X - \mu )^2 }$|
|:----:|:----:|:---:|
|5|-8|+8|
|9|-4|+4|
|16|+3|+3|
|17|+4|+4|
|18|+5|+5|
| | $\large{\color{Blue}0}$| $\large{\color{Blue}130}$|

</div>

$$\Large{\color{Purple}\begin{matrix*}[c]
\sigma^2 &=& \dfrac{\sum ( X - \mu )^2}{N}\\
 &=& \dfrac{130}{5}\\
\sigma^2  &=& 26.0\\
\sigma   &=& \sqrt{\sigma^2} \ \ or\ \ \sqrt{26.0} \\
\sigma   &=& 5.1\\
\end{matrix*}}$$

#### Why ?
<ins><b>Variance</ins></b> is a **squared number** that we **cannot compare**. Suppose the two numbers are given say 12 and 13 that is easy intuitively we can say which is higher which is smaller. Suppose 124, 169 is given notice they are squared numbers. We cannot compare intuitively and not only that it is in the **square root** of **squared term**. 

We want to have it in the actual term so for comparison purpose for that purpose we are taking square root of that.


### $\large{\color{Purple}6. \ \underline{\textrm{Sample Variance:}}}$  

<div align="center">
 
|$\large{\color{Purple}X}$| $\large{\color{Purple}X - \bar{X}}$ | $\large{\color{Purple}(X - \bar{X} )^2 }$|
|:----:|:----:|:---:|
|2398|625|390625|
|1844|71|5041|
|1539|-234|54756|
|1311|-462|213444|
|$\large{\color{Blue} 7,092}$| $\large{\color{Blue}0}$| $\large{\color{Blue}633,866}$|

</div>

$$\Large{\color{Purple}\begin{matrix*}[c]
S^2 &=& \dfrac{\sum ( X - \bar{X} )^2}{n-1}\\
 &=& \dfrac{633,866}{3}\\
  &=& 221,288.67\\
\end{matrix*}}$$

* Why we are dividing by **n -1**? the reason is that to make the **variance** as the **unbiased** estimator. This is due to **degrees of freedom**, since we already know the value of the mean will last one **degrees of freedom**.
* That we are dividing by **n – 1** so it is very important whenever you find the sample variance so the in the denominator there should be a **n-1**.
* So here the variance is **221,288.67**.

### $\large{\color{Purple}7. \ \underline{\textrm{Sample Standerd Deviation:}}}$  

<div align="center">
 
|$\large{\color{Purple}X}$| $\large{\color{Purple}X - \bar{X}}$ | $\large{\color{Purple}(X - \bar{X} )^2 }$|
|:----:|:----:|:---:|
|2398|625|390625|
|1844|71|5041|
|1539|-234|54756|
|1311|-462|213444|
|$\large{\color{Blue} 7,092}$| $\large{\color{Blue}0}$| $\large{\color{Blue}633,866}$|

</div>

$$\Large{\color{Purple}\begin{matrix*}[c]
S^2 &=& \dfrac{\sum ( X - \bar{X} )^2}{n-1}\\
 &=& \dfrac{633,866}{3}\\
S^2 &=& 221,288.67\\
S &=& \sqrt{S^2}\\
S &=& \sqrt{221,288.67}\\
&=& 470.41
\end{matrix*}}$$

* So, a **square root** of the **variance** is nothing but **standard deviation**.
 
### 🔲 $\large{\color{Brown} \underline{\textrm{Uses of Standard Deviation:}}}$  
* Indicator of financial risk
* Quality Control
  * construction of quality control charts
  * process capability studies
* Comparing populations
  * household incomes in two cities
  * employee absenteeism at two plants
    
**Standard Deviation** is giving an indicator of <ins><b>financial risk</ins></b>. **Higher the standard deviation** is **more risk**, **lesser the standard deviation** is **less at risk**.

In quality control context generally when we manufacture something suppose here **plant A** and **plant B** or **shift A** and **shift B** <ins><b>whenever the variances in lesser then the quality of the product is high</ins></b>.

The **process capability** also they should have the <ins><b>lesser variance means in the process capabilities high</ins></b>. Then I suppose therefore comparing the populations household income of 2 cities, employee absenteeism in 2 plants for these purposes, it is for comparing the population that means 
* <ins><b>wherever there is a lesser standard deviation so that is having higher homogeneous data set</ins></b>.

### $\large{\color{Brown} \underline{\textrm{Standard Deviation as an Indicator of Financial Risk:}}}$  


<p align="center">
 <img src="https://github.com/iAmKankan/Data-Analytics-with-Python/assets/12748752/17bb257e-7457-4cb9-b716-25079e3d5bf1" width=50%/>
  <br>
  <ins><b><i> </i></b></ins> 
</p>

You see look at this one $\large{\color{Purple}\mu}$ and $\large{\color{Purple}\sigma}$, see this is a financial **security A** and **B**. See the return rate is 15, 15 it is both are giving equal return but look at this the σ standard deviation because in financial context it is, it is measured as the risk. So the first one is 3% second with 7% so the security B having a higher risk, so always we will go for where there is a lesser standard deviation because mean is same. We are the same time the risk all should be same. So far we have seen different central tendencies, different dispersions. In the coming class will use Python will take some sample data set. I will explain you how to find out central tendency and the dispersion of the given data set. Thank you very much.

### 🔲 $\large{\color{Purple}\underline{\textrm{Empirical Rule:}}}$  
The Empirical Rule says how much of the data lies within **one**, **two**, **three** <ins><b>standerd deviation of the mean</ins></b>(for approx normal distribution).

The **empirical rule**, also sometimes called the <ins><b>three-sigma</ins></b> or <ins><b>68-95-99.7</ins></b> rule, is a **statistical rule** which states that for normally distributed data, almost all observed data will fall within three standard deviations (denoted by the Greek letter **sigma**, or $\large{\color{Purple}\sigma}$ ) of the mean or average (represented by the Greek letter **mu**, or $\large{\color{Purple}\mu}$ ) of the data.


<p align="center">
 <img src="https://github.com/iAmKankan/Data-Analytics-with-Python/assets/12748752/9c24ccbf-9e31-49f2-b6f5-8fa3d3a1685f" width=90%/>
 <br>
 <ins><b><i>Empirical Rule for the dataset with Bell shaped curves</i></b></ins>
</p>

The <ins><b>Normal Distribution</ins></b> is the father of all the distributions if you have any doubt on the **nature of the distributions** or if you are not really sure about what distribution the data follow  you can assume <ins><b>Normal Distribution</ins></b>. 

But there is a **limitation** of this **Empirical Rule**. It is applicable only for the **Bell shaped curves**. There may be a situation, the actual phenomena need not follow bell shaped curve. At that time this formula that is the **empirical rule will not work**. So we will go to another rule-

#### Data are normally distributed ( or approximately Normal)

<div align="center">

|Distance From the <br> Mean | Percentage of Values <br>falling within Distance|
|:---:|:---:|
|$\Large{\color{Purple} \mu \pm 1 \sigma}$| 68%|
|$\Large{\color{Purple} \mu \pm 2 \sigma}$| 95%|
|$\Large{\color{Purple} \mu \pm 3 \sigma}$| 99.7%|

 </div>

Actually this **1, 2, 3** is nothing but **Z**


### 🔲 $\large{\color{Purple} \underline{\textrm{Chebysheff’s Theorem:}}}$  
The previously we have seen that the properties of normal distribution, that is a **bell shaped curve**. Sometimes certain phenomenon need not follow the **bell shaped curve**. That time, you cannot use that property of Empirical Rule; you had to go for another formula for to find out how much observations are covering under 1σ, 2 σ and 3 σ distance. This idea was given by Chebysheff’s.

* A more general interpretation of the **standard deviation** is derived from **Chebysheff's Theorem**, which applies to **all shapes of histograms** (**not just bell shaped**).
* The proportion of observations in any sample that lie within **k** standard deviations of the mean is at leas- 

$$\Large{\color{Purple}1 - \dfrac{1}{k^ 2} \ \ \ \  for \ \  k > 1}$$

* For k=2 (say), the theorem states that at least 3/4 of all observations lie within 2 standard deviations of the mean. This is a "lower bound" compared to Empirical Rule's approximation (95%)

 Suppose a phenomenon which is not following **normal distribution**. If you want to know the 2 σ distances, how much percentage of observation can be covered? So when you substitute here 1- (1/ k 2 )= 1-1/4 = 3/4. So, 3/4 means 75 %. So if you are travel 2 σ distance on the either side. For a distribution which is not following normal distribution. You can cover 75 % of all observations.

You see the previously; It is 95 %. So you see that that is a given. For k equal to 2, the theorem states that, at least 3/4th of all observations lie within two standard deviation of the mean. This is lower bound compared to empirical rule approximation 95 %. In case the previous slide, if it is 2. We can cover 95% of all observations, but here we can cover only 75% of all observations. Sometime we can use Chebysheff’s theorem also; the data is not following normal distribution.

### 🔲 $\large{\color{Purple} \underline{\textrm{Coefficient of Variation:}}}$  
* Ratio of the standard deviation to the mean, expressed as a percentage
* Measurement of relative dispersion

$$\Large{\color{Purple}C.V = \dfrac{\sigma}{\mu}(100)}$$

It is the measurement of **relative dispersion**. Already there is a **standard deviation** is there. What is the purpose of this **coefficient of variations** that will see the next-

$$\Large{\color{Purple}\boxed{\begin{matrix*}[c]
\mu_1 &=& 29\\
 \sigma_1 &=& 4.6\\
C.V._1 &=& \dfrac{\sigma_1}{\mu_1}(100)\\
 &=& \dfrac{4.6}{29}(100)\\
 &=& 15.86\\
\end{matrix*} }
\hspace{35pt}
\boxed{
\begin{matrix*}[c]
\mu_2 &=& 84\\
 \sigma_2 &=& 10\\
C.V._2 &=& \dfrac{\sigma_1}{\mu_1}(100)\\
 &=& \dfrac{10}{84}(100)\\
 &=& 11.90\\
\end{matrix*}}}$$

* Look at the above, leftside- **stock A** or **stock 1** : right side **stock B** or **stock 2**.
* **Stock A**: $\large{\color{Purple}\mu_1 = 29}$, $\large{\color{Purple}\sigma_1 = 4.6}$.
* **Stock B**:  $\large{\color{Purple}\mu_2 = 84}$,  $\large{\color{Purple}\sigma_2 = 10}$
* Supposed to choose which is better. If you compare only the **mean**, 29 verses 84, the **stock 2** is better.
* Suppose if you compare the **standard deviation**, **4.6** and **10**- The lower the **standard deviation** better it is. So the **stock 1** is better.

 Now there is a **contradiction**, with respect to **mean** **Stock B** is **better**, with represent **standard deviation** **Stock A** is better. 
 
 Now there is a **contradiction** to need to have the **trade off**. 
 * In this situation we have to go for this **coefficient of variation**, <ins><b>Coefficient of Variation</ins> = &sigma; /  &mu;  </b>. For example:
 * For **stock A** case = <b>&sigma;<sub>1</sub> /  &mu;<sub>1</sub>  = (4.6 / 29)x 100 = 15.86</b>,
 * For **stock B** case = <b>&sigma;<sub>2</sub> /  &mu;<sub>2</sub>  = (10 /84 )x 100 = 11.90</b>.
 * **Lower** the <ins><b>Coefficient of Variation</ins></b>, but have the option is. So, if the Coefficient of variance is smaller that goup here **Stock B** has to be choosen.

### 🔲 $\large{\color{Purple}\underline{\textrm{Variance and Standerd Diviation of Grouped Data:}}}$  

$$\Large{\color{Purple}\boxed{\begin{matrix*}[c]
& {\color{Brown}\textrm{Population}} &\\
\hline\\
 \sigma^2 &=& \dfrac{\sum f \big\(  M-\mu \big\)^2}{N}\\
 \sigma &=& \sqrt{\sigma^2}\\
\end{matrix*} }
\hspace{35pt}
\boxed{
\begin{matrix*}[c]
& {\color{Brown}\textrm{Sample}} &\\
\hline\\
 S^2 &=& \dfrac{\sum f \big\(  M - \bar{X} \big\)^2}{n-1}\\
 S &=& \sqrt{S^2}\\
\end{matrix*}}}$$

#### For the Population
*  $\large{\color{Purple}f}$ is the **frequency**.
*  $\large{\color{Purple} M}$ is the **midpoint of that interval**.
*  $\large{\color{Purple}\mu}$ is the **mean of the interval**,
*  $\large{\color{Purple}N}$ is **sum of all frequencies**.

#### For the Sample
*  $\large{\color{Purple}f}$ is the **frequency**.
*  $\large{\color{Purple} M}$ is the **midpoint of that interval**.
*  $\large{\color{Purple}\bar{X}}$ is the **mean of the interval**,
*  $\large{\color{Purple}n}$ is **sum of all frequencies (n-1)**.

<p align="center">
 <img src="https://github.com/iAmKankan/Data-Analytics-with-Python/assets/12748752/d26c0784-a6ea-4f3f-8ad8-2d4d854080b8" width=80%/>
 <ins></ins><b></b><i></i>
</p>

$$\Large{\color{Purple}\begin{matrix*}[c]
 \sigma^2 &=& \dfrac{\sum f \big\(  M-\mu \big\)^2}{N}\\
 &=& \dfrac{7200}{50} = 144\\
 \sigma  &=& \sqrt{144}\\
     &=& 12\\
\end{matrix*} 
}$$

* So **144** is the **population variants** of this **grouped data**.
* If you want to know the **standard deviation** of this group of data, just to take the **square root** of the **variance**, that is **12**.

### 🔲 $\large{\color{Brown}\underline{\textrm{Measures of Shape:}}}$  

#### <ins><b>Skewness</ins></b>
* Absence of symmetry
* Extreme values in one side of a distribution
#### <ins><b>Kurtosis</ins></b>
Peakedness of a distribution
* <ins><b>Leptokurtic</ins></b>: high and thin
* <ins><b>Mesokurtic</ins></b>: normal shape
* <ins><b>Platykurtic</ins></b>: flat and spread out
#### <ins><b>Box and Whisker Plots</ins></b>
* Graphic display of a distribution
* Reveals skewness

This measure is for shape or distribution of a set of data. It allow us to see a set of data what distribution follows.

####  $\large{\color{Purple}\underline{\textrm{Skewness}}}$

<p align="center">
 <img src="https://github.com/iAmKankan/Data-Analytics-with-Python/assets/12748752/0500d150-5b39-424a-836a-c69874bacc76" width=60%/>
 <ins></ins><b></b><i></i>
</p>

Skewness is the **absence of symmetry**. It may be **left skewed data** or a **right skewed data** or a **symmetric data**. So the other one the application of skewness is to find out what is the nature of this shape- whether it is skewed or symmetric. 

####  $\large{\color{Purple}\underline{\textrm{Kurtosis}}}$

<p align="center">
 <img src="https://github.com/iAmKankan/Data-Analytics-with-Python/assets/12748752/c61738e0-2bbf-43f6-ad1a-b103eb7c2660" width=30%/>
 <br>
 <ins><b><i>Different Types of Kurtosis</i></b></ins> 
</p>

It is the <ins><b>peakedness of a distribution</b></ins> . There are three layers- <ins><b>Leptokurtic</b></ins> , <ins><b>Mesokurtic</b></ins> , <ins><b>Platykurtic</b></ins> . 
* <ins><b>Leptokurtic</b></ins> means high and thin
* <ins><b>Mesokurtic</b></ins> is little flat in this way and
*  <ins><b>Platykurtic</b></ins> very very flat this way flat and spread out.

####  $\large{\color{Purple}\underline{\textrm{Box and Whisker Plots}}}$
It is a graphical display of distribution. It reveals skewness. The application of boxer whisker plot is to check whether the data, follow a symmetry or what is the nature of the skewness of the distribution.

### 🔲 $\large{\color{Brown}\underline{\textrm{Skewness:}}}$  

<p align="center">
 <img src="https://github.com/iAmKankan/Data-Analytics-with-Python/assets/12748752/3443543c-93d8-4876-a51f-983505e35e9e" width=30%/>
 <br>
 <ins><b><i>Different Types of Skewness</i></b></ins> 
</p>

* Look at the skewness left one which is in **orange**  it is the **negatively skewed**. As we know skewness is how it is named is looking at the **tail**- the **tail is on the left hand side** so it is a **left skewed** or **negatively skewed**.
* Come to the **blue** one, the **extreme right**. It is this **tail is on the right hand side**, so, it is a **right skewed** or **positively skewed**.
* The **middle** one there is **no skewness**, so it is **symmetric**.

#### Some more points on Skewness
The skewness of a distribution is measured by comparing the relative positions of the mean, median and mode.
* If the Distribution is **symmetrical**
  * **Mean** = **Median** = **Mode**
* If the Distribution is **skewed right**
  * **Median** lies between **mode** and **mean**, and **mode is less than mean**.
* If the Distribution is **skewed left**
  *  **Median** lies between **mode** and **mean** and **mode is greater than mean**.  

<p align="center">
 <img src="https://github.com/iAmKankan/Data-Analytics-with-Python/assets/12748752/97d803d4-8af7-4ca9-86bd-0934c845d010" width=40%/>
 <br>
 <ins><b><i>Different Types of Skewness</i></b></ins> 
</p>

### 🔲 $\large{\color{Brown}\underline{\textrm{Coefficient of Skewness:}}}$  

* Summary measure for skewness
  
$$\large{\color{Purple} S = \dfrac{3(\mu - M_d)}{\sigma}}$$

* If  **S < 0**, the distribution is <ins><b>negatively skewed<ins><b> (**skewed to the left**)
* If **S = 0**, the distribution is <ins><b>symmetric<ins><b> (**not skewed**)
* If **S > 0**, the distribution is <ins><b>positively skewed<ins><b> (**skewed to the right**)
