# Word-2-Vec
I created a word2 vec model that takes in a job title and outputs a list of requirements related to that position, it helps the recruiters and the job searchers to be aware of the recent tools and technologies required in the market for different positions
* We Scraped around 1200+ jobs applications and extracted the Description column as a seperate text
* Conducted a NLP preprocessing techniques on the text data
* Finally applied the word2vec model and got an accurate results as outcome

# Preprocessing
For preprocessing i have conducted the following:

* I have Removed newlines & Tabs , white spaces from strings , all the special characters 
* Lower cased all the rows in the data
* Adjusted punctuation
* Removed stop words
* generated bigrams in the data

# Result
Finally i reached the below results

<img width="904" alt="Word 2vec results" src="https://user-images.githubusercontent.com/67180181/142373913-78a64135-8d98-4fdc-b14a-964c734c05bc.png">
