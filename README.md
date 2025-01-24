Hover Button Project

Features

Responsive and minimalist hover button design.

Smooth animations with keyframes.

Uses Google Fonts for a modern look.

Background animation for visual appeal.

File Structure

hoverButton/
|-- index.html       # Main HTML file
|-- button.css       # CSS file for styles and animations

How to Run

Navigate to the hoverButton directory:

cd hoverButton

Open index.html in your browser:

open index.html

Technologies Used

HTML5

CSS3 (with keyframe animations and transitions)

Key Features in CSS

Button Hover Effect

Transition: Smooth margin-bottom adjustment for a bounce-like effect.

Box Shadow: Adds glow when hovering over the button.

Border Color Change: Dynamic color highlighting.

Animation (Slide Down)

The button slides into view with the following animation:

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


This project is licensed under the MIT License. See the LICENSE file for details.
