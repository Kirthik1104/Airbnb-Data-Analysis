<h1># Airbnb-Data-Analysis<img src="https://media.giphy.com/media/r3J4ibKEk5MafUxFue/giphy.gif" width="48" /></h1>

<h2>Problecm Statement:</h2>
Many travelers now have access to fantastic, simple, and convenient lodging thanks to Airbnb. Similar to that, it has also provided many people the 
chance to earn extra money by selling their properties as places where people can stay. Today, Airbnb has developed into a unique service that is used by 
people all over the world. However, there are so many ads with different price ranges accessible, When the primary goal of a 
prospective host is to market a home on Airbnb and generate rental income, how can he decide what kind of property to buy? Furthermore, How does a traveler know what factors to 
consider to discover a suitable listing if he wants to find the cheapest listing available but with particular qualities he/she 
loves like "maximum reviews", "minimum price, “popular host" etc.? Using the Airbnb dataset, we predicted the crucial 
problem for a host and also for the traveler. We identified the number of Airbnb locations owned by an individual host also 
predicted popular Airbnb locations along with high rated host furthermore gathered locations of different room types with minimum prices and maximum reviews.


<h3>Data Analysis Carried Out:</h3>

* Problem Statement 1: Analyzed our dataset and exhibit number 
  of houses at simultaneous location owned by host and 
  furthermore providing total summation of houses that is total 
  count of all houses owned by host at all locations.

* Problem Statement 2: Predicted top five popular Airbnb 
  locations to visit under high rated host and also total nights 
  spend by tourist at this location. Additionally, inspected the 
  high rated host for the aforesaid locations

* Problem Statement 3: Extracted different types of room which 
  are available in our dataset from 48995 data values available. 
  From that Analyzed and predicted top 3 locations with 
  individual room types, host name, near by location, 300+ days 
  availability, price less than 100 and maximum number of reviews.
  
<h3>Implementation:</h3>

Created Database considering that documents are stored in JSON format in MongoDB and since our dataset is in csv file, we created our collection and 
passed our csv file to MongoDB and we got our dataset in JSON format. Mongo db provides its own schema visualization for better understanding. 
By analyzing different filters and understanding graphs we made contemplative query analysis. Furthermore, we used 
python with MongoDB for the implementation of the system. For better visualization and understanding we used Pycharm with MongoDB Database.
Having access to various python libraries allows us to perform complex tasks. To access the MongoDB database, Python needs a MongoDB driver.
To use the Mongo Client tool, we imported the pymongo module into the PyCharm program on our local computer
