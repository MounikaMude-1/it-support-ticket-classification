
# IT Support Ticket Classification Using Machine Learning

## Project Overview
This project uses Python and Machine Learning to classify IT support
tickets into four categories: Network, Access, Software, and Hardware.

## Problem Statement
IT support teams receive many tickets every day. Manually categorizing
each ticket can take time. This project demonstrates how machine learning
can help automatically categorize ticket descriptions.

## Technologies Used
- Python
- Pandas
- Scikit-learn
- TF-IDF Vectorization
- Logistic Regression
- Matplotlib
- Google Colab

## Dataset
The project uses 40 manually created example support tickets,
with 10 tickets in each category.

The dataset is synthetic and intended for learning and demonstration.
It is not a real company dataset.

## Methodology
1. Create and explore the ticket dataset.
2. Split the data into training and testing sets.
3. Convert text into numerical features using TF-IDF.
4. Train a Logistic Regression classifier.
5. Evaluate predictions on the test set.
6. Test the model with new ticket descriptions.
7. Save the trained model.

## Categories
- Network
- Access
- Software
- Hardware

## Limitations
The dataset is small and synthetic. Test accuracy may vary and does
not establish performance on real-world IT support tickets.
A larger, realistic, labeled dataset is needed for reliable evaluation.

## Future Improvements
- Use a larger real-world dataset.
- Improve classification with more diverse ticket descriptions.
- Compare multiple machine learning algorithms.
- Build a simple web application for ticket classification.

## Author
Created as a beginner machine learning portfolio project.
