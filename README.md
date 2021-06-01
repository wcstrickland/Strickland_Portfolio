
# [Project 1: Yikes!](https://still-wildwood-10638.herokuapp.com/)
## A yelp like website for sharing haunted locations!
#### [The github repo](https://github.com/wcstrickland/yikes)

A web app for users to:
- create locations listings
- leave reviews
- and report content

This project includes:
- NodeJS
- Express
- MongoDB
- Deployment via Heroku
- templating to create dynamic web pages
- user authentication
- using API's from multiple cloud services. e.g. mongoDB, cloudinary, mapbox

![If you are reading this my link broke. :(](https://media.giphy.com/media/jujOO2uiyU0Xt31E2t/giphy.gif)

---------------------------------------------------------------------------------------------------------------------------------------------

# [Project 2: Call Center performance analysis and visualization](https://github.com/wcstrickland/call_center)
#### Business Case: A call center supervisor is provided an excel spreadsheet with performance metrics generated by call monitoring software and desires a format with improved insight.

Reformatted [original](images/call_raw_xl.png) excel workbook designed for rudimentary analysis.
Then used Python to reorganize data and calculate new fields specific to business case,
and generated [statistical analysis](images/jupyter_img.png) of performance by group. 
Finally, exported data to tableau and created [interactive dashboard](https://public.tableau.com/shared/KXPPY74GJ?:display_count=y&:origin=viz_share_link) for the end user.

![If you are reading this my link broke. :(](https://media.giphy.com/media/LoZyUPDg7HZu2sgd5I/giphy.gif)

---------------------------------------------------------------------------------------------------------------------------------------------


# [Project 3: Priority Queue Scheduler](https://github.com/wcstrickland/priorityqueue)
## Concept
The program allows the creation of Employees, Jobs, and Priority levels. Jobs have several properties including a priority level, a length of time the job has been listed, and an estimated time the job will take to complete. The program assigns “jobs” to employees always allocating the highest priority level job that has been listed the longest. This system ensures the most important jobs are evenly distributed across employees for simultaneous completion to prevent bottlenecking. Employees are scheduled up until they reach their “max hours” for the day, which may vary if the employee is part-time or working a half-day. A threshold can be set to provide an alert if there are jobs left outstanding in a priority level after scheduling to determine resource management such as authorizing overtime or using temp employees. 

## Practical Highlights:
- Versatile: can be applied to any allocation of a prioritized workflow (maintenance work orders, call center hold queue, patient intake in a hospital)
- Streamlined: user input required only at the level of necessity such as creating a work order or determining employees who are not working on a given day. Jobs are automatically added to appropriate queues, and warnings are provided if inputs are malformed such as creating a job with a priority level that does not exist.
- Reusable
- Efficient


## Technical Highlights:
- Use of unit testing
- Use of max heap to create priority queues based on the attribute of an object to optimize performance
- Use of generator functions. 

## Sample alert and individual schedule 
![If you are reading this my link broke. :(](images/sample_alert.png)

---------------------------------------------------------------------------------------------------------------------------------------------

# [Project 4: Create databse table from CSV](https://github.com/wcstrickland/csv_to_sql)
#### A python command line tool that inserts data from a CSV file into a Database.

The goal of the project was to provide a tool to quickly migrate large amounts of data into a databse where the traditional import tools in database workbenches would become bogged down or hang. The sample file shown in the gif is a flow cytometry output CSV of over a million rows and almost 20 columns. The file is [too large](images/csv4.png) to upload to github and consistently causes the MySQL workbench import wizard to fail. Even after converting the CSV to a a SQL script the process is still unreliable. This program creates a database table and inserts the data in a matter of [seconds](images/csv1.png).

This project improved my understanding of
- [creating a Command Line Interface](images/csv3.png)
- property decoration
- generator behavior
- context managers
- i/o
- custom iteration
- [utilizing GUIs](images/csv2.png)

![If you are reading this my link broke. :(](https://media.giphy.com/media/IqKeb1e0qlnZFz9vk9/giphy.gif)


---------------------------------------------------------------------------------------------------------------------------------------------

# Project 5: Rock Paper Scissors
# [Python version](https://github.com/wcstrickland/rock_paper_scissors)
# [Javascript version](https://github.com/wcstrickland/RockPaperScissors)

#### A simple graphical game of Rock Paper Scissors.

![If you are reading this my link broke. :(](https://media.giphy.com/media/5kQYqUcXHCKkGYBQNY/giphy.gif)

![If you are reading this my link broke. :(](https://media.giphy.com/media/JGXjxr0c0bRPa682fn/giphy.gif)

This project includes:
- implementing logic in multiple languages.
- drawing/manipulating GUI elements
- callback functions
- basic DOM manipulation

---------------------------------------------------------------------------------------------------------------------------------------------



# [Project 6: Web Scraper and API](https://github.com/wcstrickland/news_api)
#### A REST API interfacing with a data base of news articles scraped from a website in JSON like format.

##### Part 1
Created a web scraping program that requests html from a major news outlet and then parses the request return via tags. 
##### Part 2
Created a front facing API that allows users to programmatically search the data base with high level of specificity through a series of endpoints, or a simple query string.
##### Part 3 
Created a simple static html page with  a brief description of the API’s endpoints and provided examples on how to properly use them. 

This project includes:
- web scraping and html tags
- capturing information via python and storing/accessing it in a database.
- Web framework principles (Flask) specifically establishing request routes, defining resources, serialization of information, and JSON format.
- Utilizing a python driver to interface with SQL.

![If you are reading this my link broke. :(](images/home_page_img.png)

