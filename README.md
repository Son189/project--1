# Trains Services

This project deals with giving railway day to day timetable.

For one to travel he/she has to go through the railway schedule then order for tickets.



# Getting started

# procedure

1. Clone this repository to your machine:

        git clone 

2. Change the directory into the project directory: 

      cd project -1.

3. To open in your code editor run: 

        code .

4. To install json server run: 

        npm i json-server

5. To get started with json server run: 

        json-server --watch db.json

6. To view the app use the link provided below

      https://amazing-cat-cd69fa.netlify.app/

# Deliverables

As a user, I can:

1. See the first train's details, including its **number, name, arrival time, departure time, start point 
    and endpoint**, when the page loads. You will need to make a GET request to the
   following endpoint to retrieve the train data:

   ```txt

   GET /trains/1

   Example Response:
   {
      "id": 1,
    "train_num": "12235",
    "name": "Dibrugarh - New Delhi Rajdhani Express",
    "arriveTime": "13:55 +2 nights",
    "departTime": "19:25",
    "train_from": "DBRG",
    "train_to": "NDLS"
      ]
    }
   ```

# Interactivity with the user

-  One is able to go through the railway schedule.

-  One is able to order for train tickets.

-   one is able to like, comment to our services provided.


# Author

- Benson Wanjira

# License
-Was License by ISC
# Built-with

->HTML

->CSS

->JavaScript
