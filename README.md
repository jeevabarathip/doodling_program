# doodling_program
# Interactive Doodling with Generative AI

![Doodle](doodle.png)

## Overview

This repository contains an interactive doodling program built using OpenCV and Generative AI. The program allows users to draw on a canvas using different colors and an eraser. Additionally, the AI generates creative descriptions of the doodles drawn by the user.

## Features

- Draw on the canvas: Use the 'd' key to enter drawing mode and move the cursor to create doodles.
- Color selection: Press 'r' for red, 'b' for blue, and 'g' for green. Use the 'e' key for an eraser (white color) to clear the canvas.
- Clear the canvas: Press 'c' to clear the entire canvas.
- AI-generated doodle descriptions: Press 'g' to let the AI generate a description of your doodle.
- Save the doodle: Press 's' to save the doodle as a PNG image.

## Requirements

To run this program, you need to have Python and the following libraries installed:

- OpenCV (`opencv-python`)
- Transformers (`transformers`)
- NumPy (`numpy`)

Install the required libraries using the following command:

```bash
pip install opencv-python transformers numpy
