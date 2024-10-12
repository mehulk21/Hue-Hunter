# Real-Time Color Detection Project

## Overview
This project allows real-time color detection using a webcam or an image. The application reads pixel values from a video stream, compares them to a dataset of known colors, and displays the closest matching color name along with its RGB and hex code.

## Project Structure
- `Real Time Color Detection.py`: Python script that captures real-time video input, detects colors, and displays the corresponding color name and RGB values.
- `colors.csv`: Contains a dataset of color names along with their respective RGB and hex values.

## Dataset
The `colors.csv` file consists of color data, with each row representing a specific color:
- **Columns**: `color`, `color_name`, `hex`, `R`, `G`, `B`

## Libraries Used
- `OpenCV`: For image and video processing.
- `Pandas`: For handling the color dataset.
- `NumPy`: For numerical operations.

## Instructions to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/mehulk21/Real-Time-Color-Detection.git
