# Resume-Analysis-using-NLP

### Goal
The main goal of this project is to build a model that scans a group of users resume and highlights skills/technologies that assists employers to choose a person with the highest skill they require through detailed visualizations.

### Data Used
Collected resumes from the peers in both word and pdf format. Prepared a dictionary of words based on the research we have done by analyzing data science/analyst job descriptions.

### Packages Used
numpy, pandas, re, spaCy, docx2txt, pydf2, nltk, textract, genism and CountVectorizer. 

### Techniques
Pattern Matching, Text Summarization, Skill wise Classification and Spell Checker. 

### IDE
Python 3.7

### Evaluation Metric
Cosine Similarity. 

### Steps Included:
1. First, to check whether the resume is in proper format we implemented spell checker and checked for missing key words between resume and job description.
2. Second, we performed text summarization of the resume and with the help of cosine similarity we learnt how similar are the resumes to the JD.
3. Next, we plotted a pie chart to see the different skills of each person and finally with the help of bar chart we performed skill-wise comparison among all the applicants.

Built a model that scans a group of users’ resume and highlights skills/technologies using bar chart and pie chart that assists employers to choose a person with the highest skill they require through detailed visualizations. The model is beneficial for applicants and employers to check similarity among job description and resumes for Data Analytics / Data Science job roles. 

### Conclusion
The methods implemented in this project range from pattern matching, text summarization, text classification, skill-wise comparison, missing keywords and spell checker which validifies with similarity score of Cosine and dissimilarity score of Jaccard. 
Aimed to increase the predicting power of getting rejected or accepted into a job more accurately in the future for the candidates. This will be helpful during a hiring freeze, recession, for new graduates and unpredictable pandemics.

### Limitations
The dictionary creation tends to be biased based on the creator of the program’s input. The lack of a pre-defined dataset or corpus to apply these algorithms on a much larger sample of data. 

### Future Work
More focus on missing value keywords by providing exact percentage of missingness and similarities of the job description and resumes. Work is focused on Data Analytics field but can be applied to any other industry roles. Extensions may include, software engineering, product management, business development, sales, etc. 
