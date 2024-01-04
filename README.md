# Webscraping Books
The website [books to scrape](https://books.toscrape.com/) is an educational website for web scraping containing a catalogue of 1,000 books over 50 pages.

In this project, we will use the Python package `BeautifulSoup` to scrape the books and extract their details such as title, price, ratings, etc.

## Outline 
1. The HTML code of the first page of the website was requested, parsed and stored in a variable called soup.
2. The chunk of HTML code that contained the data of all 20 books on the first page was extracted and stored in a variable as a list.
3. The first item of the list (the HTML code for the first book) was broken down to get the title, price, book rating and book link.
4. This process was placed in a user-defined function and repeated for all 20 books on the first page, the details of which were stored in a dictionary.
5. Once page 1 extraction was successful, a URL list for all 50 web pages was generated, and a function was defined to repeat the entire process listed above and create a dictionary with all 1000 books.
6. This dictionary was converted into a pandas data frame and extracted as a CSV file.

## Challenges
As a first web scraping project, there were numerous trials and errors along with finding the correct methods to deploy. However, overall, the process was positively challenging and insightful.

