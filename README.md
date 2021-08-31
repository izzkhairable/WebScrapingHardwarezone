This project will scrap through hardwarezone gaming-pc page and add the data to mongodb

To run the project:

1. Start MongoDB with "mongod" command
2. Run "scrapy crawl hardwarezone" to start crawling and dumping the data in mongodb
3. Go to Robo3T and the "hardwarezone" database would be created with a "threads" collection

Additional work done:

1. Added "date_posted" data
2. Simple data cleansing in the spider and pipeline
3. Simple data validation in pipeline
