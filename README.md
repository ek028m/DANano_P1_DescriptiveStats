# Descriptive Statistics Computed & Statistical Testing Performed for Stroop Effect Dataset (based on a psychological phenomenon)
## Questions For Investigation
### 1. What is our independent variable? What is our dependent variable?
Independent variable – the condition of the word (congruent, incongruent)

Dependent variable – the amount of time it takes to say out loud the color of the ink of the word displayed

### 2. What is an appropriate set of hypotheses for this task? What kind of statistical test do you expect to perform? Justify your choices. 
Since this test uses dependent samples and clearly has two conditions – congruent words and incongruent words – an appropriate statistical test would be to use the t-test statistic.  

Hypotheses –

The null hypothesis is where the population mean for the congruent condition equals the population mean for the incongruent condition.  The alternative hypothesis is where the population mean for the congruent condition does not equals the population mean for the incongruent condition.

H0: µC = µI

Ha: µC ≠ µI

Where C represents congruent words condition and I represents incongruent words condition.

I would like to perform a two-tailed t-test for dependent samples since there are two conditions being measure here. Assuming that this fits a t distribution.  Also assuming the alpha value is .05.

### 3. Report some descriptive statistics regarding this dataset. Include at least one measure of central tendency and at least one measure of variability.

###### Measure of Central Tendency – 
- For congruent condition, the mean of the data is 14.05
- For incongruent condition, the mean of the data is 22.02

Other measures of central tendency include mode and median.  The mean was calculated by taking the average time in took each participant to record a time for saying aloud the color of the ink in which the word is printed.

###### Measure of Variability – 
1. The Sample Standard Deviation for the congruent condition sample is 3.560.

2. The Sample Standard Deviation for the incongruent condition sample is 4.797.

The formula used for this calculation is sqrt(∑(Xi – Xbar)2 / (n-1)).  Where Xi represents the sample value of each participant’s ability to say out loud the color of the ink for each condition, Xbar represents the sample average of those sample values.  

### 4. Provide one or two visualizations that show the distribution of the sample data. Write one or two sentences noting what you observe about the plot or plots.

The shape of the data follows that of a t distribution curve.

### 5. Now, perform the statistical test and report your results. What is your confidence level and your critical statistic value? Do you reject the null hypothesis or fail to reject it? Come to a conclusion in terms of the experiment task. Did the results match up with your expectations?

Assuming that we have α = .05,

Confidence Interval: (-10.02, 32.04)

t-critical values: ±2.069

Since the t-value is -8.02, we reject the null hypothesis since it’s outside the critical region.  Yes, the results match with my expectations since it would seem advantageous in terms of saying the color of the ink out loud when the work is congruent with its color (as proved by the Stroop Effect).


