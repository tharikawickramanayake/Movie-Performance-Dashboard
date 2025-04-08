# Movie-Performance-Dashboard
Movie Performance Dashboard built with Power BI using SQL data. Includes insights on box office revenue, Oscar wins, movie studios, and more — all powered by tables like Actor, Film, Director, Genre, and Studio. Great for understanding patterns in movie success.
# 🎬 Movie Performance Dashboard (SQL-Powered) 🍿

This Power BI project analyzes movie performance using data imported from a structured SQL database. The dashboard focuses on key movie metrics such as box office revenue, Oscar wins, genres, and film studios. This project demonstrates advanced data modeling, Power BI relationships, and DAX calculations.

---

## 🗂️ Database Structure

The project connects to a relational database called `Movies` containing the following tables:

- `Actor`: Actor ID, Name, Birth Year, etc.
- `Certificate`: Film certifications (e.g., PG, R)
- `Country`: Country of production
- `Director`: Director names and metadata
- `Film`: Main fact table with movie details and foreign keys
- `Genre`: Movie genres
- `Language`: Primary spoken language
- `Role`: Roles played by actors in films
- `Studio`: Movie production studios

These tables are linked using foreign keys and normalized to follow best practices in database design.

---

## Dashboard Features

- 🎟️ Box Office Revenue by Movie Title
- 🏆 Oscar Wins and Nominations by Film
- 🎬 Genre and Studio Breakdown
- 🎭 Actor and Director-based Performance Metrics
- 📊 Filterable by Title, Studio, Year, and FullName (lead contributor)

---

##  Tools & Technologies

- **SQL Server Management Studio (SSMS)** – for database creation and querying  
- **Power BI Desktop** – for visualization and modeling  
- **Power Query** – to load and transform SQL data  
- **DAX** – for calculated fields and KPIs

---

##  Key Insights

- Titanic and Avatar top the box office earnings
- Studios like 20th Century Fox dominate in awards and revenue
- Certain directors consistently produce high-performing films
- Genre has a major impact on average box office value

---

##  Files Included

- `MovieDashboard.pbix` – Power BI dashboard file
- `dashboard-screenshot.png` – image preview of the dashboard
- (Optional) `SQL Scripts/` – folder containing SQL table creation scripts or queries

---

## 🖼Dashboard Preview

![Dashboard Screenshot](![Movie Perfomance Dashboard](https://github.com/user-attachments/assets/4a393b2e-344d-42ad-9f48-99d043d67f11)
)
