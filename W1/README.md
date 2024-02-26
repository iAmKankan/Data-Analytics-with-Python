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
* Formula is $\large{\color{Purple}\textit{Weighted Average} = \dfrac{\sum wx}{\sum w}}$

Sometimes if you look at the previous values, the each value is given equal weightage. Suppose it is not always the case there may be some marks there some values where there may be higher weightage. So for that case we have to go for weighted average. Some time you see this we will list two average numbers but we want to assign more importance or weight to some of the numbers. The average you need is the weighted average  
