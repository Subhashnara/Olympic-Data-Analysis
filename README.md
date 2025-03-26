# **Olympic Data Analysis Project**

This project analyzes and visualizes 120 years of Olympic history, from Athens 1896 to Rio 2016, using the "120 years of Olympic history: athletes and results" dataset from Kaggle.

**Data Source**

* The dataset was scraped from www.sports-reference.com in May 2018.
* It includes information on all Olympic Games from 1896 to 2016, covering both Summer and Winter Olympics.
* Dataset Link: [https://www.kaggle.com/datasets/heesoo37/120-years-of-olympic-history-athletes-and-results](https://www.kaggle.com/datasets/heesoo37/120-years-of-olympic-history-athletes-and-results)

**Description**

* This project analyzes and visualizes 120 years of Olympic history, from Athens 1896 to Rio 2016.
* The analysis includes categorization by countries and athletes, providing insights into Olympic trends and statistics over time.

**Important Note**

* The Winter and Summer Games were held in the same year up until 1992.
* After that, they were staggered with Winter Games occurring on a four-year cycle starting in 1994, followed by Summer Games in 1996, and so on.

**Features**

* **Overall Analysis:** Provides a general overview of the Olympic data.
* **Country-wise Analysis:** Examines medal distribution and performance by country.
* **Athlete Performance Analysis:** Focuses on individual athlete achievements.
* **Medal Tally Visualization:** Presents medal counts in graphical formats.
* **Historical Trends:** Identifies changes and patterns over time.

**Files**

* `app.py`: Main script for data analysis and visualization.
* `preprocessor.py`: Data cleaning and preparation script.
* `helper.py`: Functions for creating various charts and graphs.
* `requirements.txt`: List of required Python packages.

**Requirements**

* Python 3.x
* Pandas
* Matplotlib
* Seaborn
* NumPy

**Usage**

1.  Clone the repository.
2.  Install required libraries: `pip install -r requirements.txt`
3.  Run the main script: `python data_analysis.py`

**Results**

The analysis provides insights into:

* Medal distribution across countries.
* Performance trends of top athletes.
* Evolution of Olympic events over time.
* Gender participation trends.

**Future Work**

* Incorporate data from the Tokyo 2020 Olympics.
* Develop interactive visualizations.
* Perform predictive analysis for future Olympic performances.
