# Build a Student Intervention System

Supervised Learning Project

## Install

This project requires Python 2.7 and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

## Code

The code is provided in the notebook `student_intervention.ipynb`.

To open it, go to the top-level project directory `student_intervention/` and start the notebook server:

```jupyter notebook```

This should open a web browser to the server's dashboard (typically `http://127.0.0.1:8888`). Click on the appropriate notebook (`.ipynb`) to open it, and follow the instructions.

## Run

To run a code cell in the notebook, hit `Shift+Enter`. Any output will be displayed below the corresponding cell.

You can also add/edit markdown text cells and render them using `Shift+Enter`.

## Data

The dataset used in this project is included as `student-data.csv`. It has the following atributes for each student:

- absences - number of school absences (numeric: from 0 to 93)
- activities - extra-curricular activities (binary: yes or no)
- address - student's home address type (binary: "U" - urban or "R" - rural)
- age - student's age (numeric: from 15 to 22)
- Dalc - workday alcohol consumption (numeric: from 1 - very low to 5 - very high)
- failures - number of past class failures (numeric: n if 1<=n<3, else 4)
- famrel - quality of family relationships (numeric: from 1 - very bad to 5 - excellent)
- famsize - family size (binary: "LE3" - less or equal to 3 or "GT3" - greater than 3)
- famsup - family educational support (binary: yes or no)
- Fedu - father's education (numeric: 0 - none, 1 - primary education (4th grade), 2 – 5th to 9th grade, 3 – secondary education or 4 – higher education)
- Fjob - father's job (nominal: "teacher", "health" care related, civil "services" (e.g. administrative or police), "at_home" or "other")
- freetime - free time after school (numeric: from 1 - very low to 5 - very high)
- goout - going out with friends (numeric: from 1 - very low to 5 - very high)
- guardian - student's guardian (nominal: "mother", "father" or "other")
- health - current health status (numeric: from 1 - very bad to 5 - very good)
- higher - wants to take higher education (binary: yes or no)
- internet - Internet access at home (binary: yes or no)
- Medu - mother's education (numeric: 0 - none, 1 - primary education (4th grade), 2 – 5th to 9th grade, 3 – secondary education or 4 – higher education)
- Mjob - mother's job (nominal: "teacher", "health" care related, civil "services" (e.g. administrative or police), "at_home" or "other")
- nursery - attended nursery school (binary: yes or no)
- paid - extra paid classes within the course subject (Math or Portuguese) (binary: yes or no)
- passed - did the student pass the final exam (binary: yes or no)
- Pstatus - parent's cohabitation status (binary: "T" - living together or "A" - apart)
- reason - reason to choose this school (nominal: close to "home", school "reputation", "course" preference or "other")
- romantic - with a romantic relationship (binary: yes or no)
- school - student's school (binary: "GP" or "MS")
- schoolsup - extra educational support (binary: yes or no)
- sex - student's sex (binary: "F" - female or "M" - male)
- studytime - weekly study time (numeric: 1 - <2 hours, 2 - 2 to 5 hours, 3 - 5 to 10 hours, or 4 - >10 hours)
- traveltime - home to school travel time (numeric: 1 - <15 min., 2 - 15 to 30 min., 3 - 30 min. to 1 hour, or 4 - >1 hour)
- Walc - weekend alcohol consumption (numeric: from 1 - very low to 5 - very high)