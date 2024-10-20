# PageRank
Simple Python Search Spider, Page Ranker, and Visualizer

This is a set of programs that emulate some of the functions of a 
search engine. They store their data in a SQLITE3 database named
'spider.sqlite'. This file can be removed at any time to restart the
process.   
This program crawls a web site and pulls a series of pages into the
database, recording the links between pages.
In this sample run, we told it to crawl a website and retrieve two 
pages. If you restart the program again and tell it to crawl more
pages, it will not re-crawl any pages already in the database. Upon 
restart it goes to a random non-crawled page and starts there. So 
each successive run of spider.py is additive.
