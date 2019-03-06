# lvv-ri
## Lateral ventricle volume trajectories predict response inhibition in older age - a longitudinal brain imaging and machine learning approach

Astri J Lundervold, Alexandra Vik, Arvid Lundervold.
Lateral ventricle volume trajectories predict response inhibition in older age - a
longitudinal brain imaging and machine learning approach. PLOS ONE Manuscript draft

**Abstract**

{\bf Objective:} In a three-wave 6 yrs longitudinal study we investigated if the expansion of lateral ventricle (LV) volumes (regarded as a proxy for brain tissue loss) predicts third wave performance on a test of response inhibition (RI).
{\bf Participants and Methods:}  Trajectories
of left and right lateral ventricle volumes across the three waves were quantified using the longitudinal stream in Freesurfer. All participants ($N=74$;$48$ females;mean age $66.0$ yrs at the third wave) performed the Color-Word Interference Test (CWIT). Response time on the third condition of CWIT, divided into {\tt fast}, {\tt medium} and {\tt slow}, was used as outcome measure in a machine learning framework. Initially, we performed a linear mixed-effect (LME) analysis to describe subject-specific trajectories of the left and right LV volumes (LVV). These features were input to a multinomial logistic regression classification procedure, predicting individual belongings to one of the three RI classes. To obtain results that might generalize, we evaluated the significance of a $k$-fold cross-validated f1 score with a permutation test, providing a $p$-value that approximates the probability that the score would be obtained by chance. We also calculated a corresponding confusion matrix.
{\bf Results:} The LME-model showed an annual $\sim3.0$\% LVV increase. Evaluation of a cross-validated score using $500$ permutations gave an f1-score of $0.462$ that was above chance level ($p=0.014$). $56$\% of the fast performers were successfully classified. All these were females, and typically older than $65$ yrs at inclusion. For the true slow performers, those being correctly classified had higher LVVs than those being misclassified, and their ages at inclusion were also higher.
{\bf Conclusion:} Major contributions
were: (i) a longitudinal design, (ii) advanced brain imaging and segmentation procedures with longitudinal data analysis, and (iii) a data driven machine learning approach including cross-validation and permutation testing to predict behaviour, solely from the individual's brain ``signatures” (LVV trajectories).

*Objective:* In a three-wave 6 yrs longitudinal study we investigated if expansion of 
lateral ventricle (LV) volumes (regarded as a proxy for brain parenchyma loss) predicts
performance on a test of response inhibition. *Participants and Methods:* Anatomical
trajectories of left (LH) and right (RH) lateral ventricle volumes across the three
study-waves were quantified using the Longitudinal Stream in Freesurfer 5.3 and
modelled using a linear mixed-effects (LME) algorithm. All participants (N = 74, mean
age 60.7 yrs at inclusion, 48 females) performed the Color-Word Interference Test
(CWIT). Response time on the third condition was used as a measure of response
inhibition (RI) and divided into three classes (fast, medium and slow). The Extreme
Gradient Boosting (XGBoost) algorithm was used for calculating the relative
importance of selected LV volume features from the LME model in predicting RI class.
Finally, the two most important extracted features were fed into a 10-fold
cross-validation framework, estimating the accuracy, precision and recall of the RI class
prediction. *Results:* Four LME based features were selected to characterize LV volume
trajectories: steepness of LV volume change and the LV volume at the time of
inclusion, each from the right and left hemisphere. The XGBoost procedure selected the
steepness measure from the right and the volume at inclusion from the left hemisphere as the two
most important features to predict RI performance. The 10-fold cross validation
procedure showed a recall, precision and accuracy score (.40 - .50) that were clearly
above chance level. *Conclusion:* Measures of the LV volume trajectories gave a fairly
good prediction of response inhibition performance, confirming the role of LV volume
as a biomarker of cognitive function in older adults. Future studies should investigate the
value of the lateral ventricle volume trajectories as predictors of cognitive preservation
or decline into older age.
