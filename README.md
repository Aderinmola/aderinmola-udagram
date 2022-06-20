# Udagram Image Filtering Microservice

Udagram is a simple cloud application developed alongside the Udacity Cloud Engineering Nanodegree. It allows users to register and log into a web client, post photos to the feed, and process photos using an image filtering microservice.

Elasticbeanstalk url (EB_URL):
http://udacity-udagram-aderinmola.us-east-1.elasticbeanstalk.com/

The endpoint can be tested by sending a GET request to:

http://udacity-udagram-aderinmola.us-east-1.elasticbeanstalk.com/filteredImage?image_url={image_url}
where image_url is a query parameter that represents the url of the publicly available image.