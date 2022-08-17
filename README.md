# Talent-Hunter

#Part 1: Finding the right candidates for an interview
Screening many resumes and only contacting those relevant to the position is the first step in eliminating candidates. The process is a challenge if companies are handling high volumes of applicants and choose to screen applicants manually. We will build a resume screener for companies to take advantage and contact the most relevant candidates for the position. We utilize sklearn's cosine similarity and TfidfVectorizer to process and nltk's to visualize and derive the best candidates from a pool of applicants.

Dataset taken from: https://www.kaggle.com/datasets/wahib04/multilabel-resume-dataset

This dataset contains the category of the resume and the resume as a string. I renamed category to current occupation in order to add a little bit of story behind the dataset. This was the only resume dataset I found on Kaggle.

The application was deployed using Streamlit and further deployed publically using herokuapp.

https://halqaroni-talent-hunter-myapp-doiuq9.streamlitapp.com/

https://talent-huntering.herokuapp.com/


