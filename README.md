# Data_Extraction

## Objective

The objective of this assignment is to extract textual data articles from the given URL and perform text analysis to compute variables that are explained below. 

### Importing the Libraries

I have used following libraries to finish this project:-
1. Pandas to read Excel File(Input.xlsx)
2. Beautiful soup for Data extraction 
3. Regular Expression(re) to data filtering
4. Requests to extract text from HTML file
5. User Agent to read HTML file through Chrome browser
6. Date Time to convert date into datetime format
7. NLTK to tokenize words
8. WordNet Lemmatizer to lemmatize the text
9. Glob to return all file paths that match a specific pattern
10. OS to extract text from text file

## Data Study
	
Reading the Excel files using pandas and finding out the datatypes of the variables in the dataset.

## Data Manipulation

I have performed a function to see if all the URLs in the list are working or not and given a label for all of them. After that I have separated the URLs that are not working. Then I used the Beautiful Soup library to read all the URLs in the list and extracted the text and the date when it was published on the website.

## Data Extraction

I have performed a function to extract title and text from the website monthwise and saved each file with the name of their URL in the Output Folder inside the Assignment Folder. After that I have appended the whole text in each dataframe against each URL. At last I have added all the dataframes from all months to form a single dataframe.

## Textual Analysis
	
In Textual Analysis Firstly I performed Data Cleaning by removing numerical data from text. After that I have filtered the text by removing stop words and punctuation using nltk and string library. Then I have tokenized the text using nltk.word tokenize and lemmatization using WordNet Lemmatizer.

### Creating Dictionary of Positive and Negative Words

I have extracted all the positive and negative words from the Master Dictionary in different variables.

### Extracting Derived Variables
	
Finding out all the variables

- POSITIVE SCORE
- NEGATIVE SCORE
- POLARITY SCORE
- SUBJECTIVITY SCORE
- AVG SENTENCE LENGTH
- PERCENTAGE OF COMPLEX WORDS
- FOG INDEX
- AVG NUMBER OF WORDS PER SENTENCE
- COMPLEX WORD COUNT
- WORD COUNT
- SYLLABLE PER WORD
- PERSONAL PRONOUNS
- AVG WORD LENGTH

### Writing dataframe into Excel file

Finally writing all the values in an Excel file named Output Data Structure.xlsx
