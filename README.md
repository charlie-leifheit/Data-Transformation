# Data-Transformation
Taking the raw scraped data from TripAdvisor and transforming it to output the specific words per park and by year.

Dependencies:
1. google.colab drive
2. matplotlib
3. numpy
4. seaborn
5. pandas

Steps:
1. Get raw data from web scraper 
2. Put data into Pandas dataframe
3. Understand how long is reviews dataset by creating visualization of bar chart. 
4. Create two independent dataframes one for "review_title" and another for "review_body".
5. Using Spacy, generate tokens from text as well as get parts of speech of words.
6. Filter out stop words, punctuation, characters, and words less than 3 characters if not caught by stop words.
7. Count all unique words and return them grouped by park and year for further analysis.
