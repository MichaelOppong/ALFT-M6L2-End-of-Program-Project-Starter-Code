# Capstone Project: AMC's Ticket App

Oh no! AMC's app developer QUIT! Their app needs updating ASAP.

Can you help them to update their app?

# Project Requirements

The app should have at least 2 sections. When the page loads, only the first section should be visible.

### Task 1: Movie Poster Image
* Add at least 4 movie posters to the HTML (find image choices linked below)

### Task 2: Movie Poster Resize
* Once you have the movie poster images in your HTML, use CSS to make the posters the same size.When a poster is clicked, there must be a visual cue. (i.e. poster size increases, poster has a border, etc.)

### Task 3: Movie Reviews
* Create an array of movie reviews for each movie. Using a loop and jQuery append reviews for each movie to the div with the class `movieReviews`. This for loop should run when a user clicks on the movie image.

The remaining sections should be displayed, when the user is ready to buy tickets.

### Task 4: Cost Calculation
*When the user clicks on the "Calculate Total" button, use `.val` to calculate the total cost based on the number of tickets entered into the input fields: 
* Create a variable named `child` and set it equal to the number a user types into the input field with the id `numberChild` multiplied by the price of a child ticket ($8)
* Create a variable named `adult` and set it equal to the number a user types into the input field with the id `numberAdult` multiplied by the price of a child ticket ($12)
*Create a variable named `total` and set it equal to the variable `adult` + the variable `child`

### Task 5: Checkout
Use conditionals to display different messages depending on total cost in the div with the id `totalCost`:
* If total is less than 0 display, "You cannot select a negative number"
* If total  is equal to 0 display, "You did not select any tickets"
* If total  is more than 0 display, "Your total cost is" + the cost


### Task 1 Movie poster image options:
* Black Panther:
https://images-na.ssl-images-amazon.com/images/M/MV5BMTg1MTY2MjYzNV5BMl5BanBnXkFtZTgwMTc4NTMwNDI@._V1_UY1200_CR90,0,630,1200_AL_.jpg 

* A Wrinkle in Time:
http://cdn.collider.com/wp-content/uploads/2017/11/a-wrinkle-in-time-poster.jpg

* Avengers:
https://upload.wikimedia.org/wikipedia/en/4/4d/Avengers_Infinity_War_poster.jpg

* Lady Bird:
http://is4.mzstatic.com/image/thumb/Video118/v4/33/ff/46/33ff4600-7d1b-0e8a-50b9-5fdb83c6e2ab/source/1200x630bb.jpg

Thank you for your help. If you are successful, you will be paid $1,000,000.