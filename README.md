# CS231_code_practice
# Content
  1.The code of KNN

  2.Distance matrix (L1 coordinate dependency, individual elements does have meaning,L2) Try them both and see which one is better

  3.Hyperparameters: 
       3.1 we set for the algorithm but not the parameters that learned by the algorithm. Problem-dependent. Try            and error. Sometimes choosing the hyperpaters that give the highest accuracy and performance. K=1                always work the best in the data, but that was wrong.
       3.2 Suggested way: split the data into three dataset, train,validate and test. Train with different choice            in training, check it in validate, run once in test.
       3.3 Cross validation, use commonly in a small dataset, not DL. Take dataset,split into different fold                after taking out the last part for testing.

   4. KNN is never used in picture classification:1) slow testing time, 2) the distance matrics on pixels are not informative 3) Curse of dimensionality
