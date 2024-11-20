## Tennis Analysis using OpenCV

### Introduction
The aim of this project is to develop and evaluate a computer vision system capable of accurately tracking the movement of a tennis ball and detecting players on the court in real-time. 
This project analyzes Tennis players in a video to measure their speed, ball shot speed and number of shots. This project will detect players and the tennis ball using YOLO and also utilizes CNNs to extract court keypoints. 

### Models Used
- YOLO v8 for player detection
- Fine Tuned YOLO for tennis ball detection
- Court Key point extraction
- Trained YOLOV5 model
- Trained tennis court key point model

### Requirements
- python3.8
- ultralytics
- pytroch
- pandas
- numpy
- opencv

### Setup Guide 
To set up the project locally, follow these step-by-step instructions:
- Clone the project repository from GitHub:

- Navigate to the project directory:
```
cd tennis_analysis
```

- Create a virtual environment (optional but recommended):
```
python -m venv env_name
```

- Activate the virtual environment:
```
env_name\Scripts\activate
```

- Install the project dependencies:
```
pip install -r requirements.txt
```

- Download the models from folder and paste it in the models folder

- Run the project:
```
python main.py
```

The project should now be up and running. 🚀

### Output

Screenshot from one of the output videos:
![Screenshot](input/tennis-output.jpeg)
