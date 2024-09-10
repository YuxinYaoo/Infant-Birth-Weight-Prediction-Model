# Infant-Birth-Weight-Prediction-Model
# Description

Build predictive models of a baby's birthweight from variables measured on the fetus before birth, on the mother and her pregnancy, and on the father and family characteristics. 

This dataset comes from the [Infant Health and Development Program](https://pubmed.ncbi.nlm.nih.gov/1371341), a collaborative, randomized, longitudinal, multisite clinical trial designed to evaluate the efficacy of comprehensive early intervention in reducing the developmental and health problems of low birth weight infants. An intensive intervention extending from hospital discharge to 36 months corrected age was administered at eight different sites. 

Enrolling participants in clinical trials takes time. If investigators could predict which babies would be born underweight, they could enroll mothers in the trial in advance of the birth so that the intervention could begin immediately upon hospital discharge. An accurate predictive model for prioritizing patients for enrollment was therefore desirable in this case; if the baby did not end up being born underweight, the participant could be unenrolled and compensated for their time. 

There are other more common applications for accurate predictive models of baby birthweight:

- *Clinical use*: For doctors to recommend specific treatment to either delay birth (and thus increase birthweight) or to prepare for a low birthweight delivery, i.e., triaging mothers to give birth in hospitals equipped to care for babies requiring specific neonatal intensive care unit (NICU) facilities.
- *Public health use*: To understand factors associated with low birthweight babies, which may require extra care upon birth (e.g. NICU level III), or extreme high birthweight babies, which may set baby at risk for metabolic disorders in childhood, which can inform the design of public health guidelines

## Dataset

This dataset consists of 3657 births and includes the following variables:

  * `babysex`: baby's sex (male = 1, female = 2)
  * `bhead`: baby's head circumference at 37 weeks (womb measurement) (centimeters)
  * `blength`: baby's length at 37 weeks (womb measurement) (centimeteres)
  * `bwt`: baby's birth weight (grams)
  * `fincome`: family monthly income (in hundreds, rounded)
  * `frace`: father's race (1 = White, 2 = Black, 3 = Asian, 4 = Puerto Rican, 8 = Other, 9 = Unknown)
  * `malform`: presence of malformations that could affect weight (0 = absent, 1 = present)
  * `menarche`: mother's age at menarche (years)
  * `mheigth`: mother's height (inches) 
  * `momage`: mother's age at delivery (years)
  * `mrace`: mother's race (1 = White, 2 = Black, 3 = Asian, 4 = Puerto Rican, 8 = Other)
  * `parity`: number of live births prior to this pregnancy
  * `ppbmi`: mother's pre-pregnancy BMI
  * `ppwt`: mother's pre-pregnancy weight (pounds)
  * `smoken`: average number of cigarettes smoked per day during pregnancy
  * `wtgain`: mother's weight gain during pregnancy (pounds).
  
Note: recommended weight gain during pregnancy differs by prepregnancy weight status:

- underweight (BMI<18.5): gain between 28-40 lbs
- normal (BMI 18.5-25): gain between 25-35 lbs
- overweight (BMI 25-30): gain between 15-25 lbs
- obese (BMI > 30): gain between 11-20 lbs


## Objective

The objective of this assignment is to build models to predict a baby's weight at birth from pre-birth measurements on mother and fetus, as well as to understand which factors are stronger predictors of birthweight. In questions 2-3, you should seek to build the predictive model with the strongest performance without focusing on parsimony (number of variables collected); such a model could have application in the clinical trial noted above, or in public health use or advanced clinical guidance. Question 4 asks you to build a parsimonious model to provide as guidance for a clinician.

