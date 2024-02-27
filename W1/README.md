$\large{\color{blue} Note\ Books:}$
* [Python Tutorial 001](https://github.com/iAmKankan/Data-Analytics-with-Python/blob/main/W1/Python_Basics_NPTEL.ipynb)

### ⬛ $\Large{\color{blue}\underline{\mathcal{Central\ Tendency\ and\ Dispersion}}}$
### $\large{\color{Purple}\textrm{Objective:}}$
* $\large{\color{Purple}\textrm{Central Tendency}}$ or  $\large{\color{Purple}\textrm{measures of location }}$
* $\large{\color{Purple}\textrm{Measures of Dispersion}}$
### <ins><b><i>We are going to cover</i></b></ins>

<div align="center">
  
| $\large{\color{Brown}\underline{\textrm{Central tendency}}}$|  $\large{\color{Brown}\underline{\textrm{Measures of Dispersion}}}$|
|:-------------|:------------|
| $\large{\color{Purple}\textrm{Arithmetic mean}}$|$\large{\color{Purple}\textrm{Skewness}}$|
| $\large{\color{Purple}\textrm{Weighted mean}}$|$\large{\color{Purple}\textrm{Kurtosis}}$|
| $\large{\color{Purple}\textrm{Median}}$|$\large{\color{Purple}\textrm{Interquartile range}}$|
| $\large{\color{Purple}\textrm{Percentile}}$|$\large{\color{Purple}\textrm{Standard score}}$|
| |$\large{\color{Purple}\textrm{Range}}$|
||$\large{\color{Purple}\textrm{Variance}}$|
||$\large{\color{Purple}\textrm{Coefficient of variation}}$|
<br>

</div>

### 🔲 $\large{\color{Purple}\underline{\textrm{Measures of Central Tendency}}}$
* **Measure of central tendency** yield information about **particular places** or **locations** in a group of numbers.
* A **single number** to describe the **characteristics** of a set of data.

Measure of central tendency yield information about **particular places** or **locations** in a **group of numbers**. Suppose there are a group of number, that group of numbers has to be replaced by <ins><b>a single number</ins></b> that single number we can call it as central tendency. <ins><b>That is a single number to describe the characteristics of a set of data</ins></b>.


### $\large{\color{Purple}1. \underline{\textrm{Arithmetic mean}}}$

* Commonly called 'the mean'
* It is the average of a group of numbers
* Applicable for **interval** and **ratio data**
* Not applicable for **nominal** or **ordinal data**
* Affected by each value in the data set, including **extreme values**
* Computed by summing all values in the data set and dividing the sum by the number of values in the data set

One of the problem of the with the mean is that it is affected by the extreme values. 

### $\large{\color{Purple}\underline{\textrm{Population mean:}}\ \  \ \Large \mu}$
$\Large{\color{Purple} \mu}$ is used as a notation for <ins><b>Population mean</ins></b>.

$$\Large{\color{Purple} \begin{matrix*}[l]
\mu &=& \dfrac{\sum X}{N}\\
 &=& \dfrac{X_1+X_2+X_3+\cdots+X_N}{N}\\
 &=& \dfrac{24+ 13+ 19+ 26+ 11}{5}\\
 &=& \dfrac{94}{5}\\
  &=& 18.6\\
\end{matrix*}}$$

* **18.6** is the average of **24, 13, 19, 26, 11** these **5** numbers.
* So, now the **18.6** can be replaced by these set 5 numbers. Just like suppose, in your class if you see the average mark is **60**. So the whole marks of all the students can be represented to be a single number that is **60**, **60** will give an idea about the **performance of the whole class**.

### $\large{\color{Purple}\underline{\textrm{Sample mean:}}\ \  \ \Large \bar{X}}$
$\Large{\color{Purple} \bar{X}}$ is used as a notation for <ins><b>Sample mean</ins></b>.

$$\Large{\color{Purple} \begin{matrix*}[l]
 \bar{X} &=& \dfrac{\sum X}{n}\\
 &=& \dfrac{X_1+X_2+X_3+\cdots+X_n}{n}\\
 &=& \dfrac{57+ 86+ 42+ 38+ 90+66}{6}\\
 &=& \dfrac{379}{6}\\
  &=& 63.167\\
\end{matrix*}}$$

### $\large{\color{Purple}\underline{\textrm{Mean of Grouped data:}}}$
* Weighted average of class midpoints
* Class frequencies are the weight
* Formula is $\large{\color{Purple}\mu = \dfrac{\sum f M}{\sum f}}$


$$\Large{\color{Purple} \begin{matrix*}[l]
\mu &=& \dfrac{\sum f M}{\sum f}\\
 &=& \dfrac{\sum f M}{N}\\
 &=& \dfrac{f_1 M_1+f_2 M_2+f_3M_3+\cdots+f_iM_i}{f_1 +f_2+f_3+\cdots+f_i}\\
\end{matrix*}}$$

The mean of your grouped data is nothing but weighted average of class midpoints, class frequencies are the weight. 
### Example of Group Data Calculation:

<p align="center">
 <img src="https://github.com/iAmKankan/Data-Analytics-with-Python/assets/12748752/de1520a3-cdc0-4a06-a531-cb5c96986f97" width=70%/>
</p>

$$\Large{\color{Purple}\mu = \dfrac{\sum f M}{\sum f} = \dfrac{2150}{50}=43.0 }$$

See this is the grouped data. What is given class interval is given frequency is given class midpoint is given and multiplied value of frequency and midpoint also we can find out. 
For example, Suppose we are talking about the markes obtained by a class of students for a perticular subject.
* <ins><b>20 to under 30 :</ins></b> The frequency is 6, means 6 students get the score between 20 to less than 30.
* <ins><b>30 to under 40 :</ins></b> The frequency is 18, means 18 students get the score between 30 to less than 40.
* <ins><b>40 to under 50 :</ins></b> The frequency is 11, means 11 students get the score between 40 to less than 50.
* <ins><b>50 to under 60 :</ins></b> The frequency is 11, means 11 students get the score between 50 to less than 60.
* <ins><b>60 to under 70 :</ins></b> The frequency is 3, means 3 students get the score between 60 to less than 70.
* <ins><b>70 to under 80 :</ins></b> The frequency is 1, means 1 students get the score between 70 to less than 80.

Suppose for this the data is in this grouped format how to find out the **mean**?  First what do you have to do first you have to find out the class midpoint.
* <ins><b>20 to under 30 :</ins></b> that is a class interval, the midpoint is **25**
* <ins><b>30 to under 40 :</ins></b> that is a class interval, the midpoint is **35**
* <ins><b>40 to under 50 :</ins></b> that is a class interval, the midpoint is **45**
* <ins><b>50 to under 60 :</ins></b> that is a class interval, the midpoint is **55**
* <ins><b>60 to under 70 :</ins></b> that is a class interval, the midpoint is **65**
* <ins><b>70 to under 80 :</ins></b> that is a class interval, the midpoint is **75**
  
Next one you have two **multiplied by frequency and class midpoint** so $\large{\color{Purple}6 \times 25 = 150}$ , $\large{\color{Purple}18 \times 35 = 630}$ , $\large{\color{Purple}11 \times 45 = 495}$ and so on. 

What the formula says $\large{\color{Purple}\mu = \dfrac{\sum f M}{\sum f}}$ it is last column the sum value is 2150, 2150/50 Sigma f is some of the frequency so for this kind of grouped data the mean is 43.

### $\large{\color{Purple}2. \underline{\textrm{Weighted Average}}}$

* Sometimes we wish to average numbers, but we assign more importance or weight to some of the numbers.
* The average you need is weighted average.
* Formula is $\large{\color{Purple}\textit{Weighted Average} = \dfrac{\sum wx}{\sum w}}$; where **x** is a data value and **w** is the weight assigned to that data value. The sum is taken over all data values.

Sometimes if you look at the previous values, the each value is given equal weightage. Suppose it is not always the case there may be some marks there some values where there may be higher weightage. So for that case we have to go for weighted average. Some time you see this we will list two average numbers but we want to assign more importance or weight to some of the numbers. The average you need is the weighted average  

### Example
* Suppose your **midterm test** score is **83**, which is **40% weights** of total score for the final exam. 
* Your **final exam** score is **95**, which is **60% weights** of total score for the final exam
* If the **minimum average** for an **A** is $\large \geq$ **90**, will you earn an **A grade**?

$$\Large{\color{Purple} \begin{matrix*}[l]
\textrm{Weighted Average} &=& \dfrac{(83 \times 0.40)+(95 \times 0.60)}{0.40 + 0.60}\\
 &=& \dfrac{32+57}{1}\\
 &=& 90.2 = \textrm{Grade \' A\'}\\
\end{matrix*}}$$

### $\large{\color{Purple}3. \underline{\textrm{Median}}}$
* <ins><b>Middle value</ins></b> in an <ins><b>ordered array of numbers</ins></b>
* Applicable for <ins><b>ordinal</ins></b>, <ins><b>interval</ins></b>, and <ins><b>ratio data</ins></b>
* Not applicable for <ins><b>nominal data</ins></b>
* Unaffected by <ins><b>extremely large and extremely small values</ins></b>.


$\large{\color{Purple}\textrm{Ordinal data}:}$  Ordinal data is a **categorical**, **statistical** data type where the variables have **natural**, **ordered categories** and the **distances between the categories are not known**.
#### Example: 
An example of a Likert scale is
<div align="center">
  
|Like|	Like Somewhat|	Neutral	Dislike| Somewhat|	Dislike|
|:---:|:---:|:---:|:---:|:---:|
|1	|2	|3	|4	|5|
</div>

* For example, the survey question "Is your general health **poor**, **reasonable**, **good**, or **excellent**?" may have those answers coded respectively as **1**, **2**, **3** and **4**.
* Sometimes data on an **interval scale** or **ratio scale** are grouped onto an **ordinal scale**: for example: **individuals** whose **income** is known might be grouped into the **income categories** **$0–$19,999**, **$20,000–$39,999**, **$40,000–$59,999**, ..., which then might be coded as **1**, **2**, **3**, **4**.
* Other examples of **ordinal data** include **socioeconomic status**, **military ranks** and **letter grades** for **coursework**.

$\large{\color{Purple}\textrm{Interval scale}:}$ The interval type allows for defining the degree of difference between measurements, but not the ratio between measurements. Examples include temperature scales with the Celsius scale, which has two defined points (the freezing and boiling point of water at specific conditions) and then separated into 100 intervals, date when measured from an arbitrary epoch (such as AD), location in Cartesian coordinates, and direction measured in degrees from true or magnetic north.

$\large{\color{Purple}\textrm{Ratio scale}:}$ The ratio type takes its name from the fact that measurement is the estimation of the ratio between a magnitude of a continuous quantity and a unit of measurement of the same kind (Michell, 1997, 1999). Most measurement in the physical sciences and engineering is done on ratio scales. Examples include mass, length, duration, plane angle, energy and electric charge. In contrast to interval scales, ratios can be compared using division. Very informally, many ratio scales can be described as specifying "how much" of something (i.e. an amount or magnitude). Ratio scale is often used to express an order of magnitude such as for temperature in Orders of magnitude (temperature).

$\large{\color{Purple}\textrm{Nominal Data}:}$ In statistics, Nominal data is qualitative data that groups variables into categories that do not overlap. Nominal data is the simplest measure level and are considered the foundation of statistical analysis and all other mathematical sciences. They are individual pieces of information recorded and used for analysis. Nominal data cannot be ordered and cannot be measured. **Example of Nominal Data** – Which state do you live in? (Followed by a **drop-down list** of names of states)

### $\large{\color{Purple}\underline{\textrm{Median Computational Procedure:}}}$
#### <ins><b>First Procedure</ins></b>
* Arrange the observations in an ordered array
* If there is an odd number of terms, the median is the middle term of the ordered array
* If there is an even number of terms, the median is the average of the middle two terms

#### <ins><b>Second Procedure</ins></b>
* The median's position in an ordered array is given by (n + 1) / 2

### $\large{\color{Purple}\underline{\textrm{Example: Odd number of terms median}}}$

$\large{\color{Purple}\textrm{Ordered Array: } 3, 4, 5, 7, 8, 9, 11, 14, 15, 16, 16, 17, 19, 19, 20, 21, 22}$

* There are **17** terms in the ordered array.
* Position of **median = (n+1)/2 = (17+1)/2 = 9**
* The median is the <b>9<sup>th</sup></b> term which is **15**.
* If the **22** is replaced by **100**, the **median is 15**.
* If the **3** is replaced by **-103**, the median is **15**.

So there is the advantage of this median over mean is median is not disturbed by extreme values.

### $\large{\color{Purple}\underline{\textrm{Example: Even number of terms median}}}$

$\large{\color{Purple}\textrm{Ordered Array: } 3,4,5,7,8,9,11, 14, 15, 16, 16, 17, 19, 19, 20, 21}$

* There are **16** terms in the ordered array
* Position of **median= (n + 1) / 2 = (16 + 1) / 2 = 8.5**
* The median is between the <b>8<sup>th</sup></b> and <b>9<sup>th</sup></b> terms, **14.5**
* If the **21** is replaced by **100**, the median is **14.5**
* If the **3** is replaced by **-88**, the median is **14.5**

### $\large{\color{Purple}\underline{\textrm{Median of Gouped data:}}}$

$$\Large{\color{Purple}Median =L+ \dfrac{\dfrac{N}{2} - cf_{p} }{f_{ med}} (W)}$$

#### <ins>Where:</ins>
* $\large{\color{Purple}L}$ = the lower limit of the median class.
* $\large{\color{Purple}cf_{p}}$ = cumulative frequency of class preceding the median class.( previous class frequency)
* $\large{\color{Purple}f_{med}}$= frequency of the median class ($\large{\color{Purple}f \ \ median \ \ = f_{med}}$)
* $\large{\color{Purple}W}$ = width of the median class
* $\large{\color{Purple}N}$ = total of frequencies

### $\large{\color{Purple}\underline{\textrm{Example: Median of Gouped data:}}}$
<p align ="center">
  <img src="https://github.com/iAmKankan/Data-Analytics-with-Python/assets/12748752/fba414c6-3db8-4e94-9c46-67a2fa75924a" width=60%/>
  <br>
</p>

$$\Large{\color{Purple}\begin{matrix*}[l]
Median &=& L+ \dfrac{\dfrac{N}{2} - cf_{p} }{f_{ med}} (W)\\
 &=& 40+ \dfrac{\dfrac{50}{2} - 24 }{11} (10)\\
  &=& 40.909
\end{matrix*}}$$

* Before using this formula first you need to find out the **median class**.
* What is the median class is when you add the frequency **6 + 18 + 11 + 11 + 3 + 1 = 50**.
* So divide this **50 / 2** it is **25**.
* Now, in the **community frequency column** or in the **last column** look at where that **25** is lying? (it is not between 30 - 40) it is going to lie on between **40 to 50** because **24** for the next term is **35**.
* So the **median class** for **this given group data** is **40 and 50**.
* So as usual **L**, is the **lower limit of the median class** that is a **40** plus **N** is **50** .
* You see the **cumulative frequency of the preceding interval** is **24**.( previous class frequency)
*  So, **Md = 40+ ((50/2) – 24) x10 /11** because the **width interval** is **10**.
*  When you simplify you would get **40.909**.


### $\large{\color{Purple}4. \underline{\textrm{Mode:}}}$
* The most frequently occurring value in a data set
* Applicable to all levels of data measurement (**nominal**, **ordinal**, **interval** and **ratio**).
* **Bimodal** -- Data sets that have **two modes**.
* **Multimodal** -- Data sets that contain **more than two modes**.


### $\large{\color{Purple}\underline{\textrm{Example: Mode}}}$

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

* The Mode is 44.
* There are more 44s than any number.

### $\large{\color{Purple}\underline{\textrm{Example: Mode of Grouped Data}}}$
* Midpoint of the model class.
* Model class has the greatest frequency.

<p align ="center">
  <img src="https://github.com/iAmKankan/Data-Analytics-with-Python/assets/12748752/c67dc156-327a-4f5d-863e-69d8d5091d2f" width=45%/>
  <br>
</p>

$$\Large{\color{Purple}\begin{matrix*}[l]
Mode  &=& L_{Mo}+ \dfrac{d_1}{d_1+d_2} w\\
 &=& 30+ \dfrac{12}{12+7}10\\
  &=& 36.31
\end{matrix*}}$$

* Here first we have to find out the **mode class**. For that look at the frequency column there **18** is the **highest frequency**.
* So corresponding the **n** class interval is called **mode interval**.
* The mode interval $\large{\color{Purple}L_{Mo}}$ is the lower limit of that mode interval is = 30 + (12/(12+7))*10
* $\large{\color{Purple}d_1}$ is **present frequency** is **18** and the **previous frequency** is **6**, $\large{\color{Purple} (18 - 6 )= 12}$
* $\large{\color{Purple}d_2}$ is the difference between your **18** and **next frequency** **11**  that is $\large{\color{Purple} (18 - 11 )= 7}$.
* Your **width** is **10**,
* So **36.31** is the mode of your **grouped data**. 

### 🔲 $\large{\color{brown}\underline{\textrm{When to use Mean or Median or Mode?}}}$

<p align="center">
 <img src="https://github.com/iAmKankan/Data-Analytics-with-Python/assets/12748752/054051ed-646f-4266-92fe-e2f39b1afaa4" width=80%/>
</p>
