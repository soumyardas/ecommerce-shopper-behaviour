# Understand the online shopper purchasing pattern through Machine Learning

## Table of Contents
- [Project Overview](#project-overview)
- [Getting started immediately](#getting-started)
- [Datasets](#datasets)
- [Dependencies](#dependencies)
- [Workflow](#workflow)
- [Directory structure](#dirctory-structure)
- [Models](#models)
- [Contributors](#contributors)
- [License](#license)
- [Acknowledgments](#acknowledgments)
- [Contributions and Feedback](#contributions-and-feedback)

---

## [Project Overview](#project-overview)

### [Getting started immediately](#getting-started)

## [Datasets](#datasets)

## [Dependencies](#dependencies)

## [Workflow](#workflow)

To run this project locally, follow these steps:

### 1. Cloning the repository: 

### 2. **Setting up the environment:**

### 3. Running `notebooks/notebook.ipynb`

### 4. Training model

### 5. Making predictions

### 6. Containerizing the model

### 7. Deploying an AWS Elastic Beanstalk application

#### Details of application:

## [Models](#models)

We evaluated the performances of four different models. Their accuracies and ROC AUC are listed in the table below:

|Model                          | Accuracy 	| ROC_AUC 	|
|-----                          | -------- 	| ------- 	|
|LogisticRegression             | 0.792 	| 0.686 	|
|DecisionTreeClassifier         | 0.793 	| 0.725 	|
|RandomForestClassifier         | 0.793 	| 0.682 	|
|XGBClassifier                  | 0.796 	| 0.749 	|
|LGBMClassifier ✅              | 0.796   | 0.752   |

Our final model, LGBMClassifier, produced a score of **0.807** and an ROC AUC = **0.797**.

## [Directory structure](#dirctory-structure)

## [Contributors](#contributors)

## [License](#license)
This project is licensed under the [MIT License](./LICENSE).

## [Acknowledgments](#acknowledgments)
* [Alexey Grigorev](https://github.com/alexeygrigorev)
* [DataTalks.Club](https://datatalks.club/)

## [Contributions and Feedback](#contributions-and-feedback)

We welcome contributions from the community and feedback from healthcare professionals and data scientists. Together, we can refine our model and enhance its utility in real-world healthcare settings. Feel free to explore the project, contribute, or reach out with any questions or suggestions. Together, we can work towards a healthcare system that is more efficient, patient-centered, and cost-effective.
