# FaceRecognition

#### install the dependencies in a virtual environment by following this link
https://github.com/ageitgey/face_recognition

create folder structure like below:

face_rec_example.py
known_faces
     -folder1
     -folder2    
unknown_faces
     -img.jpg
     -img2.jpg
     .....
test_face_result
    --after running the python file recognised faces from unknown_faces directory will be saved here
    
To run -
activate your created viurtual environment for this project (conda or venv)
go to the project directory
then run :- python face_rec_example.py
output will be displayed on screen and also saved in test_face_result folder
