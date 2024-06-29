# Sleep Detection OpenCV

This project detects if a person is sleepy by analyzing the eye width and height ratio using the OpenCV module. The program uses the `scipy.spatial.distance` to detect landmarks of the eye and triggers an alarm when sleepiness is detected.

## Requirements

- Python 3.x
- OpenCV
- dlib
- imutils
- pygame
- scipy


# Download the pre-trained dlib model for facial landmarks:
    ```sh
    wget http://dlib.net/files/shape_predictor_68_face_landmarks.dat.bz2
    bzip2 -d shape_predictor_68_face_landmarks.dat.bz2
    mv shape_predictor_68_face_landmarks.dat models/
    ```

