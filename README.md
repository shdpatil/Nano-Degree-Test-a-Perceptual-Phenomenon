

# Test-a-Perceptual-Phenomenon
Applied statistical approach to analyze the data given by an experiment called Stroop's Effect
In this project, I investigated a classic phenomenon from experimental psychology called the Stroop Effect.
I learnt a little bit about the experiment, created a hypothesis regarding the outcome of the task, then went through the task myself. 
Then I look at some data collected from others who have performed the same task and computed some statistics describing the results. 
Finally, I interpreted the results in terms of your hypotheses.


###Details about the Stroop's  Effect experiment and how I proceeded:

The Dependent variable is the time taken to name the ink color. And the the independent variable is, the two different conditions. 
For example, whether the color and word is congruent or incongruent is independent with other conditions.

Now analysing the hypothesis : Null Hypothesis(H0) H0 : (myu sub c) X = (myu sub ic)Y, Y - X = 0, Alternative Hypothesis(H1) H1 : X < Y,
where X is average for the congruent variable and Y is average for incongruent variable.

We will perform dependent t-test for paired samples, because as the sample is not changing only the reading time is changing with the
two conditions, congruent and incongruent.

We will perform a two tailed t-test for hypothesis testing for alpha level 0.05. The null hypothesis is H0 which means there will no 
difference in the reading times for the congruent and incongruent conditions.
For alternative hypothesis H1 we can assume that there will be difference in positive direction, that is the average time taken for 
incongruent condition will be more than the congruent one.

A z-score and a t-score are both used in hypothesis testing. The reason for using T-score is that we have a sample size below 30, 
and an unknown population standard deviation. If the sample size is more than 30 and standard deviation is known then we can use a z-score.

The only difference between a z-test and a t-test is that for a z-test you have the exact standard error (calculated from the population 
standard deviation, σ) whereas for a t-test you have an estimate of the standard error (calculated from the sample standard deviation, s).
