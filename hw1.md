# CS559 Machine Learning: Fundamentals and Applications
Fall 2023 HW#1
Due: 9/16/2023 12:00 AM
• The assignment must be individual work and must not be copied or shared. Any tendency to cheat/copy evidence will lead to a 0 mark for the assignment.
• The application problems must be worked on in the notebook using Python. If the problem does not mention the libraries/packages to use, students must only use Pandas, NumPy, and Spacy. All problems must be in a single notebook file as Name_HW#.ipynb.
• All files must be compressed into a single zip file as Name_HW#.zip.
 
 
Question 1. Titanic Data Training [45 pts]
The objective of the provided data set is to classify whether the passengers survived or not. In this assignment, students will perform the train data preparation. Using the provided data set, train the dataset by completing the following.
 
1. (5 pts) Determine the data type of features.
2. (5 pts) Determine the ratio of survival rate. The ideal binary classification situation (e.g., T/F or 1/0) has a 50-to-50 ratio, which we call the balanced set.
3. (5 pts) Determine the missing value features and their number of observations. Explain how you would handle features. Explain whether deleting the feature(s) or observation(s) is the best choice. If not, explain why not.
4. (5 pts) Determine any feature(s) that can be removed. Explain why. Then remove them.
5. (5 pts) Convert text feature(s) into a numerical feature(s). Explain if any features do not require numerical conversion.
6. (10 pts) Write a method “data_split(data, ratio)” that shuffles the observations and splits the input data set by the input ratio between 0 and 1. Let the method returns the split data sets.
7. (10 pts) Write a method “k_fold_CV(data, k)” that shuffles the observations and returns k many validation sets. But the repetition of observations must be avoided.