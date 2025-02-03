# OpenGL Model Loading and Animation

This repository demonstrates how to load 3D models and perform skeletal animation using OpenGL. It provides a practical implementation and serves as a learning resource for computer graphics enthusiasts.

## Overview

This project covers two main areas:

1.  **Model Loading:** Demonstrates how to load 3D models from common file formats (e.g., OBJ, FBX) into your OpenGL application.
2.  **Skeletal Animation:** Showcases how to animate models using skeletal animations.

## Folder Structure

The repository is organized as follows:

*   **`01_ModelLoading`**: Contains the code and resources for loading and rendering a 3D model.
*   **`02_SkeletalAnimation`**: Contains the code and resources for implementing skeletal animation.
*   `.gitignore`: File for excluding untracked files in git.
*   `README.md`: This file.

## Screenshots

### Model Loading:

The `01_ModelLoading` folder shows how to load and render a 3D model as depicted in the following screenshots:

![Model Loading Image 1](MLS1.png)
![Model Loading Image 2](MLS2.png)

### Skeletal Animation:

The `02_SkeletalAnimation` folder demonstrates how to load a model with an armature and implement skeletal animation. The following screenshots showcase the result of this implementation:

![Skeletal Animation Image 1](MLA1.png)
![Skeletal Animation Image 2](MLA2.png)

*Make sure to replace the `ModelLoadingImage1.png` and other placeholders with the actual image file names you use in the repository*

## How to Use

1.  **Clone:** Clone this repository to your local machine.
2.  **Dependencies:** Make sure you have OpenGL and a suitable C++ compiler setup. You might also need libraries like GLFW (for window creation) and GLM (for math).
3.  **Navigate:** Open the folder of interest (either `01_ModelLoading` or `02_SkeletalAnimation`).
4.  **Build & Run:** Follow the instructions in the respective folders to compile and run the examples.
5.  **Experiment:** Feel free to modify the code or use your own 3D models to experiment with the implementations.

## Compilation Instructions (General)

Typically, you would compile the C++ code using a command similar to the following:

```bash
g++ main.cpp -o my_opengl_app -lGL -lglfw -lGLEW
