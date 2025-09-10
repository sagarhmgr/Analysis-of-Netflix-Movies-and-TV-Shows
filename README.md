# Analysis-of-Netflix-Movies-and-TV-Shows

In this project I spent some time exploring the Netflix Movies and TV Shows dataset (2019) from Kaggle. Using Python libraries like Pandas, Numpy, Matplotlib, and Seaborn, I cleaned the dataset, handled missing values, and created some visualizations to see what insights I could find.

Dataset at a glance

Total entries: 6,234

Columns: show type, title, country, release year, rating, duration, genre, etc.

First step was cleaning: I dropped columns I didn’t need (director, cast, date_added), then filled missing values in:

country → defaulted to United States

rating → filled with TV-MA (most common rating)

What I Found
1. Ratings Distribution

Most shows and movies are rated TV-MA, followed by TV-14 and TV-PG.
Netflix is definitely catering to a more mature audience.

2. Movies vs TV Shows

When comparing content types, Netflix has more movies than TV shows in its library.

3. Content by Country

The United States leads by a wide margin, followed by India and the United Kingdom.
It’s interesting to see how much of Netflix’s library still comes from just a handful of countries.

4. Top Ratings

The five most common ratings on Netflix are:

TV-MA

TV-14

TV-PG

R

TV-Y7

5. Genres

Top 5 genres: International Movies, Dramas, Comedies, Documentaries, Action & Adventure.

Least 5 genres: Stand-Up Comedy & Talk Shows, Music & Musicals, Classic TV, Cult Movies, LGBTQ Movies.

6. Release Years

The most content was released in 2018 (over 1,000 titles).
Other big years: 2017, 2019, 2016, and 2015.
Netflix’s big growth push was clearly in the mid-to-late 2010s.

Quick Takeaways

Netflix = more movies than shows.

Heavily dominated by content from the US.

Audience focus: mature ratings like TV-MA and TV-14.

Big surge of new titles around 2015–2018.

🛠️ Tools I Used

Python (Pandas, Numpy) → cleaning & analysis

Matplotlib, Seaborn → charts & plots
