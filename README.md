# Turtle Race Game

This is a simple turtle race game built using Python's Turtle graphics module.  
Users can bet on which turtle (by color) will win the race, then watch the race unfold.

## Features

- Six turtles race across the screen, each with a unique color.
- User can place a bet by entering the color of the turtle they think will win.
- Turtles move forward by random steps to simulate a race.
- The program announces if the user won or lost based on the race outcome.

## How to Run

1. Ensure Python 3.x is installed on your system.
2. Save the script in a file, for example, `turtle_race.py`.
3. Run the script via terminal or IDE:

   ```bash
   python turtle_race.py

When prompted, enter your bet by typing the name of a turtle color.

Watch the race and see if your turtle wins!

Click on the window to exit after the race ends.

Code Explanation
Sets up the screen with a width of 500 and height of 400.

Initializes six turtles, each with a different color and position.

Starts the race once the user places a bet.

Each turtle moves forward a random amount until one crosses the finish line.

Announces the result comparing the winning turtle's color with the user's bet.

Dependencies
Python standard library: turtle and random modules.

Author
Nándor Forgó
Email: nfori.coding@gmail.com
