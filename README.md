Project Title:
Movie Ratings and Genre Analysis

Introduction:
This project is a Streamlit-based interactive dashboard designed to provide insights into movie ratings and genre data.Its core functionality is Interactive Filters, KPIs, Visualizations,it solves problems such as Data Exploration,Trend Analysis,Informed Decision-Making.

Project Type:
Streamlit Web Application

Deplolyed App:
Streamlit Web Application : https://b41da011data-wranglers-nseipynchzd62dbeomehe7.streamlit.app/

Video Walkthrough of the project:
Attach a very short video walkthough of all of the features [ 1 - 3 minutes ]

Video Walkthrough of the codebase:
https://b41da011data-wranglers-nseipynchzd62dbeomehe7.streamlit.app/

Key features of the application:

- Interactive Filters:Filters help in narrowing down the dataset for focused analysis.
- Key Performance Indicators:Provides quick insights into the overall performance of movies and genres.
- Customizable View:Users can customize the dashboard layout to focus on specific data points or areas of interest.

design decisions or assumptions:

Streamlit: Used as the core framework to create an interactive web app with minimal coding.
The dataset is assumed to be clean, or it has been pre-processed before use. This includes ensuring that missing values in critical columns are handled.


Installation & Getting started:

```bash
pip install streamlit pandas plotly matplotlib seaborn
streamlit run app.py
```
Usage

Starting the Application
After successfully installing the required dependencies and preparing the dataset, navigate to the project directory and run the app.
bash
cd movie-data-visualization
streamlit run app.py
Once the app is running, you will see several interactive filters on the sidebar. You can adjust these filters to explore different subsets of the movie dataset.
- Adjust the 'Release Year' slider to explore movies released.
- Click the 'Genre' dropdown and select multiple genres to view movies only in those categories.
- Adjust the 'Rating' slider to include only movies with a rating.
Once the filters are applied, the app will automatically update and display Key Performance Indicators and visualizations.

APIs Used:

https://www.kaggle.com/datasets/narayan63/netflix-popular-movies-dataset

Technology Stack

- Streamlit
- Python
- Pandas
- Matplotlib
- Seaborn
- Plotly

