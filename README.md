# Objectives
In this project, we determine to scrap from the webpages of useful information such as high-resolution images by using BeautifulSoup and Splinter. The scrapped information were stored in MongoDB database. We also used Flask to dispaly the data from the web scrape.

## Project Overview
In this module, we automated a web browser to visit different websites to extract data about the Mission to Mars. We stored it in a NoSQL database, and then render the data in a web application created with Flask. The completed work is displayed in our portfolio, which we also created.  
   
## Resources 
- **Data Source:** [NASA news](https://mars.nasa.gov/news/?page=0&per_page=40&order=publish_date+desc%2Ccreated_at+desc&search=&category=19%2C165%2C184%2C204&blank_scope=Latest) website, [Mars Hemispheres](https://astrogeology.usgs.gov/search/results?q=hemisphere+enhanced&k1=target&v1=Mars) website, [getbootstrap](https://getbootstrap.com/docs/4.0/components/alerts/) website 
- **Software:** BeautifulSoup, Splinter, MongoDB, Flask, Python, Jupyter notebook  

  
  
## Summary
In this module, we automated a web browser to visit the [NASA news](https://mars.nasa.gov/news/?page=0&per_page=40&order=publish_date+desc%2Ccreated_at+desc&search=&category=19%2C165%2C184%2C204&blank_scope=Latest) website and the [Mars Hemispheres](https://astrogeology.usgs.gov/search/results?q=hemisphere+enhanced&k1=target&v1=Mars) website to extract data about the Mission to Mars in [index.html](/templates/index.html). We stored it in a NoSQL database in [scraping.py](/scraping.py), and then render the data in a web application created with Flask in [app.py](/app.py)


On a smaller scale, web scraping automates tedious tasks for personal projects. For example, if you’re collecting current news on a specific subject, web scraping can make it a simple process. Instead of visiting each website and copying an article, a web scraping script will perform those actions and save the scraped data for later analysis.  
<br/>
<br/>
<br/>
<br/>  
