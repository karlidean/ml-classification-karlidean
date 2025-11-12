# Applied Machine Learning - CSIS 44670 - Northwestern Missouri State University
A Midterm Repository by Karli Dean


## TL:DR - About the Project
- This is a repo detailing my midterm project for CSIS 44670 at Northwestern Missouri State University
- This is a graduate level course
- Data Used: UCI Heart Disease Data
  - Can be found in the `data` folder or at the link in the "About the Dataset" section.
- This project has 4 main pieces
  - [Jupyter Notebook](https://github.com/karlidean/ml-classification-karlidean/blob/main/notebooks/classification_karlidean.ipynb)
  - [README.md](https://github.com/karlidean/ml-classification-karlidean/blob/main/README.md)
    - This File!
  - [Heart Disease Data Set](https://github.com/karlidean/ml-classification-karlidean/blob/main/data/raw/heart_disease.csv)
  - [Peer Review](https://github.com/karlidean/ml-classification-karlidean/blob/main/peer_review.md)


## Process 1: Starting the Repository and Prepping my Machine
1. Created the repository on GitHub, enabling Pages
2. Cloned repo from GitHub to my machine
```shell
cd C:\Repos
git clone myrepolink.site
```
3. Set up the virtual environment
```shell
uv venv
uv python pin 3.12
uv sync --extra dev --extra docs --upgrade
uv run pre-commit install
uv run python --version
.\.venv\Scripts\activate
```


## Process 2: Setting Up the Project
1. Customized `pyproject.toml` and `mkdocs.yml`
2. Added project notebook in the `notebooks` folder
3. Added `peer_review.md` file
4. Add - Commit - Push
5. Added the dataset
   1. [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/45/heart+disease)
   2. Implemented this data using python in snippet 2 of the Jupyter Notebook
6. Add - Commit - Push


## About the Dataset (in order of column)
1. **age - age in years**
2. sex - sex (1 = male; 0 = female)
3. cp - chest pain type
   1. Value 1: typical angina
   2. Value 2: atypycal angina
   3. Value 3: non-anginal pain
   4. Value 4: asymptomatic
4. **trestbps - resting blood pressure (in mm Hg on admission to the hospital)**
5. **chol - serum cholesterol in mg/dl**
6. fbs - fasting blood sugar > 120 mg/dl (1 = true, 0 = false)
7. restecg - resting electrocardiographic results
   1. Value 0: normal
   2. Value 1: Having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05mV)
   3. Value 2: showing probable or definite left ventricular hypertrophy by Este's criteria
8. **thalach - maximum heart rate achieved**
9. exang - exercised induced angina (1 = yes; 0 = no)
10. **oldpeak - ST depression induced by exercise relative to rest**
11. slope - the slope of the peak exercise ST segment
    1.  Value 1: upsloping
    2.  Value 2: flat
    3.  Value 3: downsloping
12. ca - number of major vessels (0-3) colored by flouroscopy
13. thal - 3 = normal; 6 = fixed defect; 7 = reversable defect
14. **num - diagnosis of heart disease (angiographic disease status) (TARGET)**
    1.  Value 0: < 50% diameter narrowing
    2.  Value 1: > 50% diameter narrowing


## Process 3: Working Through the Project
1. Set up my project outline
   1. Pushed to GitHub during the process
2. Began working through each section to complete the computations.
3. Add - Commit - Push
4. Completed each section and annotated the notebook, pushing after each step.
   1. Edited README.md to bold the features I'd kept.
5. Completed peer review
   1. Edited README.md to reflect
