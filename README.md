Parkinson's Disease Prediction System
Welcome to the Parkinson's Disease Prediction System repository! This project utilizes machine learning algorithms to predict the presence of Parkinson's disease based on various biomedical voice measurements. The aim is to aid in the early detection and diagnosis of Parkinson's disease, facilitating timely medical intervention and management.

Features
Data Preprocessing: Clean and preprocess the dataset to ensure optimal model performance.
Exploratory Data Analysis (EDA): Visualize data distributions, correlations, and extract key insights.
Model Training: Implement multiple machine learning algorithms
Model Evaluation: Compare models using accuracy and  precision Function

Dataset:

Context
Parkinson’s Disease (PD) is a degenerative neurological disorder marked by decreased dopamine levels in the brain. It manifests itself through a deterioration of movement, including the presence of tremors and stiffness. There is commonly a marked effect on speech, including dysarthria (difficulty articulating sounds), hypophonia (lowered volume), and monotone (reduced pitch range). Additionally, cognitive impairments and changes in mood can occur, and risk of
dementia is increased.

Attribute Information:
Matrix column entries (attributes):
name - ASCII subject name and recording number
MDVP:Fo(Hz) - Average vocal fundamental frequency
MDVP:Fhi(Hz) - Maximum vocal fundamental frequency
MDVP:Flo(Hz) - Minimum vocal fundamental frequency
MDVP:Jitter(%),MDVP:Jitter(Abs),MDVP:RAP,MDVP:PPQ,Jitter:DDP - Several
measures of variation in fundamental frequency
MDVP:Shimmer,MDVP:Shimmer(dB),Shimmer:APQ3,Shimmer:APQ5,MDVP:APQ,Shimmer:DDA - Several measures of variation in amplitude
NHR,HNR - Two measures of ratio of noise to tonal components in the voice
status - Health status of the subject (one) - Parkinson's, (zero) - healthy
RPDE,D2 - Two nonlinear dynamical complexity measures
DFA - Signal fractal scaling exponent
spread1,spread2,PPE - Three nonlinear measures of fundamental frequency variation
