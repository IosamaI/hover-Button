# Hover Button Project

## Features

- Responsive and minimalist hover button design.
- Smooth animations with keyframes.
- Uses Google Fonts for a modern look.
- Background animation for visual appeal.

## File Structure

    hoverButton/
    |-- index.html       # Main HTML file
    |-- button.css       # CSS file for styles and animations

Animation (Slide Down)
The button slides into view with the following animation:

css
Copy
Edit
@keyframes slideDown {
    0% {
        top: 0;
        opacity: 0;
    }
    100% {
        top: 50%;
        transform: translateY(-50%);
        opacity: 1;
    }
}
