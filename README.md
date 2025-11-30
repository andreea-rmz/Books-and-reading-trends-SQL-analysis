# Books-and-reading-trend-SQL-analysis (Sprint 14)
****************************************************************************************************************************************************************************************
Project Overview
****************************************************************************************************************************************************************************************

This project analyzes a relational database from a book-rating platform created during the post-COVID surge in digital reading. Using SQL, the objective was to explore book attributes, publishing trends, author performance, and user engagement to inform the value proposition of a new reading-related product.

The database contains five interconnected tables—books, authors, publishers, ratings, and reviews—providing a rich structure for multi-table joins and analytical queries.

Key Objectives:

1. Determine how many books were published after January 1st, 2000.
2. Calculate the number of user reviews and the average rating for each book.
3. Identify the publisher with the highest number of books with over 50 pages.
4. Determine which author has the highest average rating among books with ≥50 ratings.
5. Compute the average number of text reviews among users who rated more than 50 books.

Methodology:

Connected to a PostgreSQL database using SQLAlchemy and executed analytical SQL queries.
Performed table exploration, joins, aggregations, filtering, grouping, and windowing.
Ensured data consistency by validating publication dates, page counts, and rating volumes.

Results:

819 books were published after January 1st, 2000.
Several books reached a 5.0 average rating, while others received significantly lower scores.
Penguin Books is the top publisher of books over 50 pages (35 titles), dominating the modern publishing landscape.
Among authors with ≥50 ratings, Diana Gabaldon achieved the highest average rating (4.30).
Highly active users (50+ ratings) leave an average of 17 text reviews, signaling a small but influential core of power reviewers.
