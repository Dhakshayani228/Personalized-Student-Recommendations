# Personalized-Student-Recommendations
Personalized Student Recommendations for NEET Preparation

# Data Overview
This project utilizes two key datasets to analyze and provide personalized recommendations for NEET preparation based on quiz performance:

# Current Quiz Data:
Contains details of a student's most recent quiz submission.
Includes data such as questions, topics, responses, and the overall score for the latest quiz taken.
This dataset serves as the real-time data source for the student's performance.

# Historical Quiz Data:
Contains performance data from the last 5 quizzes taken by each student.
Includes scores, response maps (which are stored as Key-Value pairs representing the question ID and the selected option ID), and other relevant metrics.
This dataset serves to analyze trends and performance patterns over time.

# Task Overview
The goal of this project is to develop a Python-based solution that analyzes the quiz performance and generates personalized recommendations for students to improve their NEET preparation.

1. Analyze the Data:
Explore the dataset schema and identify patterns in student performance based on:
Topics: Which topics the student excels in and which they struggle with.
Difficulty Levels: How the student performs across different difficulty levels.
Response Accuracy: How accurately the student responds to quiz questions.
2. Generate Insights:
Weak Areas: Identify which topics or areas the student needs to focus on based on low accuracy.
Improvement Trends: Track performance over time and highlight areas where the student has shown improvement.
Performance Gaps: Identify areas where the student is underperforming and suggest improvements.
3. Create Recommendations:
Actionable Steps: Based on the analysis, generate actionable steps that the student can take to improve their preparation:
Focus on weak topics.
Practice questions from specific difficulty levels.
Review past quiz responses to identify patterns in mistakes.
Bonus Points:
Student Persona: Analyze and categorize students based on their quiz performance patterns.
Generate insights on strengths and weaknesses using creative labels (e.g., "Top Performer", "Needs Improvement").
NEET Rank Prediction: Build a probabilistic model that predicts a student's potential NEET rank based on their quiz performance and historical NEET results.

# Project Features:
Personalized Recommendations: Suggest areas to improve based on performance analysis.
Performance Visualization: Visualize topic-wise accuracy and trends over time.
Probabilistic NEET Rank Prediction: Predict a student's rank based on their quiz performance and simulate NEET scores.
Student Persona Creation: Classify students as "Top Performer", "Average Performer", or "Needs Improvement".

# Example Output:
Topic-wise Accuracy: A bar chart showing the student's accuracy in different topics.
NEET Rank Prediction: The model's prediction of the student's NEET rank based on their performance.
Personalized Recommendations: Suggested areas for improvement and actionable steps.

