# British Airways Passenger Reviews/Sentiment Analysis

## Project Overview:
This project analyzes customer reviews for British Airways (BA) to gain insights into passenger experiences. It includes:
* ✔ Exploratory Data Analysis (EDA) – Data Cleaning, Visualization & Trend Analysis.
* ✔ Sentiment Analysis – Classifying reviews as Positive, Negative, or Neutral.


## 📊 Dataset Description
Dataset: BA_reviews.csv

* Total Number Of Records: 1000
* Records after Cleaning Data: 993
* Columns Description:
    * `Review_Title`: The review title written by each customer which conveys the main/major issue or their views on customer service at British Airways.
    * `Review_Date`: The date when the customer wrote the review on services.
    * `Type_of_Traveller`: There are 4 types of travellers using BA, like Couple Leisure, Solo Leisure, Business, Family Leisure.
    * `Seat_Type`: There are 4 types of Seat Types, i.e Economy Class, Business Class, Premium Economy, First Class
    * `Route`: This column tells us the route taken by the customer for their respective reviews given for that flight.
    * `Date_Flown`: The date when the customer had his/her flight date.
    * `Seat_Comfort`: This column tells the rating out of 5, given by the customer on comfort level of the seat.
    * `Cabin_Staff_Service`: This col tells the rating(out of 5) for the cabin staff service of that particular flight.
    * `Ground_Service`: Rating(out of 5) for the ground services at the airport. These services include loading and unloading baggage and cargo, aircraft maintenance, and passenger services.
    * `Value_For_Money`: Rating(out of 5) tells if the customer thinks the BA flight is value for money or not.
    * `Recommended`: This col tells if the customer recommends the services of BA or not(represented by 0 for 'Not Recommened' and 1 for 'Recommended'.)


## Features
- **Data Cleaning & Preprocessing**
- **Missing Value Handling**
- **Outlier Detection & Treatment**
- **Correlation Analysis**
- **Feature Engineering**
- **Sentiment Classification (Positive, Neutral, Negative)**

## Technologies Used
- **Python**
- **Pandas & NumPy**
- **Matplotlib & Seaborn**
- **Scikit-learn**
- **NLTK/TextBlob (for sentiment analysis)**

## Installation
To run this project, install the required dependencies using:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn nltk 
```

## Results
### **Exploratory Data Analysis (EDA) Insights**
#### **Data Overview:**
- The dataset contains multiple columns with structured data.
- Identified numerical and categorical features.

#### **Missing Values:**
- Some columns have missing values, handled via imputation or removal.

#### **Data Distribution:**
- Visualized distributions of numerical columns using histograms.
- Categorical data analyzed with bar plots to understand value frequencies.

#### **Correlation Analysis:**
- Heatmaps and correlation matrices used to find relationships between variables.
- Strong correlations noted between certain features, indicating potential multicollinearity.

#### **Outlier Detection:**
- Boxplots and IQR methods used to identify outliers.
- Decision made whether to remove or retain outliers based on domain relevance.

#### **Feature Engineering:**
- Created new features based on domain knowledge to enhance model performance.
- Converted categorical variables using encoding techniques.

### **Sentiment Analysis Insights**
#### **Sentiment Distribution:**
- The dataset was analyzed for sentiment (positive, negative, neutral).
- Majority of sentiments were found to be **[insert majority sentiment]**.

## Contributing
Feel free to raise issues or contribute enhancements by submitting a pull request.

## License
This project is licensed under **[MIT License]**.