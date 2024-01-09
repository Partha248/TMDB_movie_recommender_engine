# TMDB Movie Recommender Engine
## Overview
   This is a simple movie recommendation engine built using the TMDB (The Movie Database) API. 
   The recommendation system suggests movies based on user input and preferences.

## Features
  Input: Users can select a movie from the provided list.
  Output: The system recommends similar movies based on user choices.
#### TMDB API: The engine leverages the TMDB API to fetch movie details and recommendations.
## How to Use
  #### Step 1: Download the Project
       Download the project by clicking the "Code" button and selecting "Download ZIP" from this repository.
#### Step 2: Unzip Files
       Unzip the downloaded file. Ensure both the .ipynb and .py files are in the same folder.
#### Step 3: Open in Code Editor
       Open the folder in a code editor like VS Code or PyCharm.
#### Step 4: Install Required Libraries
      Make sure you have the necessary libraries installed. Run the following command in your cmd terminal 
      ' pip install numpy pandas sklearn nltk pickle streamlit requests '
#### Step 5: Run Jupyter Notebook
      Run the .ipynb file using Jupyter Notebook. It will create two pickle files: 
      "movies_df_to_dict.pkl" and "similarity_obj.pkl" in the same folder.
#### Step 6: Run the Web App
      Open a new terminal and navigate to the project folder.
      Run the following command : 'streamlit run web_app.py'
      Wait for 30 to 50 seconds. Streamlit will provide a local host link. 
      Click on the link to open the app in your browser.
#### Step 7: Explore Recommendations
    The Streamlit web app is now in front of you. 
    Choose a movie, and the app will provide recommendations based on your selection.


### Visit Steamlit Web App http://localhost:8501 in your web browser.
    1.Select a Movie:
    2.Choose a movie from the dropdown menu.
    3.Click the "Recommend" button to see a list of similar movies.
#### Tech Stack : Python | Streamlit | TMDB API


#### Acknowledgments
**This project is powered by the TMDB API.**
**Special thanks to Streamlit for making web app development easy and fun!**
