# IRIS-DATASET-ANALYSIS
# Iris Dataset Analysis and Predictive Model with RESTful API

This repository contains Python code for analyzing the famous Iris dataset as part of a college project. The project includes exploratory data analysis (EDA), implementation of Linear Discriminant Analysis (LDA) with visualizations, creation of a predictive model, and setting up a RESTful API for serving predictions.

## Project Structure

- **Notebooks:** Contains several Jupyter notebooks in PDF format:
  - `IRIS EXPLORATORY DATA ANALYSIS.pdf`: Detailed exploration of the Iris dataset with explanations.
  - `IRIS LINEAR DISCRIMINANT ANALYSIS.pdf`: Implementation of LDA for dimensionality reduction with visualizations.
  - `iris pred model.pdf`: Creation and pickling of a simple predictive model.
  - `RESTful API for iris model.pdf`: Python script implementing a RESTful API server using Flask.

- **Data:**
  - In-built sklearn iris dataset is used for analysis.

- **HTML Page:**
  - `irispred.html`: Basic HTML page for displaying results from the RESTful API.

## Contents

### Exploratory Data Analysis (EDA)
The exploratory data analysis (EDA) is thoroughly documented in `IRIS EXPLORATORY DATA ANALYSIS.pdf`. It covers:
- Dataset overview and statistics.
- Visualization of data distributions using plots (histograms, pair plots, etc.).
- Insights and observations drawn from the EDA process.

### Linear Discriminant Analysis (LDA)
LDA is implemented in `IRIS LINEAR DISCRIMINANT ANALYSIS.pdf`:
- Dimensionality reduction technique applied to the Iris dataset.
- Visualizations to demonstrate the reduced feature space.
- Explanation of how LDA aids in improving predictive performance.

### Predictive Model
A simple predictive model is built and pickled in `iris pred model.pdf`:
- Training and evaluation of the model using machine learning techniques.
- Model serialization using Python's pickle module for future use.

### RESTful API
The repository includes a RESTful API (`RESTful API for iris model.pdf`) for serving predictions:
- Built using Flask for simplicity and ease of use.
- Handles incoming requests, feeds data into the predictive model, and returns predictions.
- `irispred.html` provides a basic interface for users to interact with the API and display results.

## Usage
1. **Exploratory Data Analysis:** Review `IRIS EXPLORATORY DATA ANALYSIS.pdf` for insights into the Iris dataset.
2. **Linear Discriminant Analysis:** Check `IRIS LINEAR DISCRIMINANT ANALYSIS.pdf` for LDA implementation details.
3. **Predictive Model:** Refer to `iris pred model.pdf` to understand the predictive model and its usage.
4. **RESTful API:**
   - Run `RESTful API for iris model.pdf` to start the Flask server.
   - Open `irispred.html` in a browser to interact with the API and see predictions.

## Requirements
- Python 3.x

---

Feel free to explore the notebooks and scripts provided in this repository. If you have any questions or suggestions, please contact Abhimanyu Sharma at work.abhimanyu.sharma@gmail.com .
