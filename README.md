# Datathon2024

Overview
The Datathon 2024 competition involved predicting the 'Değerlendirme Puanı' (Evaluation Score) for 11,049 applicants based on various anonymous attributes such as their university, family background, and other personal details. The goal was to build a model capable of accurately predicting these scores using a dataset of previous applications (train.csv) and to submit predictions in a specified format.

Participants were tasked with submitting a CSV file containing the id and the predicted Değerlendirme Puani for each applicant in the test set. The competition was held in multiple stages, with top teams progressing to further rounds and final presentations.

Timeline
Stage 1: Kaggle online competition (September 9 - September 15)
Stage 2: Top 10 teams/best individual participants presented their results to the jury.
Stage 3: The top 3 teams/individuals were invited to an award ceremony at the BTK Academy during the Data Science Summit.
Dataset Description
The dataset provided for the competition included two main files:

train.csv: The training set containing the historical data of applicants from 2014 onwards, including the 'Değerlendirme Puanı' (Evaluation Score).
test_x.csv: The test set containing data for 11,049 applicants from 2023, excluding the 'Değerlendirme Puanı' column.
sample_submission.csv: A sample submission file demonstrating the format for uploading predictions, containing the id and the predicted Değerlendirme Puani.
Features
The dataset contains various features that describe applicants' backgrounds, such as:

Personal Information: Gender, birth date, residence city, university, and grade point average.
Family Information: Parents' education level, employment, and sector.
Academic Information: University, department, scholarship status, and other academic details.
Extracurricular Activities: Participation in entrepreneurship clubs, NGOs, professional sports, etc.
The full list of features can be found in the dataset description.

Evaluation Metric
The performance of the models was evaluated using Root Mean Squared Error (RMSE), a common metric to measure prediction accuracy. RMSE calculates the square root of the average squared differences between predicted and actual values.
