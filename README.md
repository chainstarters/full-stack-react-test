# Chainstarters Full Stack JS Test

__Dev Test for mid to senior full stack React JS engineers__

### Context

A game requires users to travel to a checkpoint in their city to claim a token.

A checkpoint is usually a public park or famous building.

For some users, depending on where they live, the checkpoint might be far away from their home, or close-by. We want to be fair and give rewards to users based on how far they had to travel in order to complete the game.

![](/map_example.png){:height="400px" width="255px"}

### Need

We need to estimate the total distance traveled. Assume they will go from home to the checkpoint and back home again.

We need our database to give each user an integral ranking between 1-10 based on how far they must travel compared to the shortest and longest travel distance.

We need to show each user how far each checkpoint is from where they are.


### You have this data available:

- The latitude, longitude for each checkpoint.
- The latitude, longitude for the user at any moment.
- The home address of the user.

Access to 3rd party API's  - but only use if necessary.


### Implementation

1. Design a database model (Express, Prisma, or similar) that can store users, checkpoints, and distances. Note: users will play many other games like this over time.
1. Write the logic for estimating total distance and sorting users based on this distance for the game.
1. Serve a single webpage dashboard using React that shows the users and rankings
1. Bonus: Create an app screen using React Native that shows a user the location of a checkpoint and how far away it is from them.

### Deliverable

1. Fork this repository and commit your source code here.
1. Run everything locally and save screenshots of webpage and app screen 
1. Actual hosting or app build is not necessary.
1. Assuming you have a Node, React, React Native environment already setup on your computer, this project is estimated to take 3-5 hours.

### Grading

1. Your code will be inspected for readability and quality.
1. Your choices in database, API logic, interfaces will be judged compared to best practices.
1. Demonstrate you can implement only basic UI elements. (We have a designer on the team that will provide designs.) We are NOT judging UI design.
1. If you pass on the React Native app screen, we will judge a RESTful API endpoint that serves same purpose.
