# TMDB Movie Recommender Engine

## Overview
This is a simple movie recommendation engine built using the TMDB (The Movie Database) API. The recommendation system suggests movies based on user input and preferences.

## Features
- **Input:** Users can select a movie from the provided list.
- **Output:** The system recommends similar movies based on user choices.
- **TMDB API:** The engine leverages the TMDB API to fetch movie details and recommendations.

## How to Use
### Step 1: Download the Project
  - **Download the project by clicking the "Code" button and selecting "Download ZIP" from this repository.**

### Step 2: Unzip Files
  - **Unzip the downloaded file, then unzip the dataset file inside the unzipped folder. Ensure that the dataset, .ipynb, and .py files are all in the same folder.**

### Step 3: Open in Code Editor
  - **Open the folder in a code editor like VS Code or PyCharm.**

### Step 4: Install Required Libraries
  - **Make sure you have the necessary libraries installed. Run the following command in your cmd terminal:** 
   **'pip install numpy pandas sklearn nltk pickle streamlit requests'**

### Step 5: Run Jupyter Notebook
  - **Open the .ipynb file in a code editor and update the .csv file path to match the dataset's location on your PC.**
   **This ensures that the file can be read into a pandas dataframe.**
   **Run the .ipynb file using Jupyter Notebook. It will create two pickle files:**
   **"movies_df_to_dict.pkl" and "similarity_obj.pkl" in the same folder.**

### Step 6: Run the Web App
  - **Open a new terminal and navigate to the project folder. Run the following command : 'streamlit run web_app.py'**
   **Wait for 30 to 50 seconds. Streamlit will provide a local host link.**
   **Click on the link to open the app in your browser.**

### Step 7: Explore Recommendations
  - **The Streamlit web app is now in front of you.** 
   **Choose a movie, and the app will provide recommendations based on your selection.**

### Visit Streamlit Web App in your web browser.
   
   1. Choose a movie from the dropdown menu, or you can type it in the search bar.
   2. Click the "Recommend" button to see a list of similar movies.

## Tech Stack
- Python
- Streamlit
- TMDB API

## Acknowledgments
- This project is powered by the TMDB API.
- Special thanks to Streamlit for making web app development easy and fun! : )
