#accidental.ly

Accidental.ly is a minigame designed to help music students practice reading sheet music. Users will have 15 seconds to identify as many notes as possible placed on a grand staff. 

![](https://media.giphy.com/media/SnDmTb4FkmIrslGlrk/giphy.gif)

###Getting Started

After cloning the repo, you will need to run `npm install` in order to download the appropriate packages. You will then need to host a server by running `node server/index.js`. Finally, you can run `npm start` to spin the app up. This should open a window in your default browser with the app. If not, navigate to http://localhost:3000.  

###Playing the Game

Input is done via typing a note name and hitting enter to submit. Users can input their name in the bottom field, which will enable the saving of high scores. Results being tracked are the number correct and incorrect, and high scores are displayed in a scrolling div on the header of the page. 

