[<img alt="acosalens" width="300px" src="https://github.com/jindalvishal09/AWS/blob/main/Resources/other/Acosa_logo.png" />](https://acosalens.com)

# Basics

### ⚡ _Statistical analyses_
Statistical analyses are used to make generalizations about populations on the basis of the information in a sample. Thus, it is important to understand the distinction between a sample and a population:
1. **Sample** : A sample is the collection of units (e.g., people, animals, cities, feilds, whatever you study) that is actually measured or surveyed in a study.
2. **Population** : The population is the larger group of units from which the sample was selected,ideally using probability methods for the selection. A sample, which is a subset of the population, is used to estimate characteristics of the population.

Different notation is used for sample and population characteristics. For example, the mean of a sample x<sub>1</sub>,x<sub>2</sub>,.......,x<sub>n</sub> is usually denoted by x̄, whereas the mean of a population is typically denoted by the Greek letter μ . An alternative notation for a population mean is E(X), which is read as the "expected value of X."
A measure computed from sample data is called a **statistic**. A measure characterizing the population is called a **parameter**. For example, x̄ is a statistic for the sample while μ is a parameter of the population.

### ⚡ _Population Model for Simple Linear Regression_

**Again, you will never know the actual population regression model in practice.** If we always knew the quantities in population models, then there would be little need for the field of Statistics!
A regression equation describes how the mean value of a y-variable (also called the **response or dependent variable**) relates to specific values of the x-variable(s) (also called the **predictor(s) or independent variable(s)**) used to predict y. A regression model also incorporates a measure of uncertainty
or error. A general format for a regression model is:

**y = equation for mean + individual's deviation from mean**
	



### ⚡ _Basics of Regression Models_

Suppose that x<sub>1</sub>,x<sub>2</sub>,.......,x<sub>n</sub> are realizations of the random variable pairs (X<sub>1</sub>, Y<sub>1</sub>), (X<sub>2</sub>, Y<sub>2</sub>), ....... ,(X<sub>n</sub>, Y<sub>n</sub>). The simple linear regression equation is that the mean of Y is a straight-line function of x. 
This could be written as:

**E(Y<sub>i</sub>) = β<sub>0</sub> + β<sub>1</sub>x<sub>i</sub>**

where E(Y~i~) is used to represent the mean value (expected value) and the
subscript i denotes the (hypothetical) i<sup>th</sup> unit in the population. To be completely pedantic, the simple regression equation should actually be written as the mean of a conditional random variable:

**E(Y<sub>i</sub>|X<sub>i</sub> = x<sub>i</sub>) = β<sub>0</sub> + β<sub>1</sub>x<sub>i</sub>**

In other words, we fix the values of X~i~ and then proceed to observe the values
of Y<sub>i</sub>. The simple linear regression model for individuals in the larger population from which the sample has been taken is written as:
**y<sub>i</sub> = β<sub>0</sub> + β<sub>1</sub>x<sub>i</sub> + ε<sub>i</sub> where ε<sub>i</sub>is the error or deviation of y<sub>i</sub>from the line β<sub>0</sub> + β<sub>1</sub> x<sub>i</sub>.**






### ⚡ _References_

* [Handbook of REGRESSION METHODS by Derek S. Young] ([https://www.amazon.in/Handbook-Regression-Methods-Derek-Scott/dp/1498775292])
