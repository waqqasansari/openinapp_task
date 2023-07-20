# openinapp_task
The objective of this assignment is to demonstrate your skills in creating an AI model that is proficient in
lip-syncing i.e. synchronizing an audio file with a video file. Your task is to ensure the model is accurately
matching the lip movements of the characters in the given video file with the corresponding audio file.

## Prerequisites

1. Python 3.6 or later
2. Wav2Lip
3. OpenCV (pip install opencv-python)
4. moviepy (pip install moviepy)

## working

Initially, extract the video frames containing faces from each frame. 
Subsequently, apply the model; note that the model will not function if any frame lacks a face.
