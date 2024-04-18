# Job-recommendation-system-Content-Based
Job recommendation system using machine learning. The system is designed to provide personalized job recommendations based on user preferences and historical job data. It is Content-based Recommendation system, where key and content from the job Data is used and based on Preference given chosen by User the data is recommended.

# Basic Functionality
The goal of this project is to develop a job recommendation system that helps users find relevant job opportunities based on their preferences and historical data. By leveraging machine learning techniques, we aim to provide personalized recommendations that align with the user's skills, interests, and career goals. The system will take into account various factors such as job title, salary estimate, company rating, location, industry, and more to generate accurate recommendations.

# Data 
Data is read from the file 

# libraries used 
numpy for  linear algebra
pandas for data processing, CSV file I/O (e.g. pd.read_csv)
ntlk (Natural Language Toolkit) library
streamlit

# Machine Learning Techniques:
To provide personalized job recommendations, we employ the TF-IDF (Term Frequency-Inverse Document Frequency) vectorization technique. The "job_recommender-sytem.py" component plays a crucial role in this process.
In this Natural Language Toolkit (NLTK) library helps in data cleaning process( done by removing stopwords and performing stemming). It utilizes the TF-IDF vectorizer from the scikit-learn library to transform job title and descriptions into numerical feature vectors. These vectors capture the importance of each word in the documents, enabling the system to find similar job opportunities based on user preferences. 

Stemming aims to reduce words to their base or root form.
For example, "running," "runs," and "ran" would all be stemmed to "run."
The goal is to group similar words together, focusing on their core meaning.
