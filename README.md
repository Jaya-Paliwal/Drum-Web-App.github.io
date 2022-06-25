# Drum-Web-App.github.io

[Deploy link is here](https://jaya-paliwal.github.io/Drum-Web-App.github.io/)

I developed the Drum WebApp. Its a fun project designed using Html, CSS and JavaScript.  Inside the body, Create a div element with the class of keys. Now each one of these keys here has a sound associated with it. For every key on the keyboard when we do key up or key down action, there is going to be something called the key code that is associated with that key. In our project, we are using ‘A’, ‘S’, ‘D’, ‘F’, ‘G’ ‘H’, ‘J’, ‘K’, ‘L’ keys to play the sounds of the drum kit. When we press any of the above keys on the keyboard then we’re going to play the corresponding audio element. Take an example, we press keycode 65 (‘A’) on the keyboard. Next, we are finding out is there an audio element on the page that has a data-key of 65 for that we are going to use document.querySelector() to select an audio element where it has a data — key same as e.keycode.

![WhatsApp Image 2022-06-25 at 4 59 42 PM](https://user-images.githubusercontent.com/91379324/175771680-ecc4fc35-a65b-41c6-a665-368ca6a9b733.jpeg)
