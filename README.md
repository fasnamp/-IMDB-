# 🎬 IMDb Movie Data Analysis using SQL

## 📌 Project Overview
This project presents an SQL-based analysis of an IMDb-style movie dataset. The analysis focuses on exploring relationships between **movies, actors, directors, genres, and roles** to extract useful insights from the data.

Through a series of analytical SQL queries, the project demonstrates practical skills in **data exploration, relational database querying, and insight generation using SQL**.

---

## 🗄️ Database Structure
The dataset is organized into multiple relational tables:

### `actors`
- `first_name`
- `last_name`
- `gender`

### `directors`
- `first_name`
- `last_name`

### `directors_genres`
- Connects **directors** with the **genres** they work in.

### `movies`
- `movie_name`
- `release_year`
- `rank_score`
- Additional movie-related attributes.

### `movies_directors`
- Establishes the relationship between **movies** and **directors**.

### `movies_genres`
- Links **movies** with their respective **genres**.

### `roles`
- Maps **actors to movies** along with their **role names**.

---

## 📊 SQL Analysis Performed
The project includes **15 analytical SQL queries** to explore the dataset:

1. Retrieve details of all actors  
2. Count the number of movies directed by each director  
3. Find movies released after the year 2000  
4. Identify the top 5 movies based on rank score  
5. Compare the number of male and female actors  
6. Find actors who played the role **"Demon"**  
7. List genres of the movie with `movie_id = 1`  
8. Find movies directed by **Anthony Abrams**  
9. Count the number of movies in each genre  
10. Identify the top 5 directors by average movie rank  
11. Find directors who worked across multiple genres  
12. Identify actors who appeared in **Action genre** movies  
13. Find actors who acted in more than **5 movies**  
14. Display movies along with their directors and genres  
15. Identify the genre with the **highest number of directors**

---

## 🛠️ Tools & Technologies
- **Database:** MySQL  
- **Tool Used:** MySQL Workbench  
- **Dataset:** IMDb-style relational movie dataset  

---

## 📚 Key Skills Demonstrated
- Writing structured and efficient **SQL queries**
- Working with **multi-table joins**
- Using **aggregation functions** (`COUNT`, `AVG`)
- Data filtering with **GROUP BY** and **HAVING**
- Applying **subqueries and ranking logic**
- Extracting meaningful insights from datasets

---

## 🤝 Connect With Me
Feel free to explore the project and share your feedback!
