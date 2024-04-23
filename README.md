#  Analyzing Movie Dataset

## 1. Background
The goal of this project is to analyze the movie dataset that has more than 10000 movies starting from 1960 to 2015. The dataset has a wide range of data available,
but to do the analysis the ones that weren't needed were dropped. The analysis was done to answer few questions regarding the runtime, casting, production companies and budget of the movie.
Along with the questions, details of the dataset, the result of the of analysis and the file details were also provided.



## 2. Question
  a. Which year has seen more investment year to year?
  
  b. What is the average profit made each year?

  c. What is the highest number of movies made by a single production house?
   
  d. Which actors have cast in most movies?

  e. Does movie runtime affect the revenue of a movie?

  f. What is the average movie runtime of each year?

## 3. Dataset

The dataset was collected from Keggle.com. It consists of 21 columns. For the sake of the analysis, the dataset was trimmed to 11 columns which include:

a) Budget: The column contains the budget of each movie produced and the variable type is integer.

b) Revenue: The column contains the value of revenue each movie has generated. The variable type of this column is integer.

c) Cast: Cast column consists of all the actors or actresses names who have been cast in the movies. The data type is object since they are names.

d) Director: The column consists of the names of the directors, of respective movies. Like the Cast column datatype, this one too is object data type.

e) Runtime: Runtime column indicates the total length of the movies. The datatype is integer in this column.

f) Genres: The genre column is an objective datatype in this dataset and it contains genres of different movies.

g) Production_companies: This column consists of names the production companies and the data are object-type variables as well.

h) Vote_count: Vote_count field has the number of reviews each movie has received and the data type is integer.

i) Vote_average: The column has the average rating of each movie and it has a float data type.

j) Release_year: This particular column has the release year data of every movie of the dataset and the datatype of this column is integer.

## 4. Results
Upon analysis, the project will provide insights into the investment trends in the movie industry, average profits over the years, prolific production houses and actors, 
the impact of movie runtime on revenue, and the average movie runtime for each year.

## 5. Files

i) Movie.csv: Contains the data on which the analysis was done.

ii)movie.ipynb: Contains the python code that was used to do the analysis.
