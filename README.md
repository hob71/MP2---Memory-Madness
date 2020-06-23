# Hogwarts Memory Madness
## Introduction: 
 The project ‘Hogwarts memory Madness’ is based on the traditional card memory game where a player must turn a card and then turn a second card to see if the pictures match. If no match then the cards are turned back and a new card is picked. The idea is to match the cards in the least amount of turns.
This version will count the number of turned cards to complete the game plus the additional challenge of beating the clock before the game is over.
To try and add another challenge there are four different countdown times. 
The theme for the game is Harry Potter as this is something my daughter has grown up with and loves
## UX: 
# User Goals
•	A game which challenges the player to remember where a picture card is positioned on the board.
•	Interactive game with playability on both desktop and mobile.
•	Smooth animation of cards rotating when clicked upon.
•	Incorporate sound when player interacts with a card.
•	Pop up animation on both win a lose outcomes.
•	Adhere to the imagery of the Harry Potter them:

## User ideas: 
# N Hobday: 
 "As a big fan of the Harry Potter franchise the game should incorporate images and sounds from this world. I would like the game to be fun, interactive and challenging. I would prefer to be able to play it on my mobile or tablet.”
# J Buckley: 
"The game should have a magical feel in line with the subject matter. Should by easy to use on mobile as I do not us the laptop for games. The game should be responsive so clicking on cards should trigger the card turn without delay and a countdown to add extra challenge."

## Requirements:
The requirements for the game are as follows.
•	Create a clock which counts down.
•	Create a counter to track the number of cards clicked.
•	Create front face and back face of the card.
•	Cards need to rotate and rotate back if no match.
•	If cards match, do not rotate back.
•	Enter cards into a match cards array.
•	Create difficulty through reducing the game time.
•	Winner animation is all cards turned before countdown reaches 0.
•	Game over animation displayed upon not turning all cards before countdown reaches 0.
•	Check for all cards turned and clock not 0.
•	No rotation of card if card is already turned.
•	Reset of game.
•	HP fonts.
•	HP images.
•	HP colour scheme.
•	HP music.


### Design:
#### The theme of this project is Harry Potter and therefore all page elements should be consistant with what everyone has come to expect from this world.
#### Card faces contain images of Harry Potter, Hermoine Granger, Hagrid, 9 ¾ station sign, the snitch, a phoenix, 
#### Card backs show house badges and badge will change depending on difficulty level.
#### Backdrop is an image of the grand hall in Hogwarts with floating candles.

### Fonts: 
#### harryp.ttf and lumos.ttf, back up with Caudex and Chelsea Market

### Colours: 
#### The colours that have been used throughout the game are in line with the theme. These are #9c1203, #e3a000, #2d004d, #033807 and #00165e.

### Images: 
#### The background image courtesy of https://harrypotter.fandom.com/.
#### Card face, back and animation images taken from Clipart Library, http://clipart-library.com/

### Bugs
#### Sound not working on card click. Now working and added as match cards sound. src link was wrong.
#### House badges not displaying when start button clicked.
#### Reset the click counter on restart.


### Testing:
#### Throughout the coding I have been able to test if functions have been called through adding console.log() at various stages. This code has now been removed from the final versio to keep the code clean.
#### Other testing has involved checking start buttons not active once game begins, unable to rotate if card already turned, ---------------

### Deployment:
web https://hob71.github.io/MP2---Memory-Madness/
gitpod https://github.com/hob71/MP2---Memory-Madness

### Credits:
#### First 9 lines for function turn() taken from freeCodeCamp.org.
#### Shuffle card code taken from youtube shuffle card tutorial.
#### As mention previously if would like to credit the source for the images used, https://harrypotter.fandom.com/ and http://clipart-library.com/.
#### For the animation code from https://www.codesdope.com/blog/article/css3-moving-cloud-animation-with-airplane/.
#### Sound of wand credits go to soundbible.com recorded by Mike Koenig.

### Acknowledge:
#### A big thank you must be give to my mentor, Simen, for his support and motivation through this project. Also for the support and understanding given by student care.

