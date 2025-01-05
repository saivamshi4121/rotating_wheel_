Project Overview

This project demonstrates an interactive rotating wheel effect created using HTML and CSS. It features 3D perspective, depth animations, and dynamic lighting effects to provide an eye-catching and unique user interface. The wheel rotates continuously when hovered over and scales up with a glowing effect, making it visually appealing.

Features

3D Perspective and Depth Animation - The wheel appears to have depth, making it visually immersive.

Dynamic Lighting Animation - Subtle lighting effects around the wheel create a glowing, futuristic look.

Hover Interactions - Scaling and rotation effects activate when the user hovers over the wheel.

Gradient Background Animation - The background smoothly transitions colors, adding to the dynamic feel.

Responsive Design - The animation adjusts well to different screen sizes.

Live Demo

You can test the project live by opening the index.html file in your browser.

Installation

Clone the Repository

[https://github.com/your-github-username/rotating-wheel-animation.git](https://github.com/saivamshi4121/rotating_wheel_.git)

Navigate to the Project Directory

cd rotating-wheel-animation

Open in Browser
Open the index.html file in your favorite browser to see the rotating wheel effect in action.

File Structure

rotating-wheel-animation/
|-- index.html   # Main HTML file containing the code
|-- README.md    # Documentation file (this file)

Code Explanation

HTML Structure

The wheel consists of a container with nested segments for visual separation.

Additional divs for lighting and highlight effects enhance aesthetics.

CSS Animations

Keyframes for rotation, pulsing, and lighting are used to animate the wheel and background.

Hover Effects increase scale and initiate continuous rotation.

Conic Gradient divides the wheel into colorful segments.

Example CSS Snippet

@keyframes spin {
  0% { transform: rotate(0deg); }
  100% { transform: rotate(360deg); }
}

.wheel-container:hover .wheel-segments {
  animation: spin 5s infinite cubic-bezier(0.6, 0.04, 0.98, 0.335);
}

Customization Options

Colors: Modify the conic-gradient in the .wheel-segments class.

Speed: Adjust animation durations in the @keyframes definitions.

Size: Resize the .wheel-container and related elements proportionally.

Browser Compatibility

Chrome, Firefox, Safari, Edge, and Opera.

Contributing

Feel free to fork this repository and submit pull requests for improvements or additional features.

License

This project is licensed under the MIT License.

Author

Palamuri Saivamshi

LinkedIn: https://www.linkedin.com/in/sai-vamshi-328035282/

Email: palamurivamshi2005@gmail.com

