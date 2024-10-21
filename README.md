Cat Meme Picker
A simple web application that allows users to choose a cat meme based on their current emotion and preference for animated GIFs.

What the app can do
Choose cat memes that match your emotion
Option to show only animated GIFs
Randomly select a meme from the available options
Highlights the chosen emotion
Adapts to different screen sizes
How it works
Emotion buttons: Choose your current emotion from a list
GIF Filter: You can choose to see only animated GIFs
"Get Image" button: Displays a random meme that matches your emotion and preference
Pop-up window: The selected meme appears in a window that can be closed
How to use the app
Choose an emotion from the available list
If you want, check the "Animated GIFs only" option
Press the "Get Image" button to see a meme
The meme will appear in a pop-up window that you can close
How to run the project
Download the project files
Open the index.html file in your browser to view the app
Or, use a simple local server and access the project in the browser
Project files
data.js: Contains information about the memes
index.js: Controls the functionality of the app
index.html: The main web page
index.css: Styles the appearance of the app
How the data for a meme looks
jsx
Copy code
{
  emotionTags: ["happy", "relaxed"],
  isGif: true,
  image: "happy.gif",
  alt: "A cat looking happy"
}
This structure describes a meme, including the associated emotions, whether it's a GIF, the filename, and a description for accessibility.

