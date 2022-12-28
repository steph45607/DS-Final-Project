# Data Science Final Project
Test ideas and code for Data Science Final Project

## Group Members 
* Maria Clarin - 2501990331 - L3AC
* Rachel Anastasia Wijaya - 2502009646 - L3BC
* Stephanie Staniswinata - 2501997836 - L3AC

## Our Spreadsheet (Before and After Munging files included) : 
* https://docs.google.com/spreadsheets/d/1mj1YRoDM-0qGcZRHSwyQGx_OG_dH1i17LsM1brKqxjw/edit?usp=sharing
* The sheets/files Indo-Indo7 shows the data munging progress of our first dataset resource, showing the difference of each step of the data munging. 
* The sheets/files USBefore and USAfter is the raw scraped file and the post-munging file of our 2nd dataset resource.

## Datasets Resources:
* https://www.goodreads.com/book/most_read
* https://www.goodreads.com/shelf/show/most-read-this-week
* https://www.nytimes.com/books/best-sellers/
* https://www.goodreads.com/shelf/show/horror
* https://www.goodreads.com/user/top_readers

## Goal
To know if the increase or decrease of book rating is affected by the top-rated books section.

### .ipynb files and what it does
1. assignment plot.ipynb
   * Class assignment on SVM
2. Author_Details.ipynb
   * Scraping author page
   * Get information such as
     * name
     * average rating
     * number of ratings
     * number of reviews
3. Author.ipynb
   * same with author_details.ipnyb
   * add number of distinct works
4. BERTTest.ipynb
   * test BERT
   * using book descriptions to recommend other books
5. Fix_Missing.ipynb
   * clean out all missing titles from the list
   * return a new csv
6. GetBookInfoAll.ipynb
   * Get book info such as
     * Title
     * Author
     * Year
     * Rating
     * Raters
     * Genre
7. hierarchical.ipynb
   * 