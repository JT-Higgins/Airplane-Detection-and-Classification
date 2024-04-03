# Satellite Imagery Airplane Detection

## Overview
This project focuses on developing a machine learning model capable of detecting airplanes in satellite images. By utilizing a dataset of over 32,000 labeled 20x20 RGB images extracted from Planet satellite imagery, this initiative aims to automate the classification of images containing airplanes versus those without. The core challenge addresses the need for efficient analysis amidst the burgeoning volume of daily captured satellite images, catering to applications in agriculture, defense, energy, and more.

## Objective
To build and train a Convolutional Neural Network (CNN) that can accurately identify and classify satellite images as either containing an airplane or not. This technology sets the foundation for various applications, including but not limited to monitoring airport activity, tracking aircraft movement, and notably, aiding in the search and rescue operations for plane crashes.

## Potential Impact
The automation of airplane detection in satellite images holds transformative potential across several sectors:
- **Defense and Intelligence**: Enhances surveillance capabilities and situational awareness.
- **Civil Aviation**: Monitors airport traffic and airplane logistics for operational efficiency.
- **Disaster Response**: Crucially, this project has the potential to significantly aid in locating downed aircraft, facilitating quicker response times in search and rescue operations, and potentially saving lives.

## Project Structure
- `data/`: Contains the dataset of satellite images, segregated into 'plane' and 'no-plane' categories.
- `models/`: Directory for storing trained model files.
- `notebooks/`: Jupyter notebooks detailing data exploration, model training, and evaluation processes.
- `src/`: Source code for data preprocessing, model training, and image classification scripts.
- `requirements.txt`: Lists the Python dependencies for the project.

## Getting Started
To get started with this project, clone the repository and install the required Python packages using:
- git clone https://github.com/your-github-username/satellite-imagery-airplane-detection.git
- cd satellite-imagery-airplane-detection
- pip install -r requirements.txt



