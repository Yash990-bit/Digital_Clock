# Digital Clock Project

This is a Digital Clock application built using HTML, CSS, and JavaScript. It displays the current time in hours, minutes, and seconds, with a visually appealing design and animations. The clock updates every second to show real-time changes.

## Features

- **Real-Time Clock**: Displays the current time (hours:minutes:seconds) with zero-padding for single digits.
- **Responsive Design**: The layout adjusts to different screen sizes, providing an optimized view for mobile and desktop devices.
- **Stylish UI**: The clock has a modern, sleek look with gradient backgrounds, shadow effects, and an animated container.

## Technologies Used

- **HTML5**: For structuring the page and displaying the clock.
- **CSS3**: For styling the page and creating animations.
- **JavaScript**: For the functionality of updating the clock in real-time.

## Installation

To run this project locally, follow these steps:

1. Clone the repository to your local machine:
    ```bash
    git clone https://github.com/Yash990-bit/Digital_Clock
    ```

## How It Works

1. **HTML (index.html)**:
    - Contains the layout of the clock, including the `span` elements that display hours, minutes, and seconds.

2. **CSS (style.css)**:
    - Styles the clock container with gradient backgrounds, shadows, and flexbox layout to center the time on the screen.
    - The design is responsive, with font size and container size adjusting according to screen width.

3. **JavaScript (script.js)**:
    - The JavaScript code uses `setInterval` to update the clock every second.
    - The time is fetched using the `Date()` function and displayed in `HH:MM:SS` format with leading zeros for values less than 10.

### Key Functions:

- **Real-time clock update**: 
    - The `setInterval` function updates the time every second.
    - The current hours, minutes, and seconds are displayed in `span` elements with IDs `hrs`, `min`, and `sec`.
  
## Demo

Here is a live demo of the Digital Clock:
[(https://bitfus.netlify.app/)] 


