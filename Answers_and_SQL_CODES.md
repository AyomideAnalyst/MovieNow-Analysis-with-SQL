## ANSWERS
These are the SQL CODES written to answer the questions.
1. What is the total number of unique customers and distinct countries?
  ```sql
SELECT COUNT(DISTINCT customer_id) as total_customers,
        COUNT(DISTINCT country) AS total_countries
FROM movies.customers
```

2. What is the total number of movies and distinct genres movies are listed in?
```sql
SELECT COUNT(DISTINCT movie_id) AS total_movies,
   COUNT(DISTINCT genre) AS total_genre
FROM movies.movies
```
4. What is the total revenue MovieNow has generated?
5. What is the average, minimum and maximum renting price of movies available on MovieNow?
6. What is the average renting price by genre and how it compares to the overall average renting price of $2.21?.
7. Does renting price affect how movies are rented?

#### _Does rating affect how movies are rented?_
7. What is the average, minimum and maximum rating of all movies?
8. Which movie title(s) has a rating of 1?
9. Which movies have a perfect rating of 10?
10. Identify the top 10 movies with the most rentals and their average rating.
11. Do movies with the rating score of 10 have more rentals?

#### _Who are the customers of MovieNow?_
12. Who are our customers and where do they come from?
13. If MovieNow decides to reward it highest paying customer. Who would that customer be and what country would that customer be residing?.
14. Which country brings in the most revenue?
15. Which genre brings in the most revenue?
