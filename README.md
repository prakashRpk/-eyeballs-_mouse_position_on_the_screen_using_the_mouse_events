# Eyeball Follower

This project is an interactive web application that simulates eyeballs following the mouse cursor. The background features an eerie image to enhance the spooky effect. The application demonstrates the use of HTML, CSS, and JavaScript to create a fun and engaging user experience.

## Demo

You can view a live demo of the project [here](#).  
*(Replace the `#` with the URL to your hosted project, if available.)*

## Features

- Two eyeballs that track the mouse movements in real-time.
- A spooky background image that enhances the overall effect.
- Responsive design that works across various screen sizes.

## How It Works

1. **HTML Structure**: 
   - The structure contains a `div` for each eyeball, which displays an image representing the eye.

2. **CSS Styling**:
   - The background image is set to cover the entire viewport.
   - Each eye is styled to have a dark color and position them properly on the screen.

3. **JavaScript Functionality**:
   - The JavaScript code listens for mouse movements and adjusts the position of the eyeballs using the `transform` property to create a "following" effect.

## Installation

To run this project locally:

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/eyeball-follower.git
   cd eyeball-follower
   open index.html
## Customization
You can change the background image by modifying the background-image URL in the CSS.
The eyeball images can also be updated by changing the src attribute of the <img> tags in the HTML.
Adjust the size and position of the eyes by modifying the CSS properties in the .eye and .eyeball classes.
