# Style Transfer App

A Python project for applying style transfer to images using PyTorch.

![alt text](https://github.com/Amir-Goudarzi/style-transfer-app/blob/main/examples/Example.jpg?raw=true)

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage and Configuration](#Usage-and-Configuration)

## Introduction

This project allows you to apply style transfer techniques to images using a smaller version of [Gatys et al's neural algorithm for artistic style](https://arxiv.org/abs/1508.06576). The results could be generated in a couple of minutes. It utilizes PyTorch and pre-trained VGG16 models to achieve this.

## Features

- Apply style transfer to images
- Customizable style and content images
- Configurable hyperparameters

## Installation

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/Amir-Goudarzi/style-transfer-app.git
2. Navigate to the project directory:
   ```bash
   cd style-transfer-app
3. Install the required Python packages from requirements.txt:
   ```bash
   pip install -r requirements.txt

## Usage and Configuration 

1. Specify the directories for style and content images
2. Adjust the hyperparameters (e.g., a and b for content and style loss) to control the output style
3. Run all the cells , visualize and save the generated image at then end
