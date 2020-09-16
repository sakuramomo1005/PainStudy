# PainStudy
Pain study


### Missing data mechanism

* Missing at Random (MAR): Missing at random means that the propensity for a data point to be missing is not related to the missing data, but it is related to some of the observed data

* Missing Completely at Random (MCAR): The fact that a certain value is missing has nothing to do with its hypothetical value and with the values of other variables.

* Missing not at Random (MNAR): Two possible reasons are that the missing value depends on the hypothetical value (e.g. People with high salaries generally do not want to reveal their incomes in surveys) or missing value is dependent on some other variable’s value (e.g. Let’s assume that females generally don’t want to reveal their ages! Here the missing value in age variable is impacted by gender variable)



### Estimands and missing data in clinical trials of chronic pain treatments: advances in design and analysis
Xueya Cai et. al

require strong and untestable
assumptions

Control-based imputation,

weighted
generalized estimating equations

In clinical trials of treatments for chronic pain, the percentage of participants who withdraw early can be as high as 50%. Major
reasons for early withdrawal in these studies include perceived lack of efficacy and adverse events. Commonly used strategies for
accommodating missing data include last observation carried forward, baseline observation carried forward, and more principled
methods such as mixed-model repeated-measures and multiple imputation.


### Estimands in a Chronic Pain Trial: Challenges and Opportunities
Francesca Callegari et. all

primary estimand and estimation method 

Primary variable: defined as the weekly mean of 24-hr
average pain score change from baseline to the end of the
double-blind treatment period and assessed using the 11-
point numerical rating scale. The 24-hr average pain is
recorded daily by each patient on a scale from zero (“no
pain”) to 10 (“pain as bad as you can imagine”). The weekly
mean is obtained by averaging the seven daily measurements
of each week.

Summary measure: defined as treatment difference of
variable means of the study drug and placebo

The primary estimation method (related to the primary estimand)
will be based on an analysis of covariance (ANCOVA)
model including region, treatment, gender, use of concomitant
pain medication at baseline as factors and baseline age and baseline
mean pain intensity score as covariates

missing data will
be imputed via multiple imputation using the missing at
random (MAR) assumption.

### Demonstrating Heterogeneity of Treatment Effects Among Patients: An Overlooked but Important Step Toward Precision Medicine
Jennifer S. Gewandter et. al.

* 4 RCTs with crossover
* Mixed effect models are fitted. with patient and treatment-by-patient as random effects 
* Likelihood ratio test: LME with or without treatment-by-patient effect
* The  treatment-by-patient effect is significant within the RCTs
* Precision medicine is needed

A mixed-effects
model, including
fixed effects for treatment and episode and random effects for 
interaction, was
used to assess the heterogeneity in patients’ responses to treatment during each episode

all.1,2 In response to these assumptions,
which are largely unproven, substantial investments have
been made to advance “precision medicine,” that is, strategies
to identify patients who would have a greater response to (or
less harm from) treatment using either genotyping or phenotyping.
Th

### Are there really only 2 kinds of people in the world? Evaluating the distribution of change from baseline in pain clinical trials 
Omar B. Mbowe et. al.


### Model misspecification: finite mixture or homogeneous?

