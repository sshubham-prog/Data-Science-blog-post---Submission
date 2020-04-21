## Project Motivation<a name="motivation"></a>

For this project, I was interestested in using Seattle and Boston AirBnB data to better understand:

1. The drivers of listing prices on AirBnB based on their properties
2. Identify positive and negative reviews of users from their text reviews
3. key factors that determines user experience during their stay?


## File Descriptions <a name="files"></a>

I have shared a jupyter notebook answering each of these questions step by step with detailed EDA and CRISP-DM analysis.  Markdown cells were used to assist in walking through the thought process for individual steps. 

## Python package used <a name="files"></a>

This project is executed in a Jupyter Notebook with the help of below packages

1. Numpy
2. Pandas
3. Matplotlib
4. Seaborn
5. XGBoost
6. nltk
7. BayesianOptimization

## Conclusion <a name="files"></a>
1. Model results suggest that factors hypothesized have influence the price: no of bedrooms, bathrooms, bedrooms, and accommodates.
2. Sentiment analysis using nltk works best in most of the cases but fails to get context and hence bi-grams or n-grams failes to get tagged with right sentiment
3. Host related attributes plays a major role in determing the customer experience. Followed by geographical location and locality.

## Results<a name="results"></a>

The main findings of the code can be found at the post available here.(https://medium.com/@satyam.shubham19/predicting-listing-prices-on-airbnb-using-ml-1f614bf711e3)

## Licensing, Acknowledgements<a name="licensing"></a>

Must give credit to Inside AirBnB for the data.  You can find the Licensing for the data and other descriptive information at the link available here. (http://insideairbnb.com/get-the-data.html).

