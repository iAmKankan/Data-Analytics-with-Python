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

$$\Large{\color{Purple} \begin{matrix*}[l]
\mu &=& \dfrac{\sum f M}{\sum f}\\
 &=& \dfrac{\sum f M}{N}\\
 &=& \dfrac{f_1 M_1+f_2 M_2+f_3M_3+\cdots+f_iM_i}{f_1 +f_2+f_3+\cdots+f_i}\\
\end{matrix*}}$$

The mean of your grouped data is nothing but weighted average of class midpoints, class frequencies are the weight. For the formula is $\large{\color{Purple}\mu = \dfrac{\sum f M}{\sum f}}$

### Example of Group Data Calculation:

<p align="center">
 <img src="https://github.com/iAmKankan/Data-Analytics-with-Python/assets/12748752/de1520a3-cdc0-4a06-a531-cb5c96986f97" width=70%/>
</p>

$$\Large{\color{Purple}\mu = \dfrac{\sum f M}{\sum f} = \dfrac{2150}{50}=43.0 }$$
