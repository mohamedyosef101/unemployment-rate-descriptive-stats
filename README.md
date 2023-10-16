# What is Descriptive Statistics
Descriptive statistics are numbers that are used to describe and summarize the data. They are used to describe the basic features of the data under consideration. They provide simple summary measures which give an overview of the dataset. Summary measures that are commonly used to describe a data set are measures of central tendency and measures of variability or dispersion.

**Measures of central tendency** include the `mean`, `median` and `mode`. These measures summarize a given data set by providing a single data point. These measures describe the center position of a distribution for a data set. We analyze the frequency of each data point in the distribution and describes it using the mean, median or mode. They provide the average of a data set. They can be either a representation of entire population or a sample of the population.

**Measures of variability or dispersion** include the `variance` or `standard deviation`, `coefficient of variation`, `minimum` and `maximum` values, `IQR` (Interquartile Range), `skewness` and `kurtosis`. These measures help us to analyze how spread-out the distribution is for a dataset. So, they provide the shape of the data set.

# A quick guide on how to do descriptive statistics

## 0. The describe function
When using the describe function, there are two ways; categorical and numerical data. In case of numerical data, you'll get: 
- `count`: Number of non-NA/null observations
- `mean`: The arithmetic average
- `std`: The standard deviation
- `min`: The smallest (minimum) value
- `25%`: The first quartile (25th percentile)
- `50%`: The median (50th percentile)
- `75%`: The third quartile (75th percentile)
- `max`: The largest (maximum) value

But if you have categorical data, you'll see:
- `count`: Number of non-NA/null observations
- `unique`: Number of unique values
- `top`: The most common value (the mode)
- `freq`: The frequency of the most common value

## 1. Measures of central tendancy
**Central tendency** means a central value which describe a probability distribution. It may also be called a center or location of the distribution. The most common measures of central tendency are **mean**, **median** and **mode**. 
* The most common measure of central tendency is the mean. 
* For skewed distribution or when there is concern about outliers, the median may be preferred. *So, median is more robust measure than the mean.*

![measures of central tendancy](https://github.com/mohamedyosef101/unemployment-rate-descriptive-stats/assets/118842452/6b787b96-545b-4a7e-a599-13325aa87fa1)


## 2. Measures of variability
**Dispersion** is an indicator of how far away from the center, we can find the data values. The most common measures of dispersion are **variance**, **standard deviation** and **interquartile range (IQR)**. 
* Variance is the standard measure of spread. 
* The standard deviation is the square root of the variance.

![IQR](https://github.com/mohamedyosef101/unemployment-rate-descriptive-stats/assets/118842452/72ba4d79-26aa-45db-8627-75551f739694)


## 3. Measures of Shape
Now, we will take a look at measures of shape of distribution. There are two statistical measures that can tell us about the shape of the distribution. These measures are **skewness** and **kurtosis**. These measures can be used to convey information about the shape of the distribution of the dataset.

### Skewness
* **Skewness** is a measure of a distribution's symmetry or more precisely lack of symmetry.
* It is used to mean the absence of symmetry from the mean of the dataset.
* It is a characteristic of the deviation from the mean.
* It is used to indicate the shape of the distribution of data.

![skewness](https://github.com/mohamedyosef101/unemployment-rate-descriptive-stats/assets/118842452/de66eb99-4198-46f9-bf87-5bbc8ae9ffed)


#### Reference range on skewness values
The rule of thumb for skewness values are:
* If the skewness is between -0.5 and 0.5, the data are fairly symmetrical.
* If the skewness is between -1 and – 0.5 or between 0.5 and 1, the data are moderately skewed.
* If the skewness is less than -1 or greater than 1, the data are highly skewed.


### Kurtosis
* **Kurtosis** is the degree of peakedness of a distribution.
* Data sets with high kurtosis tend to have a distinct peak near the mean, decline rather rapidly and have heavy tails.
* Data sets with low kurtosis tend to have a flat top near the mean rather than a sharp peak.

![Kurtosis](https://github.com/mohamedyosef101/unemployment-rate-descriptive-stats/assets/118842452/29c670bd-f551-4529-924c-9f5a1accda53)


#### Reference range for kurtosis
* The reference standard is a normal distribution, which has a kurtosis of 3.
* Often, **excess kurtosis** is presented instead of kurtosis, where excess kurtosis is **simply** kurtosis - 3.

# Useful Resources
* Adam Hayes. (2023). [Descriptive Statistics: Definition, Overview, Types, Example](https://www.investopedia.com/terms/d/descriptive_statistics.asp#:~:text=Descriptive%20statistics%20are%20brief%20informational,measures%20of%20variability%20(spread).). Investopedia.

* Prashant Banerjee. (2019). [Descriptive Statistics with Python](https://gist.github.com/pb111/512c840affb32593d28573fbb764045b#file-descriptive-statistics-with-python-ipynb). GitHub Gist.

* Simranjeet Singh. (2023). [The Ultimate Guide to Statistics: Part 1 - Descriptive Statistics](https://pub.towardsai.net/complete-guide-to-statistics-descriptive-statistics-part-1-600a7783be0). Towards AI.


---
If you have any question, feel free to **[send me a message on LinkedIn](https://linkedin.com/in/mohamedyosef101)**.
