# Talent-Hunter

#Part 1: Finding the right candidates for an interview
As a part of the hiring process, it is crucial to efficiently review a large number of resumes and identify the most qualified candidates for the position. However, this can be a challenging task, especially when there are high volumes of applicants and manual screening is required. That's why we developed a resume screener tool to help companies easily identify the most relevant candidates. Our screener uses sklearn's cosine similarity and TfidfVectorizer to process resumes and nltk to visualize and select the top candidates from the pool of applicants. By using our tool, companies can streamline their hiring process and efficiently find the best fit for their open positions.

Dataset taken from: https://www.kaggle.com/datasets/wahib04/multilabel-resume-dataset

This dataset contains the category of the resume and the resume as a string. I renamed category to current occupation in order to add a little bit of story behind the dataset. This was the only resume dataset I found on Kaggle.

The application was deployed using Streamlit and further deployed publically using herokuapp.

https://halqaroni-talent-hunter-myapp-doiuq9.streamlitapp.com/

https://talent-huntering.herokuapp.com/


