
##Task
The task is to create backend API to allow a user to search for a movie search by genre.
Your backend will receive a requested genre and will only serve movies with the corresponding genre.
The client requests all Action movies.
The backend should parse the CSV, filter by the genre `Action and reply with a list of Action movies, 
while also respecting the HTTP protocol.
For this project you will be able to use a framework to take care of the HTTP communication protocol.

## Description
Technical Description
Create a backend app with a light web framework. It uses flask
It will listen on port 8080.
All the routes answer in JSON format!
No need for a database, just parse the provided CSV.
 backend serves six routes:
GET on / This route will parse the GET parameter genre, to be able to filter by movie genre.
Example on how to access this route:
curl "http://localhost:8080?genre=action"
GET on /action This route will only serve action movies.


## Installation
There was no installation

## Usage
SV (Comma Separated Values) is a popular file format used to store tabular data. 
Parsing a CSV file involves reading the file and breaking it down into its constituent parts,
 such as rows and columns, so that the data can be used and manipulated as needed. 
 Here are the general steps for parsing a CSV file:
Open the CSV file: Use Python's built-in open() function to open the CSV file in read mode.
 You can specify the file path and name as the argument.

Read the file: Use Python's csv.reader() function to read the file. 
This function takes the file object as an argument and returns a CSV reader object that can be used to iterate over the rows in the CSV file.

Process the data: Loop over the rows in the CSV file using a for loop, 
and use Python's built-in string manipulation functions to split each row into individual values based on the delimiter (usually a comma). You can then store these values in a data structure such as a list or a dictionary.
Close the file: After you're done processing the CSV file, 
make sure to close it using the close() method of the file object.





```
./my_project Oluwakemi Deniran
```

### The Core Team


<span><i>Made at <a href='https://qwasar.io'>Qwasar SV -- Software Engineering School</a></i></span>
<span><img alt='Qwasar SV -- Software Engineering School's Logo' src='https://storage.googleapis.com/qwasar-public/qwasar-logo_50x50.png' width='20px'></span>
