# Mission-to-Mars
## Overview
A junior data scientist, Robin had a dream to work in NASA someday. In her spare time, she does freelance astronomy work such as visiting websites and gathering Mission to Mars News. One day, Robin had an idea to access all information related to Mission to Mars in one location and decided to build a web application. The web application shall provide the most up to date information at the click of a button. Information for this web application will be provided by scraping data from Redplanetscience, Spaceimages-mars, Galaxyfacts-mars, and Marshemispheres websites using Python. After scraping the data, MongoDB is used to store the data and Flask is used to display information as a web application.

## Summary
### 1. Scraping
By importing Beautiful Soup, Pandas, Splinter, and ChromeDriverManager dependencies using Python, the following data is scraped:

- Latest Mars News from Redplanetscience website.
- Featured Mars Image from Spaceimages-mars website.
- Mars Facts from Galaxyfacts-mars website.
- Mars Hemispheres from Marshemispheres website.

### 2. Storing
After scraping data from multiple websites, the images, tables, and paragraphs retrieved are stored in a MongoDB database.

### 3. Displaying
Using MongoDB with Flask templating, a new HTML page was created. To style and display the data in a structured way, Bootstrap 3 components were used. The structured HTML page is displayed as shown below: 

![image](https://user-images.githubusercontent.com/76491891/116786937-635c0980-aa6f-11eb-8fe3-730fb30d80cf.png)
![image](https://user-images.githubusercontent.com/76491891/116786953-7ff84180-aa6f-11eb-88ba-d339489121c5.png)
