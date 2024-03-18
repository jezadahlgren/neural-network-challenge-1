# neural-network-challenge-1
Module 18 Challenge - Neural Network first challenge 


**Name:** Module 18 Challenge: neural-network-challenge-1

**Description:**

According to the module, this is a company that specializes in student loan refinancing.  They have asked me to see if I can predict wheather a student borrower will replay thier loan and as a follow-up what are the data considerations for a recommendation system (likely the next assignment).  

**Support:**

The build of the supoort was provided through class lessons which one question thrown to copilot.

**Libraries imported:**

- pandas
- tensorflow
    - from tensorflow.keras.layers import Dense
    - from tensorflow.keras.models import Sequential
    - from sklearn.model_selection import train_test_split
    - from sklearn.preprocessing import StandardScaler
    - from sklearn.metrics import classification_report
    - from pathlib import Path

**Data analysis process and results:**

The data was explored, trained, scaled and tested.  Deep neural networks were used to create a multiple hidden layer model that had a reasonable accuracy score (.72). For financial data, I would expect this model would need to include additional data prior to pushing into a LIVE environment.  

