# lvv-ri
## Lateral Ventricle Volume trajectories and Response Inhibition

Astri J Lundervold, Alexandra Vik, Arvid Lundervold.
Lateral ventricle volume trajectories predict response inhibition in older age - a
longitudinal brain imaging and machine learning approach. PLOS ONE Manuscript draft

**Abstract**

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
