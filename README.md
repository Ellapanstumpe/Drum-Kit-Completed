# Drum-Kit Project

This is a simple, interactive web-based drum kit that allows users to play different drum sounds by either clicking on buttons or pressing specific keys on the keyboard. The project is built using HTML, CSS, and JavaScript, and it demonstrates basic concepts of DOM manipulation, event handling, and audio playback in web development.

Features
Interactive Buttons: Clickable drum buttons on the web page play corresponding drum sounds.
Keyboard Interaction: Users can also play drum sounds by pressing designated keys on their keyboard.
Visual Feedback: Buttons animate when clicked or when the corresponding key is pressed, providing a responsive and engaging user experience.
How It Works
Event Listeners:

The project uses JavaScript to add click event listeners to all buttons with the class .drum.
A keypress event listener is added to the entire document to detect when a key is pressed.
Playing Sounds:

When a button is clicked or a key is pressed, the inner HTML or the key value is passed to the makeSound function.
The makeSound function uses a switch statement to determine which sound to play based on the input.
Button Animation:

The buttonAnimation function temporarily adds a pressed class to the button, which adds a visual effect (like changing the button's appearance).
After 100 milliseconds, the animation effect is removed, returning the button to its original state.
Usage
Click the Drum Buttons:

Simply click on any drum button on the page to play the corresponding sound.
Use the Keyboard:

Press the keys w, a, s, d, j, k, or l on your keyboard to play the corresponding drum sound.
![WeChata2c3ab41f777d5429e17b9a297d344b5](https://github.com/user-attachments/assets/fbe0b722-18c8-4ce1-839d-aa6124ad59e3)

index.html: Contains the structure of the web page.
styles.css: Defines the styles and layout of the drum kit.
index.js: Contains the JavaScript logic for handling user interactions and playing sounds.
sounds/: A directory containing the drum sound files in .mp3 format.

#Installation

To run this project locally:

Clone the repository: git clone https://github.com/Ellapanstumpe/Drum-Kit-Completed.git
Navigate to the project directory: cd drum-kit
Open index.html in your web browser: open index.html

or visit following link to check out the completed project:
 https://drumkitfromella.netlify.app/ 
