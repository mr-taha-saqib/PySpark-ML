# Movie and Wine Dataset Analysis

This project involves analyzing the provided `Movies.csv` dataset, which contains information about various aspects of movies, and performing clustering on the Wine dataset. The tasks include data exploration, querying specific details from the movie dataset, and implementing clustering algorithms.

---

## Project Tasks

### **Movie Dataset (Movies.csv)**
1. **Explore the Dataset**  
   Perform an initial exploration of the dataset to understand its structure, content, and any potential data quality issues.

2. **Action Films Winning Awards**  
   Find the title, year, and director of action films that won an award.

3. **Award-Winning Actors' Movies**  
   For each award-winning actor, find the movies they acted in. Print the names of the movies along with the director of each movie.

4. **Top 10 Most Popular Non-Award-Winning Movies**  
   Identify the top 10 most popular movies that did not win an award.

5. **10 Least Popular Pre-1980 Movies**  
   Find the 10 least popular movies that were released before 1980.

6. **Sorting Movies Released Before 1990**  
   Sort the list of movies released before 1990 by their titles.

---

### **Clustering Analysis**
1. **PySpark Built-In Clustering**  
   - Use the PySpark built-in **K-Means** and **Bisecting K-Means** algorithms for clustering the movies dataset.

2. **Custom K-Means Implementation on Wine Dataset**  
   - Implement the K-Means algorithm using **RDDs** on the Wine dataset (provided in the previous lab).
   - Use the Wine dataset for this task.

---

## Dataset Details
- **Movies.csv**  
  Contains information about movies such as title, year, director, genre, popularity, award status, and other relevant attributes.

- **Wine Dataset**  
  Provided in a previous lab, this dataset contains attributes of different wine samples for clustering tasks.

---

## Requirements
- Python 3.x
- PySpark
- Pandas
- Wine dataset (from the previous lab)

---
