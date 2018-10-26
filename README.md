## Statistical analysis tools for the Boston Lung Cancer Survival Cohort (BLCSC) study

The Boston Lung Cancer Survival Cohort (BLCSC) study is a cancer epidemiology cohort of 11,164 lung cancer cases, enrolled at the Massachusetts General Hospital (MGH), the Dana-Farber Cancer Institute (DFCI), and the Brigham and Women's Hospital since 1992. Dr. David C. Christiani (Harvard TH Chan School of Public Health) is the project director of the BLCSC study, which has collected detailed demographic, smoking, occupational, dietary information, in addition to pathology, radiomics, treatments history, oncogenic mutation status, serum, white blood cells, DNA, and tumor tissues. 


#### Covariance-insured screening
 * By incorporating the inter-feature dependence, a covariance-insured screening approach is proposed
to identify predictors that are jointly informative but marginally weakly associated with outcomes.
  * [paper](https://www.stt.msu.edu/users/hhong/2018-CIS_CSDA_final%20%281%29.pdf)
  * [R code]
  
#### Partition-based screening
 * Leveraging prior grouping information on covariates, the partition-based screening methods for ultrahigh-dimensional variables is proposed in the framework of generalized linear models
 * [paper](https://www.stt.msu.edu/users/hhong/pbs.pdf)
 * [R code]()

#### Weak signals in high-dimensional regression: Detection, estimation and prediction
 * This method aims to incorporate weak signals in variable selection,
estimation, and prediction. W
 * [paper](https://www.stt.msu.edu/users/hhong/asmb.2340%20%281%29.pdf)
 * [R code]()


#### The Lq-norm learning for ultrahigh-dimensional survival data: an integrated framework
* The Lq-norm learning is proposed to detect predictors with various levels of impact, such as short- or long-term impact, on censored
outcome.
  * [paper](https://www.stt.msu.edu/users/hhong/2018-CMC-0715-4p.pdf)
  * [R code](https://github.com/younghhk/software/blob/master/Lq.R)
  
#### Integrated powered density (IPOD): screening ultrahigh dimensional covariates with survival outcome
 *  With a flexible weighting scheme, Kolmogorov statistic as a special case,  IPOD method can detect early or late impact on censored outcome.
  * [paper](https://www.stt.msu.edu/users/hhong/Hong_et_al-2017-Biometrics.pdf)
  * [R code](https://github.com/younghhk/software/blob/master/IPOD.R)
 
#### Conditional screening for survival data
 * The recently developed variable screening methods, though powerful in many practical setting,  are less powerful in detecting marginally weak while jointly important signals. A new conditional screening method for survival outcome data computes the marginal contribution of each biomarker given priorily known biological information.

 * [paper](https://www.stt.msu.edu/users/hhong/conditional_survival.pdf) 
 * [R code](https://github.com/younghhk/software/blob/master/CS.R)

