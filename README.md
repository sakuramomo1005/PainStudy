# PainStudy


#### Goal: 

* Hypothesis test: Test medication effects (mean effect among population)
* Precision medicine: Make personalized treatment decision rule

#### Features: 

Similar as mental health studies

* Longitudinal (trajectory)
* Heterogeneity 
* Drop-off



## Estimands in a Chronic Pain Trial: Challenges and Opportunities
***Francesca Callegari et. all***

Discussed about the primary estimand and estimation method 

Primary variable: 

* Assessed using the 11-point numerical rating scale (0 to 10).
* Weekly mean, calculated by averaging the seven daily measurements of each week.
* Record from baseline to the end of the treatment period

Summary measure: 

* Defined as treatment difference of variable means of the study drug and placebo

Primary estimation method: 

* Analysis of covariance (ANCOVA) model including region, treatment, gender, use of concomitant pain medication at baseline as factors and baseline age and baseline mean pain intensity score as covariates

* Missing data will be imputed via multiple imputation using the missing at random (MAR) assumption.


## Estimands and missing data in clinical trials of chronic pain treatments: advances in design and analysis
Xueya Cai et. al

In clinical trials of treatments for chronic pain, the percentage of participants who withdraw early can be as high as 50%

Categories of dropout reasons: 

* adverse event (AE)
* lack of compliance
* lack of efficacy
* loss to follow-up
* withdrawal of consent, and other.

Methods to handle missing data require strong and untestable assumptions, e.g. MCAR or MAR. 

### Missing data mechanism

* Missing Completely at Random (MCAR): Missingness is unrelated to the data and is ignorable

* Missing at Random (MAR): Missingness is related to some observed variables

* Missing not at Random (MNAR): Missingness is related to some unobserved variables

```diff
+ Assumption for chronic pain study
```

* Jump to reference (J2R): Outcomes after dropout immediately switch to be like those from subjects in the placebo group 
* Copy reference: the outcomes after dropout gradually switch to be like those from subjects in the placebo group


### Missing data handling methods in chronic pain studies

| Method | Assumption | Pros | Cons|
| --- | --- | --- |--- |
|Complete case (CC) |  MCAR | | |
|Last observation carried forward (LOCF)| Measurement remains at the same level | |
|Baseline observation carried forward (BOCF)|Measurement remains at the same level | | 
|Mixed-model repeated-measures (MMRM) | MAR | | |
|Multiple imputation (MI)| MAR |  | |
|Weighted generalized estimating equations| MAR | | |
|Trimmed means|Treat drop-offs as bad outcomes | | | 


The method called control-based imputation might be suitable for chronic pain analysis, since it allows a variety of assumptions to be made concerning the conditional distribution outcomes. 


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




## Thoughts 

Do not have trajectory information 

d
