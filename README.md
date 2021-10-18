# Classification of _issues_ from _GitHub_ repositories

## Foundation

This project was developed during the course of measurement and experimentation laboratory in software engineering. In addition, the information has been translated and modified following this [repository](https://github.com/LucasRotsen/tcc_case_study_tasks).

### Introduction

<hr>

GitHub repositories have a space dedicated to _Issues_. _Issues_ are topics submitted by users and people who contribute to a repository, and serve to report issues found, ask questions, report vulnerabilities and so on.

An example we can look at is the issues page in the [React Repository](https://github.com/facebook/react/issues). Note that some _issues_ are labeled with a _label_ (example: 'Type: Bug'), however often this _label_ needs to be manually entered by the user submitting the _issue_. Since _issues_ are not correctly labeled, many of the _bugs_ reported by users and contributors are not identified by repository maintainers.

The aim of this project is to create a mechanism to identify whether a _issue_ reports a bug or not, so that in the future they can be automatically classified. In this way, the developers responsible for the repository will be able to more effectively filter reported bugs.

### Dataset

<hr>

To carry out the project, we will use a pre-processed sample of the dataset [GitHub Bugs Prediction](https://www.kaggle.com/anmolkumar/github-bugs-prediction/version/1),
made available on the community platform [Kaggle](https://www.kaggle.com/).

The dataset consists of three columns:

- **Title** - The title of the GitHub Issue
- **Body** - The GitHub Issue body
- **Label** - Represents the label of that issue (Bug; Feature; Question)
