# datafun-07-applied
Project 7: Apply Supervised Machine Learning - Simple Linear Regression

## Project Purpose

The purpose of this project is to implement the guided projects outlined in sections 10.16 and 15.4 of the textbook "Intro to Python for Computer Science and Data Science: Learning to Program with AI, Big Data and the Cloud."

### Overview

The project involves employing a type of supervised machine learning, simple linear regression, to train a model using all available data. The resulting model, represented by a "best-fit" straight line, is then used to make predictions.

#### Project Requirements

- Build a model
- Make predictions
- Visualize the model
- Publish insights

### Project Structure & Deliverables

- **datafun-07-applied**: Project repository
- **README.md**: Provides an overview of the project and instructions for setting up and executing the environment.
- **requirements.txt**: Lists all packages required for the project.
- **examples files**: Contains all associated textbook materials to perform the project.
- **tmontague_ml.ipynb**: Jupyter Notebook file

### Environment Setup & How to Install and Run the Project

1. Create a new GitHub repository named `datafun-07-applied` with a default `README.md`.
2. Clone the repository to your local machine.

#### Clone the repository from the specified URL
git clone https://www.your-repository.com

#### Create a Project Virtual Environment in the .venv folder
# Activate the Project Virtual Environment



py -m venv .venv
.\.venv\Scripts\Activate.ps1
Install dependencies into your .venv and freeze into your requirements.txt.
bash

pip install -r requirements.txt
Add a useful .gitignore to the root project folder with .vsode/ and .venv/ to prevent adding to the repository.
Git add, commit, and push to GitHub.
bash


git add .
git commit -m "initial commit"
git push origin main
Project Organization & Data Files
Access and download associated files and data from IntroToPython/examples.
Create examples subfolder in the root project repository folder: datafun-07-applied.
Add downloaded associated files and data to the examples subfolder.
Start the Project
Open datafun-07-applied root project repository in VS code.
Open a terminal in your root project repository folder and run git pull to make sure you have the latest changes from GitHub.
Create a new notebook in the root project repository named: tmontague_ml.ipynb.
Add a Markdown cell at the top of the new notebook with Title, Author, and clickable link to the project repository.
Add Python cell with import statements.
python


import matplotlib
from matplotlib import pyplot as plt
import pandas
import pyarrow
import scipy
from scipy import stats
import seaborn as sns
import sklearn
from sklearn.model_selection import train_test_split
import numpy as np
Analysis Workflow
CC 7.5: Chart a Straight Line (Part 1)
Complete section per Project 7 requirements.

CC 7.6: Predict Avg High Temp in NYC in January (Part 2)
Complete section per Project 7 requirements for Object-Oriented Programming.

Build a model
Make predictions
Visualize the model
CC 7.7: Predict Avg High Temp in NYC in January (Part 3)
Complete section per Project 7 requirements for Supervised Machine Learning.

Build a model
Make predictions
Visualize the model
CC 7.8: Insights (Part 4)
Complete section per Project 7 requirements.

Publish insights
Optional Bonus (Part 5)
Complete section per Project 7 requirements.

Loading the data
Training and testing the data
Visualizing the data
Choosing the best model from the 4 listed
Contributing
We welcome contributions to this project. If you have suggestions to improve the analysis or encounter issues, please open an issue or submit a pull request.

References & Acknowledgments
Guided projects in 10.16 and 15.4 of the textbook: "Intro to Python for Computer Science and Data Science: Learning to Program with AI, Big Data and the Cloud."

Special thanks to OpenAI for assistance with project design and coding structure.

Additional references used for this project include:

JUPYTER.md for Jupyter Notebook keyboard shortcuts and recommendations.
MARKDOWN.md for Markdown syntax and recommendations.
Data Visualization using Python, Matplotlib and Seaborn for visualization project ideas.
Seaborn Tutorial for assistance with plotting functions.
Linear Regression in Python using Jupyter Notebooks! to create forecasting projections.
3D Scatter Plots in Python to create 3D scatter plots.
