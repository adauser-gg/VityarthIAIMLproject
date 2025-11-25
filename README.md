# Question Paper Archive

This is a local web application built using Python and Flask. It facilitates the uploading of question papers (PDFs or images) and tagging them with essential metadata such as subject, year, and exam type. All data and files are stored locally on your machine using SQLite.
It uses numpy and arrays learned in the course to manage files and explores different sorting algorithm like breadth first search & depth first search, etc.

## Overview

The primary goal of this project is to consolidate scattered question paper files into a single, searchable digital library. Users can upload a file, tag it with relevant details, and have it saved to a structured folder while the metadata is recorded in a database. This allows for easy searching and filtering of specific papers later.

## Features

* File Upload: Supports uploading of PDF and image files.

* Metadata Tagging: Allows tagging of papers with Subject, Exam Type, and Year.

* Search Functionality: Filter existing papers based on their tags.

* Local Storage: Files are securely saved in a local uploads directory.

* Database: Utilizes SQLite to maintain file details without requiring an internet connection.

* Unique Filenames: Automatically renames files to prevent accidental overwriting of existing documents.

## Technologies Used

Python 3

* Flask (Web Framework)

* SQLite (Database)

* HTML/CSS

* numpy

* array

## Steps to Install & Run the Project

* Download the Code

* Clone this repository or download the project folder to your computer.

* Install Dependencies
Open your terminal within the project folder and execute:
```
pip install -r requirements.txt
```

## Run the App

* Start the server by running:
```
python main.py
```

Open in Browser
Go to: http://127.0.0.1:5000

## Instructions for Testing

### To Upload:

* Click "Upload a Paper" on the home screen.

* Select the Subject, Exam Type, and Year.

* Choose a file from your computer.

* Click Upload.

### To Search:

* Click "Search for a Paper" on the home screen.

* Select the filters you wish to apply (e.g., "Maths" and "2024").

* Click Search.

* Click on the filename in the results list to open or download the file.

  ## Screenshots

![Home Page](./screenshots/img.png)
![Upload Page](./screenshots/img_1.png)
![Search Page](./screenshots/img_2.png)
![Terminal view](./screenshots/img_3.png)

### Get started and save your question papers!
