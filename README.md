# Github Actions Matrix 
#### Project that builds a GitHub Actions matrix to test multiple versions of python for MiniProj 2 (Descriptive Stats with Pandas)
---
#### Requirements:

- [X] Set up a Gitlab Actions workflow
- [X] Test across at least 3 different Python versions
- ##### Other:
- [X] Generate summary statistics (mean, median, standard deviation)
- [X] Create at least one data visualization
- [X] Python script 
- [X] CI/CD with badge

---
### Folder Navigation
##### Here is a quick overview of how the folders are structured for this project:
---
- Project Folder
    - .devcontainer
        - devcontainer.json
        - Dockerfile
    - .github
        - workflows
            - matrix.yml
    - outputs
        - ADD OUTPUT HERE
    - python_files
        - test_files
            - test_main.py
            - test_lib.py
        - lib.py
        - main.py
    - Makefile
    - README.md
    - requirements.txt
---
### Workflow Summary and Explanation
##### This project contains the following dependencies:
- pylint 
- black
- pytest
- pandas
- matplotlib
- ruff
- nbval
- jupyter
- tabulate

---
### Descriptive Statistics Table
---
###### The following table is the main.py output, indicating the count, mean, std, min, quartiles, and max for the numeric variables


---
### Visualizations
---
###### The following graph is a visualization created by the script, which displays:


