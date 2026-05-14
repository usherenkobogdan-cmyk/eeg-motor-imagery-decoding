**Title
**EEG Motor Imagery Decoding

Short description

This project explores whether motor imagery states can be distinguished from EEG brain signals using a classical BCI pipeline.

Pipeline
EEG data loading from EEGBCI
event extraction and epoching
band-pass filtering (8–30 Hz)
binary classification (T1 vs T2)
CSP feature extraction
comparison of LDA, SVM, and Logistic Regression


Results
All models achieved high performance on subject-specific data.
The strongest baseline was CSP + LDA with mean accuracy around 97.1%.

Files
01_eeg_preprocessing.ipynb — preprocessing and epoch generation
02_model_8_30Hz.ipynb — model training and comparison
outputs/model_comparison.csv — final table
outputs/model_mean_accuracy.png — bar chart
outputs/model_accuracy_boxplot.png — boxplot


Why it matters

This project is a first step toward brain-computer interfaces, neural signal decoding, and neurotechnology systems that can interpret human intent from brain activity.
