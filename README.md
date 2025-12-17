### College Event Feedback Analysis



##### Project Overview



This project focuses on analyzing student satisfaction survey data to understand feedback trends and identify strengths and improvement areas in the teaching and learning process. The objective is to convert survey responses into meaningful insights that can support institutional quality improvement and better student engagement.



The analysis was performed using Python, with visualizations and statistical summaries used to interpret satisfaction levels across multiple survey questions.





##### Dataset Description



The dataset used for this project is Student\_Satisfaction\_Survey.csv, which contains structured survey responses collected from students.



**Key columns include:**



* Questions
* Weightage 1 to Weightage 5
* Average/ Percentage
* Course Name
* Basic Course



Each row represents aggregated feedback for a specific survey question.





##### Tools and Technologies



* Python
* Google Colab
* Pandas
* Matplotlib
* Seaborn





##### Data Preparation



The following steps were carried out:



* Loaded the dataset using appropriate encoding
* Cleaned column names and removed unnecessary columns
* Extracted numeric values from mixed-format fields
* Created a new average score column for analysis
* Grouped data by survey questions to calculate mean satisfaction scores





##### **Analysis Performed**



* Question-wise average satisfaction analysis
* Identification of top-rated strengths
* Identification of lower-rated areas requiring improvement
* Visualization of satisfaction trends using bar charts





##### **Key Insights**



* Students rated fairness in evaluation and teacher communication very highly.
* Teaching preparation and use of examples were strong positive areas.
* Lower ratings were observed in mentoring support, use of ICT tools, and promotion of internships and field visits.
* Overall student satisfaction is high, with clear opportunities for targeted improvement.



##### Project Structure



FUTURE_DS_03/
│
├── College_Event_Feedback_Analysis.ipynb
├── Student_Satisfaction_Survey.csv
├── Screenshots/
│   ├── satisfaction_analysis.png
│   └── strengths_and_improvements.png
└── README.md



