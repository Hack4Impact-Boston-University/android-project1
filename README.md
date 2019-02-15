# Mini Project 1: Match that Color
The first project for the Android track. 

---
## Project Description:

The user will be given a color name in text like, "blue" and four squares of random colors. The trick is that the text "blue" will be shown in a different color, like red for example. 

Let's say the squares are:  :large_blue_diamond: :red_circle: :white_circle: :large_orange_diamond:
And the text: blue is displayed in the color red. 

The user will have 4 seconds to select the blue block and match the color with the text "blue". If they successfully do so, continue the game. If they fail even once, they lose! After the user wins their 7th game, they win!  **Tough game, I know.**

Play off of the Stroop Experiment: https://faculty.washington.edu/chudler/words.html

---

## Key Features of the App
*Reference section 5 of the Android Udemy course for info about timers and the Brain Trainer Game (similar logic)*
### 1. The Introduction Screen
      - displays a big neon button that says "Go!"
      - when clicked, the user will be brought to the Game Screen.

### 2. The Game Screen 
      - displays "Match that Color! By: [Your Name]" at the top
      - displays a timer that counts down from 4
      - displays a random color name like "blue" that is displayed in a random color like red
      - if a user clicks the incorrect color
            - the game is over and you are brought to The Loser Page
      - if a user clicks the correct answer:
            - increment the counter that keeps track of the number of games being played
            - return to the game screen, reset timer and play again!
      - when counter = 8, break out of the loop and go to The Winner Page
          

### 3. The Loser Page
      
      - displays "You lose :(!"
      
### 4. The Winner Page
      
      - displays "You win! :)"
      
---
      
      
     

 :sun_with_face: **YAAYY!!** :sun_with_face:
