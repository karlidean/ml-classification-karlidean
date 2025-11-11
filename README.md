# Applied Machine Learning - CSIS 44670 - Northwestern Missouri State University
A Midterm Repository by Karli Dean

## TL:DR - About the Project
- This is a repo detailing my midterm project for CSIS 44670 at Northwestern Missouri State University
- This is a graduate level course
- Data Used: UCI Heart Disease Data
  - Can be found in the `data` folder or at the link in the "About the Dataset" section.
- This project has 4 main pieces
  - Jupyter Notebook (main project)
  - README.md (this file)
  - Dataset (data folder)
  - Peer Review (found at peer_review.md)


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
