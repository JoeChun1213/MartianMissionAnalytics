## Project Overview
In this module, we automated a web browser to visit different websites to extract data about the Mission to Mars. We stored it in a NoSQL database, and then render the data in a web application created with Flask. The completed work is displayed in our portfolio, which we also created.  
  


   
## Resources 
- **Data Source:** [NASA news](https://mars.nasa.gov/news/?page=0&per_page=40&order=publish_date+desc%2Ccreated_at+desc&search=&category=19%2C165%2C184%2C204&blank_scope=Latest) website, [Mars Hemispheres](https://astrogeology.usgs.gov/search/results?q=hemisphere+enhanced&k1=target&v1=Mars) website, [getbootstrap](https://getbootstrap.com/docs/4.0/components/alerts/) website 
- **Software:** BeautifulSoup, Splinter, MongoDB, Flask, Python, Jupyter notebook  

  
  
  
## Objectives
By the end of this module, we will be able to: 
- Gain familiarity with and use HTML elements, as well as class and id attributes, to identify content for web scraping.
- Use BeautifulSoup and Splinter to automate a web browser and perform a web scrape.
- Create a MongoDB database to store data from the web scrape.
- Create a web application with Flask to display the data from the web scrape.
- Create an HTML/CSS portfolio to showcase projects.
- Use Bootstrap components to polish and customize the portfolio.

  
  
  
## Summary
In this module, we automated a web browser to visit the [NASA news](https://mars.nasa.gov/news/?page=0&per_page=40&order=publish_date+desc%2Ccreated_at+desc&search=&category=19%2C165%2C184%2C204&blank_scope=Latest) website and the [Mars Hemispheres](https://astrogeology.usgs.gov/search/results?q=hemisphere+enhanced&k1=target&v1=Mars) website to extract data about the Mission to Mars in [index.html](/templates/index.html). We stored it in a NoSQL database in [scraping.py](/scraping.py), and then render the data in a web application created with Flask in [app.py](/app.py)


On a smaller scale, web scraping automates tedious tasks for personal projects. For example, if you’re collecting current news on a specific subject, web scraping can make it a simple process. Instead of visiting each website and copying an article, a web scraping script will perform those actions and save the scraped data for later analysis.  
<br/>
<br/>
<br/>
<br/>  

## Challenge Overview
In this challenge, we will scrape additional content for the web app. This time, the focus is to add more images to the app.
Background  

## Objectives
- Use BeautifulSoup and Splinter to automate a web browser and scrape high-resolution images.
- Use a MongoDB database to store data from the web scrape. 
- Update the web application and Flask to display the data from the web scrape.
- Use Bootstrap to style the web app.
