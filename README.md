# CeneoScraperCS11
https://www.ceneo.pl/84514582#tab=reviews_scroll

## Ceneo scraping algorithm
1. Analysis of the structure of the webpage
2. Sending HTTP request to access first page with opinions
3. Checking the code of HTTP responce
4. Parse the HTML code of first page with opinions 
5. Extract required data from the parsed code
6. If there are more pages, move to the next page and repeat steps 2-6 for them
7. Save extracted data

## Analysis of the structure of the webpage
|Component|Selector|Variable|
|---------|--------|--------|
|opinion ID| | |
|opinion’s author| | |
|author’s recommendation| | |
|number of stars| | |
|opinion’s content| | |
|list of product advantages| | |
|list of product disadvantages| | |
|for how many helpful| | |
|for how many unhelpful| | |
|publishing date| | |
|purchase date| | |