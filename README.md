This project looks to understand the category of books readers enjoy the most and books frequently purchased.
# Data Scraping
The data was scraped from [Amazon book site](https://www.amazon.com/s?i=stripbooks&bbn=283155&rh=n%3A283155&s=review-count-rank&dc&Adv-Srch-Books-Submit.x=30&Adv-Srch-Books-Submit.y=21&qid=1602616200&unfiltered=1&ref=sr_ex_n_1), using a combination of selenium and BeautifulSoup packages in python. This data is not a full collection of all books present on Amazon. Rather, it captures data from the first three pages of each category since these information will be sufficient for the scope of the project. The data was collected on 06, Oct, 2020. 
# Data Curation
The data gotten from the scraping process was subjected to data curation processes and the data saved in a csv file.
## Data Description
* **Author**: Names of books Authors.
* **Category**: Categories books are grouped into, as seen on 
The data was scraped from [Amazon book site](https://www.amazon.com/s?i=stripbooks&bbn=283155&rh=n%3A283155&s=review-count-rank&dc&Adv-Srch-Books-Submit.x=30&Adv-Srch-Books-Submit.y=21&qid=1602616200&unfiltered=1&ref=sr_ex_n_1).
* **Title**: Title of book.
* **Publication_date:** Date of book's publication.
* **Rating:** Average ratings of books based on the total number of reviews.
* **Number_of_rating:** Total number of reviews a book has gotten.

Further insghts on code implementations can be gotten from in-line comments in the notebooks.
