# Popular-movies-analysis
**Data science project**
This is individual project that requires work with a dataset to produce a series of data preparation, visualizations and analysis using Python.

**Parts of the project**
  1. Dataset - firstly you need to select dataset of your interest, it can be any dataset from the web.
  2. Introduction - give some background information about your project and dataset. Describe briefly what you want to do in your analysis.
  3. Data description - provide information about your dataset, size of it, and description of the columns.
  4. Research questions - create at least 5 interseting questions that you will need to answer using data visualisation. Note that questions should not be similar.
  5. Data prepartion - cleaning, shaping, manipulation with the data that you have.
  6. Data Analysis and Visualisation - you need to answer questions you prepared using different charts.\
  7. Conclusion - write conclusion for all of your findings.
  8. Data modelling - if you want you can apply some Machine Learning model to your data. It should be proper application (for bonus points).
  9. Defense - during the final exam weeks you will need to defense your project in front of your lecturer/practice teacher.

**Project data examples**
Proper datasets from https://www.kaggle.com/datasets
Financial datasets from https://quandl.com
Yelp academic dataset https://www.yelp.com/dataset
MovieLens dataset from https://grouplens.org/datasets/movielens/
others sources will be fine as long as dataset is good
**1. Introduction**
My project is about popular movies around the world, so I've chosen the dataset from kaggle, Top 10.000 Popular Movies(link: https://www.kaggle.com/omkarborikar/top-10000-popular-movies). In my project, I would like to know the most popular movies in different languages, popular movies of every decades, popular and non-popular genres, dependence of columns between each other, and I would like to do this using pandas, numpy, seaborn and matplotlib libraries.

**2. Data description**
My dataset is about 10.000 popular movies. This dataset has 10.000 rows and 9 columns(id,original_language,original_title,popularity,release_date,vote_average,vote_count,genre,overview). Very important columns for me are id, original_language, popularity, release_date and vote_average, vote_count and genre. I think only two columns are not clear, so vote_average is column of critics' average vote, and vote_count is in total, how many votes for any movie.

**3. Research question**
1)Plot a barchart of count of films for every language

2)Find outliers for vote counts.

3)Plot two barcharts in the same figure. For one of them get number of vote_average, and for another get vote_count.

4)Find the correlation between popularity, vote_count and vote_average

5)Find the most popular movies by their language and find popular movies of every decade of 21st century. Plot it into two barcharts

6)Find less popular movies of every decade in 20th century

7)Find out in which month movies are most often released

8)Count the number of genres and plot it

9)Find the most popular movie of 'Comedy' genre of every language

All next steps you can see by running code
