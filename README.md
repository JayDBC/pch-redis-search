This app uses Jedis (Jedis Pipelining) to load data from a CSV file into Redis Hash or JSON objects.

It can add 1 level of nesting in JSON, to support 1 to Many use cases. e.g. Order Header > Order Line Items

See sample file Sunscriptions-10.csv

Note: This code is for demo / learning purposes only. Use the RIOT utility to load data into Redis.

To run the application.

#1 Download the repository from GIT (this uses maven as the build tool)
#2 Create config.properties with connection details (use sample-config.properties as the template)
#2 Edit the App.java specify the path the csv file you wish to load.
#3 Execute App.java
