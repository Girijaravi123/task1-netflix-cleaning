Task 1 – Netflix Dataset Cleaning (Data Analyst Internship)

This is my submission for Task 1 of the data analyst internship. I worked on cleaning the Netflix Movies and TV Shows dataset using Python and Pandas in Google Colab.

Tools Used:
- Google Colab (for writing and running code)
- Python (main language)
- Pandas (for data handling)
- GitHub (to upload and share the project)

Dataset Used:
I used the Netflix Movies and TV Shows dataset from [Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows). It contains information about TV shows and movies available on Netflix.

What I Did:
As a beginner, I followed simple but important steps to clean the data:

- Checked for missing values
- Filled missing data in:
  - `director` → with `'Unknown'`
  - `cast` → with `'Not Available'`
  - `country` → with `'Unknown'`
- Converted the `date_added` column to proper date format
- Removed duplicate rows
- Renamed column headers to lowercase and used underscores (for consistency)
- Saved the cleaned dataset as a new CSV file

Files in this Project
- `task1.ipynb` – My notebook with all the Python code
- `netflix_cleaned.csv` – The final cleaned dataset

Final Output:
The dataset is now clean and ready for analysis. I learned how to use Pandas for real-world data cleaning, and how to organize my work on GitHub.

