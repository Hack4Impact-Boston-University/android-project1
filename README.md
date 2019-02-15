# Mini Project 1: Match that Color
The first project for the Android track. 

---
## Project Description:

The user will be given a color name in text like, "blue" and four squares of random colors. The trick is that the text "blue" will be shown in a different color, like red for example. 

Let's say the squares are:  :large_blue_diamond: :red_circle: :white_circle: :large_orange_diamond:
And the text: blue is displayed in the color red. 

The user will have 4 seconds to select the blue block and match the color with the text "blue". If they successfully do so, continue the game. If they fail even once, they lose! After the user wins their 7th game, they win!  **Tough game, I know.**

---

## Key Features of the App
*Reference section 4 in the iOS 11 & Swift 4 Udemy Course for tips and guidance*
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
*Reference section 13 for a to-do list code along in the console*
      
      - displays "You lose :(!"
      
### 3. The Winner Page
      
      - displays "You win!"
      
---
      
      
     

 :sun_with_face: **YAAYY!!** :sun_with_face:
