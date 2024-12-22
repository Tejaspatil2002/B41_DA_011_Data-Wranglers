<h1 align="center"> Movie Ratings and Genre Analysis </h1>


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

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Movie Ratings and Genre Analysis</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 20px;
        }
        h1, h2, h3 {
            color: #333;
        }
        ul {
            list-style-type: disc;
            margin-left: 20px;
        }
        a {
            color: #007BFF;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
        .code-block {
            background-color: #f9f9f9;
            padding: 10px;
            border-left: 4px solid #007BFF;
            font-family: monospace;
        }
    </style>
</head>
<body>
    <h1>Movie Ratings and Genre Analysis</h1>

    <div class="section">
        <h2>Introduction</h2>
        <p>This project is a Streamlit-based interactive dashboard designed to provide insights into movie ratings and genre data. Its core functionality includes:</p>
        <ul>
            <li>Interactive Filters</li>
            <li>Key Performance Indicators (KPIs)</li>
            <li>Visualizations</li>
        </ul>
        <p>It solves problems such as:</p>
        <ul>
            <li>Data Exploration</li>
            <li>Trend Analysis</li>
            <li>Informed Decision-Making</li>
        </ul>
    </div>

    <div class="section">
        <h2>Project Type</h2>
        <p><strong>Streamlit Web Application</strong></p>
    </div>

    <div class="section">
        <h2>Deployed App</h2>
        <p><a href="https://b41da011data-wranglers-nseipynchzd62dbeomehe7.streamlit.app/" target="_blank">Streamlit Web Application</a></p>
    </div>

    <div class="section">
        <h2>Video Walkthrough</h2>
        <ul>
            <li><strong>Project Walkthrough:</strong> Attach a very short video walkthrough of all features (1-3 minutes).</li>
            <li><strong>Codebase Walkthrough:</strong> <a href="https://b41da011data-wranglers-nseipynchzd62dbeomehe7.streamlit.app/" target="_blank">Click here to view</a></li>
        </ul>
    </div>

    <div class="section">
        <h2>Key Features of the Application</h2>
        <ul>
            <li><strong>Interactive Filters:</strong> Filters help in narrowing down the dataset for focused analysis.</li>
            <li><strong>Key Performance Indicators:</strong> Provides quick insights into the overall performance of movies and genres.</li>
            <li><strong>Customizable View:</strong> Users can customize the dashboard layout to focus on specific data points or areas of interest.</li>
        </ul>
    </div>

    <div class="section">
        <h2>Design Decisions or Assumptions</h2>
        <ul>
            <li><strong>Streamlit:</strong> Used as the core framework to create an interactive web app with minimal coding.</li>
            <li>The dataset is assumed to be clean or pre-processed before use, including handling missing values in critical columns.</li>
        </ul>
    </div>

    <div class="section">
        <h2>Installation & Getting Started</h2>
        <div class="code-block">
            <p>pip install streamlit pandas plotly matplotlib seaborn</p>
            <p>streamlit run app.py</p>
        </div>
    </div>

    <div class="section">
        <h2>Usage</h2>
        <p><strong>Starting the Application:</strong></p>
        <p>After successfully installing the required dependencies and preparing the dataset, navigate to the project directory and run the app:</p>
        <div class="code-block">
            <p>cd movie-data-visualization</p>
            <p>streamlit run app.py</p>
        </div>
        <p>Once the app is running, you will see several interactive filters on the sidebar. You can adjust these filters to explore different subsets of the movie dataset:</p>
        <ul>
            <li>Adjust the 'Release Year' slider to explore movies released in specific years.</li>
            <li>Click the 'Genre' dropdown and select multiple genres to view movies only in those categories.</li>
            <li>Adjust the 'Rating' slider to include only movies with specific ratings.</li>
        </ul>
        <p>Once the filters are applied, the app will automatically update and display Key Performance Indicators and visualizations.</p>
    </div>

    <div class="section">
        <h2>APIs Used</h2>
        <p><a href="https://www.kaggle.com/datasets/narayan63/netflix-popular-movies-dataset" target="_blank">Netflix Popular Movies Dataset</a></p>
    </div>

    <div class="section">
        <h2>Technology Stack</h2>
        <ul>
            <li>Streamlit</li>
            <li>Python</li>
            <li>Pandas</li>
            <li>Matplotlib</li>
            <li>Seaborn</li>
            <li>Plotly</li>
        </ul>
    </div>
</body>
</html>
