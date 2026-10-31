# SMS Spam Detection Using Data Structures and Algorithms

## 1. Project Overview

SMS Spam Detection is a Python-based project that uses Machine Learning and Data Structures and Algorithms (DAA) to identify spam and genuine text messages.

The project classifies SMS messages into two categories: Spam and Not Spam. It also uses searching and sorting algorithms to manage and analyse prediction history.

## 2. Objectives

- To identify spam and genuine SMS messages.
- To understand the practical use of algorithms.
- To implement Linear Search for searching SMS records.
- To implement Merge Sort for sorting SMS messages.
- To measure and analyse algorithm execution time.
- To understand algorithm efficiency and time complexity.

## 3. Technologies Used

- Python
- Flask
- Scikit-learn
- Pandas
- SQLite
- HTML and CSS
- TF-IDF
- Multinomial Naive Bayes

## 4. Algorithms Used

### A. Linear Search

Linear Search is used to find SMS messages in the prediction history.

The algorithm checks each record one by one until a matching message is found.

**Time Complexity:**
- Best Case: O(1)
- Average Case: O(n)
- Worst Case: O(n)

### B. Merge Sort

Merge Sort is used to arrange SMS messages alphabetically.

It divides the list into smaller parts, sorts them and then merges the sorted parts.

**Time Complexity:**
- Best Case: O(n log n)
- Average Case: O(n log n)
- Worst Case: O(n log n)

**Space Complexity:** O(n)

## 5. Performance Analysis

The project measures the execution time of Linear Search and Merge Sort using Python's `time.perf_counter()` function.

The execution time is measured using the available SMS prediction records.

This helps in understanding how algorithms perform when working with different amounts of data.

## 6. Working of the Project

1. The user enters an SMS message.
2. TF-IDF converts the message into numerical features.
3. The trained Naive Bayes model predicts whether the message is spam or not.
4. The prediction is stored in the SQLite database.
5. Linear Search is used to search messages in prediction history.
6. Merge Sort arranges messages alphabetically.
7. Execution time is measured for algorithm performance analysis.

## 7. Machine Learning Component

The project uses Multinomial Naive Bayes for SMS classification.

TF-IDF is used for feature extraction. It converts text messages into numerical values that can be processed by the classifier.

## 8. Database Management

SQLite is used to store prediction history, including SMS messages, prediction results and timestamps.

## 9. Conclusion

This project demonstrates the practical application of Data Structures and Algorithms in a real-world problem.

By implementing Linear Search, Merge Sort and execution time measurement, the project provides an understanding of algorithm design, searching, sorting and performance analysis.

It also combines Python programming and Machine Learning to develop an SMS spam detection system.
