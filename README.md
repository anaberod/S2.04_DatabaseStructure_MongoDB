# 🍽️ MongoDB Restaurant Queries – Level 1

## 📄 Description – Exercise Statement

This project focuses on learning how to query a NoSQL database using **MongoDB**. The exercise is based on a real-world dataset of restaurants located in New York City. The goal is to run a series of queries on this dataset to retrieve, filter, and manipulate restaurant documents according to various criteria.

## 💻 Technologies Used

- **MongoDB** – NoSQL document-oriented database
- **MongoDB Compass** – GUI for MongoDB queries
- **JSON** – Format used for data import/export
- **Markdown** – For documentation
- **Git & GitHub** – Version control and hosting

## 📋 Requirements

Before running this project, ensure the following are installed on your local machine:

- MongoDB Community Edition – version 6.x recommended
- MongoDB Compass – latest version
- Git – optional, for version control
- A modern browser (for viewing MongoDB Compass UI)

## 🛠️ Installation

Follow these steps to set up the project locally:

1. Clone the repository
   git clone https://github.com/anaberod/S2.04_DatabaseStructure_MongoDB_Level1.git
   cd S2.04_DatabaseStructure_MongoDB_Level1

2. Start your MongoDB server (if not running automatically):
   mongod

3. Open MongoDB Compass, connect to:
   mongodb://localhost:27017

4. Import the dataset:
   - Open the Restaurants collection in Compass.
   - Click "Add Data" > "Import File".
   - Choose restaurants.json and set file type to "JSON - Each line is a separate document".
   - Click Import.

## ▶️ Execution

Once the data is imported:

1. Go to the Documents tab inside the Restaurants collection.
2. Use the filter bar to execute each query one at a time.
3. You can also use the Options panel to apply:
   - Projections (select specific fields)
   - Sort
   - Limit/Skip results

Example query:
{ "borough": "Bronx" }

## 🌐 Deployment

This is a local-only educational project, but to deploy to a remote environment:

- Use MongoDB Atlas to host the database in the cloud.
- Import the .json file using the Atlas UI or mongosh.
- Use the same queries via Compass or MongoDB Atlas’s query console.

## 🤝 Contributions

Contributions are welcome! If you want to improve this project:

1. Fork the repository
2. Create a new branch:
   git checkout -b feature-name
3. Commit your changes and push:
   git push origin feature-name
4. Submit a pull request

Please follow conventional commit messages and include clear documentation for your changes.
