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

## $\large{\color{Purple}1.\ \underline{\textrm{Range: Ungrouped Data}}}$  
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

### $\large{\color{Purple}3.\ \underline{\textrm{Inter-Quartile range:}}}$  
* Range of values between the **first quartile** and **third quartile**
* Range of the "**middle half**"
* Less influenced by **extremes**

  $$\Large{\color{Purple}\textit{Inter-Quartile range} = Q_3 - Q_1}$$

* As we know  <b>Q<sub> 3</sub></b> is <b>75<sup>th</sup> percentile</b>  <b>Q<sub>1</sub></b> is the <b>25<sup>th</sup> percentile</b> so range of values between the **first and third quartile** is called <ins><b>interquartile range</ins></b>.
* It is a range of middle of the data set.
* Why we are using quartile range because it is the less influenced by the **extreme values**.
* Because when we collect the data set we are not going to consider at very low values at the same time very high values. So the middle values which is not affected by extremes that is taken for further calculation .For that purpose we are using **interquartile range**.
