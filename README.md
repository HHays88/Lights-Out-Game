The purpose of the game is to turn all the lights out (turn all the squares black) by tapping in the squares. 
Each tap turns on or off the lights in the square tapped and orthogonally adjacent squares.

This app uses the following concepts:
- Create a grid of 9 buttons with a "New Game" button below it using ConstraintLayout and a child GridLayout using
styles defined in themes.xml, colors defined in colors.xml, and strings defined in strings.xml.
- MainActivity.java is the controller activity that manipulates the model and updates the view.
- Created a landscape layout file so the device can be rotated without losing state and keeping buttons visible.
- Added multiple activities using fragments.
- Help activity has text layered over an image.
- Color activity changes the light colors.
- Set startActivity() to determine which activity opens at launch.
- Sending and receiving data to select different colors that updates in the game with intents.
