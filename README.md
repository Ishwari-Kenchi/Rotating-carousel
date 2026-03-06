# Rotating-carousel
3D Rotating Image Carousel

A visually engaging 3D Rotating Image Carousel built using pure HTML and CSS.
This project demonstrates how CSS 3D transforms and animations can create a dynamic rotating gallery without using JavaScript or external libraries.
Link -  https://ishwari-kenchi.github.io/Rotating-carousel/

📌 Features

3D circular image layout

Smooth continuous rotation animation

Pure HTML + CSS implementation

Uses CSS 3D transforms

Lightweight and easy to integrate into any webpage

Responsive and visually appealing design

⚙️ Technologies Used

HTML5

CSS3

CSS 3D Transforms (rotateY, translateZ)

CSS Variables

CSS Animations (@keyframes)

🧠 How It Works

Each image is placed around a circular path using the following CSS transform:

transform: rotateY(calc(var(--i) * 45deg)) translateZ(350px);

Explanation:

rotateY() positions each image around a circle.

translateZ() pushes the image outward from the center.

--i is a CSS variable used to calculate the angle for each image.

@keyframes rotate continuously rotates the entire carousel.

This creates the illusion of a 3D rotating gallery.

📂 Project Structure
project-folder
│
├── index.html
└── README.md
