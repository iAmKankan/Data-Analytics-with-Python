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
 
### 🔲 $\large{\color{Brown} \ \underline{\textrm{Uses of Standard Deviation:}}}$  
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

### $\large{\color{Brown} \ \underline{\textrm{Standard Deviation as an Indicator of Financial Risk:}}}$  


<p align="center">
 <img src="https://github.com/iAmKankan/Data-Analytics-with-Python/assets/12748752/17bb257e-7457-4cb9-b716-25079e3d5bf1" width=50%/>
  <br>
  <ins><b><i> </i></b></ins> 
</p>

You see look at this one $\large{\color{Purple}\mu}$ and $\large{\color{Purple}\sigma}$, see this is a financial **security A** and **B**. See the return rate is 15, 15 it is both are giving equal return but look at this the σ standard deviation because in financial context it is, it is measured as the risk. So the first one is 3% second with 7% so the security B having a higher risk, so always we will go for where there is a lesser standard deviation because mean is same. We are the same time the risk all should be same. So far we have seen different central tendencies, different dispersions. In the coming class will use Python will take some sample data set. I will explain you how to find out central tendency and the dispersion of the given data set. Thank you very much.

### 🔲 $\large{\color{Purple} \ \underline{\textrm{Empirical Rule:}}}$  
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


### 🔲 $\large{\color{Purple} \ \underline{\textrm{Chebysheff’s Theorem:}}}$  

* A more general interpretation of the **standard deviation** is derived from **Chebysheff's Theorem**, which applies to all shapes of histograms (**not just bell shaped**).
* The proportion of observations in any sample that lie within k standard deviations of the mean is at least:

$$\Large{\color{Purple}1 - \dfrac{1}{k^ 2} \ \ \ \  for \ \  k > 1}$$

* For k=2 (say), the theorem states that at least 3/4 of all observations lie within 2 standard deviations of the mean. This is a "lower bound" compared to Empirical Rule's approximation (95%)


