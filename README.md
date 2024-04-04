# Z-Buffer Rendering Algorithm Implementation in C# and WinForms

This project is an implementation of the Z-buffer rendering algorithm using C# and WinForms. The Z-buffer algorithm, also known as the depth-buffer algorithm, is essential for rendering realistic 3D graphics by determining the visibility and rendering order of objects in a 3D scene.

## Introduction

The project aims to demonstrate the principles and functionality of the Z-buffer algorithm. It provides a user-friendly graphical interface for interacting with a 3D scene, where users can add, manipulate, and view objects in real-time.

## Features

- Render objects in 3D space using the Z-buffer algorithm
- Create and customize cubes with translation, rotation, and scaling options
- Control camera field of view (FOV) for viewing the scene
- Select individual objects or all objects in the scene
- Translate, rotate, and scale selected objects using intuitive controls

## Libraries Used

- **System.Drawing**: Core library for basic drawing functionality.
- **System.Collections.Generic**: Provides generic collection classes.
- **WinForms**: Graphical user interface framework.

## Usage

1. Clone the repository.
2. Open the project in Visual Studio or any C# IDE.
3. Build and run the application.
4. Interact with the 3D scene using the provided controls.

## Controls

### Screen/Scene Controls

- **R + Ctrl**: Reset scene to initial view.
- **O**: Decreases camera FOV.
- **P**: Increases camera FOV.
- **1 - 9**: Select the nth object in scene.
- **0**: Select all objects.

### Translation Controls

- **Right arrow/Left Arrow**: Translates selected objects towards negative/positive X.
- **Up/Down arrow**: Translates selected objects towards negative/positive Y.
- **Z/X**: Translates selected objects towards positive/negative Z.

### Rotation Controls

- **A/D**: Rotates selected objects around positive/negative origin Y.
- **Q/E**: Rotates selected objects around positive/negative origin Z.
- **W/S**: Rotates selected objects around negative/positive origin X.

### Scale Controls

- **.**: Upscales selected objects.
- **,**: Downscales selected objects.

## Video Demo

A video demo of the project can be found [here](https://www.youtube.com/watch?v=AldZxZBQfsw).

## Credits

This project was developed by [Rajaram Karki] for [Computer Graphics Projet]. 

For detailed implementation and code structure, refer to the project files.
