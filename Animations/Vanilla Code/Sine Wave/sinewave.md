# Sine Wave HTML Page

## Overview
This Markdown document represents an HTML page that generates a sine wave animation with various interactive features. It includes HTML, JavaScript, and CSS code for creating the animation and provides user controls via the dat.GUI library.

## HTML
The HTML part of the code includes the following elements:
- `<!DOCTYPE html>`: Specifies the document type.
- `<html>`: The root HTML element.
- `<head>`: Contains metadata and external script and style references.
  - `<meta>`: Charset and viewport meta tags.
  - `<title>`: The title of the page.
  - `<script>`: Importing the dat.GUI library.
  - `<style>`: Internal CSS styles for canvas and the music player.
- `<body>`: The body of the page.
  - `<canvas>`: The canvas element for rendering the sine wave.
  - `<div>`: The music player with an embedded audio element.

## JavaScript
The JavaScript part of the code includes various scripts that create and manage the sine wave animation and interactive controls.
- Creating GUI controls for adjusting parameters using dat.GUI.
- Defining objects for wave settings, stroke colors, background colors, shapes, and trippy effects.
- Creating classes for particles and defining functions for particle animation.
- Animating the canvas to draw the sine wave, shapes, and trippy effects.
- Handling user interactions to switch between trippy effects and more.

## CSS
The CSS part of the code includes styling for the canvas and the music player.
- Styles for the canvas to make it block-level.
- Styles for the music player at the bottom of the page with a fixed position, background color, and text color.

## External Resources
- The code references an external JavaScript library, dat.GUI, via a CDN.
- It also uses an audio file "abstract.mp3" for the embedded music player.

## Interactive Features
- The animation parameters can be controlled via the dat.GUI interface, including wave properties, stroke colors, background colors, shapes, and trippy effects.
- Users can click on the canvas to switch between different trippy effects.

## Language Used
- HTML: For structuring the webpage.
- JavaScript: For creating animations and interactive controls.
- CSS: For styling the elements on the webpage.

This HTML page creates an engaging animation with user-controlled settings for an interactive experience.

## Created by
- Jason Leisure
