# Microsoft Azure Hackathon for working professionals

This hackathon is aimed at developing solutions using Microsoft Azure for Developers.

Microsoft Azure is a flexible, scalable, and full-featured cloud platform. If you can imagine it, you can build it on Azure, using the tools, languages and frameworks you’re already familiar with. Python, JavaScript, Java, .NET - you can run them all on Azure! You are expected to build innovative solutions and products for the hackathon using the services provided by Azure.



# Folder Structure, Instruction to setup the web application, brief about data and technology stack used

a) Project folder structure

Microsoft_Hackathon_Web_Application is folder name

static
 css
 csv
 js
 img
 json
 scss
 lib
 node_modules
 plugin
 vendor
 favicon.ico

templates
 index.html (main page)
 sides_deck.html
 prediction.html (page for inputting the variables to be fed into ML model)
 final_prediction.html (final prediction page)

app.py (main python file)

core_ML_logic.py (core prediction model using pickled model)

create_mysql_table_scripts.py (run this file to set up a local or remote data table in MySQL database)

requirements.txt: list out all necessary libraries/dependencies for the project


b) Framework and Libraries
Core ML Library:	 sklearn (4 models)
Web Application Framework:	 Python Flask
Other python Libraries:	 pandas, NumPy, seaborn etc.
HTML/CSS/JavaScript:	 Bootstrap, jQuery, d3.js
Database:	 Azure MYSQL Database Instance
Server:	 Microsoft Azure Linux Machine
Analytics Platform:	 Microsoft Azure Databricks
Visualization:	 Microsoft PowerBI
Other Components:	 Azure Data Factory, Azure Blob


c) To run a flask web application, we only need a app.py file. Run this in the python virtaul environment setup for the project.


We used Azure Linux VM Machine to deploy our codes. The VM machine environment will automatically set up the instance, Vnet, and handle loan blancing, scaling and etc.

Deployment
1. How to run the code on your local computer
Make sure that you have the python 3 or above installed on your system. Your system could be either a PC or Mac.

2.create a virtual environment (optional). let's say the virtual environment's name is "digitalwalletfraudprediction". virtualenv digitalwalletfraudprediction (optional)
activate the virtualevn source digitalwalletfraudprediction/bin/activate (optional)

3.install libraries pip install -r requirements.txt

4.create a mysql database locally or remotely and modify parameters in the connection.

5.create the database & data table in Mysql DB by typing in the using python script create_mysql_table_scripts.py

6.run the command on a terminal flask run or python app.py

visit the http://127.0.0.1:5000/
visit the site in the presentation mode at: http://127.0.0.1:5000/presentation?transition=concave#/


d) Dataset & ML Models
There are 36 variables in our dataset. We use combined of 4 ML models:

Logistic Regression Model
Decision Tree model
Random Forest Model
Gradient Boost Model

e) Next Steps
Improve the prediction model by implying more models like Netural Network models etc. Also adjust parameters to improve the accuracy and upgrade from Flask to other secured frameworks.

For full project code please contact me on : +91-9953-569-579 or tushar.sethi@hotmail.com





