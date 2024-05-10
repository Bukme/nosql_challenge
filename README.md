# Eat Safe, Love NoSQL Challenge

This repository contains code for the Eat Safe, Love NoSQL Challenge, which involves setting up a MongoDB database, importing data, and performing exploratory analysis on food establishment data.

## Part 1: Database Setup and Data Import

### Overview

In this part, the focus is on setting up the database and importing data into MongoDB. The dataset provided is `establishments.json`, containing information about food establishments.

### Steps Taken

1. **Database Setup**: A MongoDB database named `uk_food` is created.
2. **Data Import**: The `establishments.json` file is imported into the `establishments` collection within the `uk_food` database.
3. **Jupyter Notebook Setup**: Dependencies such as `pymongo` for MongoDB interaction and `pandas` for data manipulation are imported.

## Part 2: Exploratory Data Analysis

### Overview

The second part involves exploratory analysis of the food establishment data within MongoDB. Various questions are answered to gain insights into the dataset.

### Exploratory Analysis Questions

1. **Which establishments have a hygiene score equal to 20?**
2. **Which establishments in London have a `RatingValue` greater than or equal to 4?**
3. **What are the top 5 establishments with a `RatingValue` rating value of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?**
4. **How many establishments in each Local Authority area have a hygiene score of 0?**

### Steps Taken

1. **Notebook Setup**: Dependencies are imported, and the connection to the MongoDB database is established.
2. **Exploratory Analysis**: Each question is addressed by querying the database, extracting relevant information, and presenting results using both MongoDB queries and Pandas DataFrames.

### Conclusion

This repository provides a comprehensive demonstration of setting up a MongoDB database, importing data, and performing exploratory analysis on food establishment data.

For detailed code implementation and results, refer to the Jupyter Notebooks provided in this repository.


## References
Bekker, R. (2022, August 5). MongoDB cheatsheet with Pymongo. Sysadmins. https://sysadmins.co.za/mongodb-cheatsheet-with-pymongo/ 

Beugnet, M. (2023, September 27). MongoDB cheat sheet. MongoDB. https://www.mongodb.com/developer/products/mongodb/cheat-sheet/ 

MongoDB documentation.css-134mg1q{-webkit-align-self:center;-ms-flex-item-align:center;align-self:center;padding:0 10px;visibility:hidden;}.css-6vrlzm{border-radius:0!important;display:initial!important;margin:initial!important;}.css-1l4s55v{margin-top:-175px;position:absolute;padding-bottom:2px;}. MongoDB Documentation. (n.d.). https://www.mongodb.com/docs/ 

Pymongo 4.6.1 documentation#. PyMongo 4.6.1 documentation. (n.d.). https://pymongo.readthedocs.io/en/stable/index.html 

Sign in. DataCamp. (n.d.). https://app.datacamp.com/learn/courses/introduction-to-using-mongodb-for-data-science-with-python 

Other resourceful ideas gotten from class, tutor and other students. 
