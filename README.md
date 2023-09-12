# flexbox

Hosted link https://rajkumarrj.github.io/flexbox/


# Photo Gallery

This is a simple photo gallery built using HTML and CSS, showcasing a collection of cat images. It uses Flexbox for responsive layout and styling.

![Gallery Preview](https://cdn.freecodecamp.org/curriculum/css-photo-gallery/1.jpg)

## Table of Contents
- [Overview](#overview)
- [HTML Structure](#html-structure)
- [CSS Styling](#css-styling)
- [Usage](#usage)
- [License](#license)

## Overview

This project demonstrates how to create a responsive photo gallery using HTML and CSS. 
It's designed to display a collection of cat images, but you can easily replace them with your own images.

## HTML Structure

The HTML structure is straightforward.
It consists of a header with the title "css flexbox photo gallery" 
and a `div` element with the class "gallery" that contains a series of `img` elements, each with a source (`src`) attribute 
pointing to an image and an alternative text (`alt`) describing the image.


<!DOCTYPE html>
<html lang="en">
<head>
    <!-- Meta tags and title -->
</head>
<body>
    <header class="header">
        <h1>css flexbox photo gallery</h1>
    </header>
    <div class="gallery">
        <!-- Image elements here -->
    </div>
</body>
</html>


CSS Styling
The CSS styles are used to create a responsive and visually appealing photo gallery.
 It uses Flexbox to arrange the images in rows and columns.
 The gallery is centered on the page and has a maximum width of 1400px.
Each image is given a maximum width of 350px and a height of 300px, with rounded corners for a neat appearance.
