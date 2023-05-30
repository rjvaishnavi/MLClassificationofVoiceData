# MLClassificationofVoiceData
##### Dataset is stored in parkinsons.data
##### Trained model is stored as
Using  Various Machine Learning Techniques to Analyze Voice Disorders for Parkinson's Disease Detection
Techniques used include:
- KNN classification
- Logistic Regression
- Support Vector Machines (SVM)
- Random Forest Model


Dataset from : <a href=https://archive.ics.uci.edu/ml/datasets/parkinsons>Voice disorder dataset</a>
Preprocessing the data using t-SNE analysis rather than PCA

#Information about the DataSet
### Parkinson Data and Voice Disorder

This dataset is composed of a range of biomedical voice measurements from 31 people, 23 with Parkinson's disease (PD).  Our dataset includes voice attributes Information that can be used for detecting parkinson, these information including:
Matrix column entries (attributes):  
- name - ASCII subject name and recording number
- MDVP:Fo(Hz) - Average vocal fundamental frequency
- MDVP:Fhi(Hz) - Maximum vocal fundamental frequency
- MDVP:Flo(Hz) - Minimum vocal fundamental frequency
- Five measures of variation in Frequency
    - MDVP:Jitter(%) - Percentage of cycle-to-cycle variability of the period duration
    - MDVP:Jitter(Abs) - Absolute value of cycle-to-cycle variability of the period duration
    - MDVP:RAP - Relative measure of the pitch disturbance
    - MDVP:PPQ - Pitch perturbation quotient
    - Jitter:DDP - Average absolute difference of differences between jitter cycles
- Six measures of variation in amplitude
    - MDVP:Shimmer - Variations in the voice amplitdue
    - MDVP:Shimmer(dB) - Variations in the voice amplitdue in dB
    - Shimmer:APQ3 - Three point amplitude perturbation quotient measured against the average of the three amplitude
    - Shimmer:APQ5 - Five point amplitude perturbation quotient measured against the average of the three amplitude
    - MDVP:APQ - Amplitude perturbation quotient from MDVP
    - Shimmer:DDA - Average absolute difference between the amplitudes of consecutive periods
- Two measures of ratio of noise to tonal components in the voice
    - NHR - Noise-to-harmonics Ratio and 
    - HNR - Harmonics-to-noise Ratio
- status - Health status of the subject (one) - Parkinson's, (zero) - healthy
- Two nonlinear dynamical complexity measures
    - RPDE - Recurrence period density entropy
    - D2 - correlation dimension
- DFA - Signal fractal scaling exponent
- Three nonlinear measures of fundamental frequency variation
    - spread1 - discrete probability distribution of occurrence of relative semitone variations
    - spread2 - Three nonlinear measures of fundamental frequency variation
    - PPE - Entropy of the discrete probability distribution of occurrence of relative semitone variations
