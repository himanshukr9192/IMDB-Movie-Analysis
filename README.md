# IMDB-Movie-Analysis
Dataset having various columns of different IMDB Movies with 5 Whys Analysis . 

Cleaning the data:: This is one of the most important step to perform before moving forward with the analysis (Dropping columns, removing null values, etc.)
Task: Clean the data

Movies with highest profit: New column called profit which contains the difference of the two columns: gross and budget. Sorting the column using the profit column as reference. Plot profit (y-axis) vs budget (x- axis) and observe the outliers using the appropriate chart type.
Task: Find the movies with the highest profit?

Top 250: New column IMDb_Top_250 and store the top 250 movies with the highest IMDb Rating (corresponding to the column: imdb_score). The num_voted_users is greater than 25,000. Also add a Rank column containing the values 1 to 250 indicating the ranks of the corresponding films.
The movies in the IMDb_Top_250 column which are not in the English language and store them in a new column named Top_Foreign_Lang_Film. You can use your own imagination also!
Task: Find IMDB Top 250

Best Directors: TGrouped the column using the director_name column.
The top 10 directors for whom the mean of imdb_score is the highest and stored them in a new column top10director. In case of a tie in IMDb score between two directors, sorted them alphabetically.
Task: Find the best directors

Popular Genres: Performed this step using the knowledge gained while performing previous steps.
Task: Find popular genres

Charts: Created three new columns namely, Meryl_Streep, Leo_Caprio, and Brad_Pitt which containing the movies in which the actors: 'Meryl Streep', 'Leonardo DiCaprio', and 'Brad Pitt' are the lead actors. Use only the actor_1_name column for extraction. Also, make sure that you use the names 'Meryl Streep', 'Leonardo DiCaprio', and 'Brad Pitt' for the said extraction.
Appending the rows of all these columns and store them in a new column named Combined.
Grouped the combined column using the actor_1_name column.
Finding the mean of the num_critic_for_reviews and num_users_for_review and identify the actors which have the highest mean.
Observed the change in number of voted users over decades using a bar chart. Create a column called decade which represents the decade to which every movie belongs to.  Stored this in a new data frame called df_by_decade.
Task: Find the critic-favorite and audience-favorite actors


