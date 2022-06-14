# model_comparison

A comparison of different model types using SAMueL-1 data

To Do:

Compare the following mdoel types:

1) Log reg - combined fit
2) Log reg - individial hospital fit
3) Random forest - combined fit
4) Random forest - individial hospital fit
5) XGB - combined fit
6) XGB forest - individial hospital fit
7) Fully connected net - combined fit
8) Embedding net - combined fit

---

For all:

Save individual prediction from k-fold test set

---

Perform the following tests (k-fold):

1) Accuracy measurements
2) ROC_AUC
3) Identify cross-over point of sensitivity and specificity
4) Compare predicted and observed thrombolysis use at each hospital (combiedn k-fodl test sets)
5) Check model calibration
6) Check for thrombolysis of haemorrhagic stroke patients in test set
7) Perform learning curves

---

Check with the following modifications:

1) Calibrated threshold (based on training set)
2) Balanced trainign set (over-sample minority class in training set)


