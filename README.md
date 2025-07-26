This project uses the [Tokyo Airbnb Open Data](https://www.kaggle.com/datasets/tsarromanov/tokyo-airbnb-open-data) from Kaggle.

# Project description

For my machine learning course project, I have chosen the Tokyo Airbnb listings dataset from Kaggle. I picked this dataset because:

1. **Dataset structure**  
   The dataset contains CSV files including listings, calendar, reviews, and neighborhoods. Files hold flat tables with not overcomplicated data, allowing me to spend more time building models and less time on complex processing of unstructured data.

2. **Diverse data types and learning opportunities**  
   It includes numerical fields (e.g., price, adjusted price), categorical fields (e.g., neighborhood, room type), and geospatial information (e.g., longitude, latitude). With this dataset, I can practice a wide range of machine learning tasks. For example:
   - Use the listings data for price prediction (regression)
   - Apply neighborhood and room type for classification analysis
   - Utilize calendar data for time series forecasting
   - Perform sentiment analysis or text mining on reviews data
   - Conduct geospatial analysis using location information

3. **Real-world relevance**  
   Airbnb is a famous platform, and the data reflects real rental activity in Tokyo. By analyzing this dataset, I can learn how different factors such as location, room type, and reviews could affect price and popularity. This has clear applications in business and tourism. My analysis of factors influencing price or occupancy will have clear, practical applications.

4. **Manageable size**  
   Although the dataset includes four main files and two summary files, each file is not too large. The dataset is well separated, large enough to reveal interesting patterns but small enough for a beginner to run experiments on a regular laptop without requiring special hardware.

5. **Comprehensive learning experience**  
   Overall, the Tokyo Airbnb Open Data dataset is rich, practical, and flexible. It allows me to practice the full machine learning pipeline, including:
   - Data cleaning (there are missing values within the files)
   - Feature engineering
   - Regression
   - Classification
   - Clustering
   - Time series analysis
   - Text analysis

This makes it an excellent choice for my course project.

**Note**: Five CSV files except calendar.csv will be uploaded to github. calendar.csv's size is too large for it to be uploaded to Github.

## Local deployment guide

### Prerequisites

1. Python 3.9 or later
2. Git (optional)

### Installation guide

1. Clone the Repository: `git clone https://github.com/mengxin-huang/1163170.git` `cd 1163170`
2. After clone the repo, `ctrl + shift + P` in VS code -> select Pyhton: Create Environment -> select venv -> tick `requirements.txt` and install.
3. If there are missing requirements, run `pip install -r requirements.txt` to reinstall all the requirements.