# Face-Recognition-using-FaceNet


This face recognition system is implemented upon a pre-trained FaceNet model achieving a state-of-the-art accuracy.
The system comes with
both Live recognition & Image recognition.
It is trained on faces of some celebrities.



* __Installing dependencies:__
  * For Anaconda users: `conda install --file requirements.txt`<br>
  * For python users: `pip install -r requirements.txt`<br>
    (even Anaconda users can use this if they use anaconda prompt instead of terminal)

  
* __Training on other faces:__ <br>
To train model on different faces, follow the given steps:<br>
  1. Put the images containing clear frontal face.
  1. Open the repository directory in terminal and run following commands in given order:
     1. `cd script`
     1. `python generate_data.py`
  1. Follow program instructions.
  
* __Testing/Detecting faces:__ <br>
  1. __Face Recognition from Images__:
     1. Put the images containing the faces to predict.
     1. Open the repository directory in terminal and run following command:
      ```
          python image_recognition.py
      ```
     1. Output images will then be available.
   
  1. __Live Face Recognition(Obviously using camera):__
   <br>Open the repository directory in terminal and run following command:
      ```
      python live_recognition.py
      ```



__NOTE:__ Faces with __Unidentified__ labels are faces on which the model is not trained.

__Example__
<br>Before:<br>
<img src=https://github.com/ashukanderi/Face-Recognition-using-Facenet/blob/master/img1.jpg width=50%>
<br>After:<br>
<img src=https://github.com/ashukanderi/Face-Recognition-using-Facenet/blob/master/2ec945ecd5f7c08789f3ef5da5287410.jpg width=50%>

