# Sofi
Decision tree to choose your DB - 2020

## About
This project was created from a hackathon.<br />
The goal of the project is to create a service that will help developers to choose the most suitable DB for their needs.<br />
The service was built in Python and React (here is the only Python backend).

 ## Project Structure
 * flask_app.py - this is the module that implements the flask application
 * db_choise.py - this is the module that implements the decision tree from sklearn for the algorithm
 * enum_converter.py - this module contains the map between attributes and numbers,<br /> due to the limitation of sklearn tree to work only with numbers
 * generate_dataset.py - this module create a dataset from manual user inputs
 * dataset.txt - this is the dataset which the decision tree will learn from
