# Battleships game

This is a website that lets a user play a game of battleships against a computer

## Contents

* Goals
    * Owner goals
    * User goals

* Layout/Structure
    * Different parts of the game
    * Flowchart

* Features

* Technologies

* Testing 

* Issues

* Deployment

* Credits

## Goals

### Owner goals

- Make a battleships game in python, test my skills as a programmer and provide a fun
, interactive chance based game.

### User goals

- Play a fun interactive chance based game, be aware of their progress and be able to
quit and restart the game at their own discretion.

## Layout/Structure

### Start

![Start](images/start.png)

- When the user starts the game the number of rounds, ships and the board size is 
displayed to them.
- After that they are prompted to enter their name.

### Name entered

![Name](images/name.png)

- After the user enters their name their board and the computers board is printed.
- They are then prompted to guess a row and a column.

### After guess

![Guess](images/guess.png)

- After the player guesses a row and a column the program displays where the player
guessed and if they scored a hit then it does the same for the computer.
- Then it prints the player and computer's board it marks a miss on the board with
X and a hit with *.
- Then it asks the player if they would like to continue playing or quit .
- If they quit the game ends and the score is displayed, if they continue the user.
is prompted to guess an row and a column again and the same thing happens until 
they have played 5 rounds when they have played 5 rounds the game ends.

### Flowchart

![Flowchart](images/flowchart.png)

- Above is a flowchart that I made in lucidchart to help me plan out my project.

## Features

### The game allows the user to: 
- Enter their name 
- Keep playing, quit or restart whenever they want

### The game provides feedback in the form:
- Of telling the user if input is valid
- Displaying the score after a round is played
- Marking the board with an X where there was a guess that missed
- Marking the board with an asterisk where there was a hit

### It provides valuable information in the start screen such as:
- The number of ships 
- The board size
- The number of ships
- How to restart the game
- The fact that some ships may be duplicated

## Missing features

### If I had more time I would have:
- Found a way to stop ships from being duplicated

## Technologies

### I used the following to make the project:
- Code institute template for the third portfolio project
- Python to generate the board, ships,take in user input and 
update the board
- Gitpod to add code and assets to my project
- Github for version control and storing my project
- The pep8 online check website to check for errors and fix 
them
- Heroku to deploy my website
- Lucid chart to make a flow chart that I would use to plan 
out my website

## Testing 

### Validator testing 

![Test](images/test.png)

- I used the pep8 online checker to make sure that there 
are no significant errors in my code

## Issues

* Sometimes the ships can be duplicated on the same row 
and column

## Deployment

I deployed my site to heroku using the following steps:
- I made the final changes to my code and pushed them to 
github
- Logged into my heroku account
- Selected the option to create a new app
- Named my project battleships-ultimate then clicked create app
- In the settings section I added the python buildpack and the 
nodejs buildpack
- Then I went to the deploy section and connected to github
- Then I selected my battleships repository and connected it
- Then I enabled automatic deploys and clicked deploy branch 
and that was the end of the deployment

Here is a link to my site: https://battleships-ultimate.herokuapp.com/

## Credits

- I used some of the code from the 3rd portfolio project scoping video to help make the basic structure of the program
and to help me decide what functions I was going to use

Here is the code I added using the scoping video

![Code1](images/1.png)

![Code2](images/2.png)

![Code3](images/3.png)

- I would also like to thank my mentor Seun for giving me great suggestions on how to improve my game