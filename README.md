# Piano_project
Developed the structure of the piano keys, styling them to look like a real piano, and adding functionality to produce sound when keys are pressed.
IMPLEMENTATION (HTML,CSS,JS)
1 HTML: Sets up the layout with div elements representing each piano key. Each key has a data-note attribute corresponding to the musical note it plays.
2 CSS: Styles the keys to look like a piano. White keys are wider and taller, while black keys are shorter and positioned to overlap between the white keys.
3 JavaScript:
Adds click event listeners to each key to play the corresponding sound when clicked.
Adds a keydown event listener to play sounds when the corresponding keyboard key is pressed.
The playSound function creates an Audio object for the note and plays it.
