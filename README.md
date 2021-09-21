# Judicial Authorship attribution and Influence Detection [[PDF](https://github.com/municola/authorship-prediction/blob/master/Judicial%20Authorship%20attribution%20and%20Influence%20Detection.pdf)]

## Task
We try to solve two research questions:
- Can we predict which judge wrote which opinion text (Yes)
- Can we detect influence of some judges on the decision of other judges (Maybe)


## Method
**Architecture**: After some data cleaning, we use a bag of words with n-Grams approach and then apply an SVM to classify<br>
**Performance**: On the Authorship Attribution task we achieve an accuracy up to 95% (Average for the newest time-split: 0.85) 


## This Repository contains:
- Report 'Judicial Authorship attribution and Influence Detection'
- Folders 85 - 97 for each circuit court (See list below) which each contains:
	- Jupyter notebook with replication code
	- Results of the Notebooks

### Number to american circuit court mapping
85: 1st Circuit Court<br>
86: 2nd Circuit Court<br>
87: 3rd Circuit Court<br>
88: 4th Circuit Court<br>
89: 5th Circuit Court<br>
90: 6th Circuit Court<br>
91: 7th Circuit Court<br>
92: 8th Circuit Court<br>
93: 9th Circuit Court<br>
94: 10th Circuit Court<br>
95: 11th Circuit Court<br>
96: 12th Circuit Court <br>
97: Supreme Court<br>

