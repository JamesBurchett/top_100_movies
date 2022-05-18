# top_100_movies
This script is an example of web-scraping using the BeautifulSoup package.

The code
1) imports packages
2) grabs the URL and creates a variable 
3) Puts the variable inside of a BeautifulSoup object (soup)
4) finds 'all' h3 tags with the class of "title" and puts this in a variable called movie_data
5) Creates an empty list and then iterates through the movie_data to complete the list
6) Reverses the list
7) Prints the list
