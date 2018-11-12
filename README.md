# Recommender-for-DonorsChoose

This notebook explores different approaches to helping DonorsChoose recommend the right project to right user. So far we have tried the following methods:

- Content-based recommendations using tfidf
  - tfidf project descriptions
  - Calcualte document distances (e.g. cosine similarity)
  - Explore document similarity
  - Create recommendations based on similarity
  - Create evaluation metric to test whether similarity is a good predictor for recommendations
  - E.g. For users with #donations > 1 omit last donation, get ranking based on similar projects, check the ranking score of actually donated (omitted) projects
  - Compare score agains popularity "algorithm" performance and "recommending distinct projects" or "random projects"
    ...

Other relevant methods:

- Topic models using LDA
- Tag generation (automated tagging)

Links

- Nice tfidf helper code: https://towardsdatascience.com/hacking-scikit-learns-vectorizers-9ef26a7170af
- We started doing approximately the content based recommender from here: https://www.kaggle.com/ranliu/donor-project-matching-with-recommender-systems/code (with more code but different challenge here: https://www.kaggle.com/gspmoreira/recommender-systems-in-python-101/code)

