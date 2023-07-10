# MongoDB Python CRUD Operations

This repository contains a Python program demonstrating CRUD (Create, Read, Update, Delete) operations using MongoDB and the PyMongo library. The program connects to a MongoDB cluster and performs various operations on a collection named "workers" in the "office" database.

## Prerequisites

To run this program, you need to have the following:

- Python (version 3.7 or higher)
- PyMongo library
- MongoDB Atlas account or a local MongoDB instance

## Installation

1. Clone this repository to your local machine using the following command:

```
git clone https://github.com/prath0m/your-repository.git
```

2. Install the required dependencies using pip:

```
pip install pymongo
```

4. Update the connection details in the Python program (`MongoDBAssignment2.ipybn`) with your MongoDB cluster information.

## Usage

1. Run the Python program:

```
python MongoDBAssignment2.ipybn
```

2. Follow the prompts in the program to perform CRUD operations on the "workers" collection. The program includes the following functionality:

- Add a new employee document
- Update the document with the new city and department
- Copy the document to another collection ("exworkers") and delete it from the "workers" collection
- Fetch documents with salary greater than a specified value

3. View the output in the console, which displays the results of the operations.


