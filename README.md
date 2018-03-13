# springboard_capstone_2_final_submission

My capstone 2 project from Springboard is working with hotel reviews and building a classifier that detects deceptive reviews from the truthful reviews. As online reviews are impacting businesses more today, the importance of filtering out deceptive reviews is greater.

I made some edits to true-false_positive_feature_analysis.ipynb. Rather than comparing the two cohorts and their feature importance, I return the difference of the feature importance between the false and true positive cohorts. This difference is helpful for identifying which types of features are tripping the classifier into deception. The difference is calculated by taking the feature weight of the false positive group and subtract the feature weight of the true positive group, which represents the importance of the feature in the false positive class compared to the true positive class. 

My approach and results can be found in the final report and slide deck below.

Link for my final report: https://docs.google.com/document/d/1AsJbGz_Po5z_4oULTaAb4U4ki0YHFHrT9u-X4U23v4c/edit?usp=sharing

Link for my final slide deck: https://docs.google.com/presentation/d/1CE4fdtY3lsX-uEWPOZPTe-6U7jNYduKeVbzL3DRrVx4/edit?usp=sharing
