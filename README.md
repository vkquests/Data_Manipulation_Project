# Data_Manipulation_Project
This data manipulation project focuses on transforming raw data into actionable insights through preprocessing, cleansing, and structuring. The dataset originates from a survey, gathering responses from individuals to various questions, with two primary objectives:

1. Calculate the number of unique respondents for each question.
2. Determine the frequency of identical answers received for specific questions.

## Data Preprocessing
* Header and Subheader Combination: The initial data had separate header and subheader rows. To address this, we concatenated and transposed them using Excel's "Paste Special" function.

* Concatenation of Columns: Header and subheader columns were merged into a unified set of column names.

* Transposing Columns Back to Rows: The concatenated column was transposed back into rows to prepare the data for Python analysis.

## Data Analysis
* Counting Unique Respondents: We identified the number of unique respondents for each question, considering only answered questions.

* Counting Identical Answers: We calculated the frequency of identical answers for specific questions, including 'not answered' responses.

## Conclusion
Data manipulation is a pivotal step in the data analysis process. This project showcases the significance of preprocessing and structuring raw data to extract valuable insights and address specific business questions.
