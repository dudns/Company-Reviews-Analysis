# Company-Reviews-Analysis in Jobplanet website  
Jobplanet url : https://www.jobplanet.co.kr

This team project was part of 'Data Journalism' class in Seoul National University, 2018 December. 
Among four teammates, I was one of the programmers who wrote the code.


#### 1) Crawler 
We crawled review data from Jobplanet using Selenium. Jobplanet ID and password are needed to crawl the data. 
We crawled the stars reviewers gave to the company, and also text reviews. After crawling we saved the data in pandas Dataframe. 

#### 2) Correlation Coefficient
We found out among five elements, which were promotion, welfare/income, work and life balance, culture, CEO, which is the most relevant
to the total stars by correlation coefficient using Numpy. 

#### 3) Bigram and Wordcloud 
We collected the most frequently used bigrams in reviews and drew wordcloud to visualize our results.

### References
1. Crawling 
https://github.com/zzsza/jobplanet-interview-crawling
2. Wordcloud Hue Function
https://stackoverflow.com/questions/43043263/word-cloud-in-python-with-customised-colour
