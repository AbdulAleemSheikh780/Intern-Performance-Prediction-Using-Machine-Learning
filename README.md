# Intern_Performance_Prediction_Using_ML

Overview
A Machine Learning project that predicts intern performance based on engagement metrics like attendance, task completion, feedback scores, and interaction levels. The goal is to help mentors identify at-risk interns early and provide personalized guidance.

Objective
Predict whether an intern will be a High, Medium, or Low performer — before the final assessment.

Dataset Features
FeatureDescriptionattendance_rate% of days intern was presenttask_completion_rate% of tasks completed on timeavg_feedback_scoreMentor feedback score (1–5)hours_per_weekAverage working hours per weekinteraction_levelLow / Medium / HighdepartmentTech, HR, Marketing, Finance, Operations

Target Variable: performance_category → High / Medium / Low
ML Models Used

ModelPurposeRandom Forest ClassifierMain prediction modelLogistic RegressionComparison baseline

Results


Trained and compared 2 ML models
Generated mentor insights for each intern automatically
Identified Task Completion Rate and Attendance as top performance predictors
Built a prediction tool for new interns

Key Insight


Interns with high task completion (>80%) and attendance (>85%) are 3x more likely to be top performers.
