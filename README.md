Overview
This project focuses on predicting students' academic performance (final grades) using machine learning. The dataset consists of various features such as attendance, study habits, socio-economic factors, and more. The objective is to build a classification model to predict the final performance class of students based on these features.

Dataset
The dataset contains 480 records and 17 columns, including both categorical and numerical features. The target column is Class, which represents the student's final performance class. Features include:

Categorical: gender, NationalITy, PlaceofBirth, StageID, GradeID, SectionID, Topic, Semester, Relation, ParentAnsweringSurvey, ParentschoolSatisfaction, StudentAbsenceDays
Numerical: raisedhands, VisITedResources, AnnouncementsView, Discussion
Objective
The goal of this project is to predict the final Class of the student (Low, Medium, or High) based on the features provided. We use a Random Forest Classifier to accomplish this.

Project Structure
The project contains the following key components:

Dataset: The dataset used for the model (replace your_dataset.csv with your actual dataset).
Model Training: The code builds a Random Forest classifier to predict the student performance class.
Evaluation: The model is evaluated using accuracy and classification reports.

4. Run the Model:
You can run the model training and prediction using:
         python student_performance_model.py
5. Model Output:
After running the model, you will see the model's accuracy score and a classification report in the terminal output.
