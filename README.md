# Automatic-Attendance-System-Using-Computer-Vision

## Introduction --> 
Hola Amigos! <br> 
This system aims to simplify the regular attendance method by automating it with the help of face recognition and saving the precious time of student and faculty. <br>
For building this system we have used various concepts of Machine Learning and DeepLearning which can be found in PPT provided in this repo. <br>
This project is completely based on <b>PYHON.</b> <br>
So if you don't have python. Don't worry you can go ahead and download it from <a href="https://www.python.org/downloads/"> HERE </a>. <br>
Any Version above 3.6 would be a good fit.<br>

### Moules used --> 
<ul>
  <li >OpenCV Contrib 4.0.1</li>
<li >Pillow</li>
<li >Numpy</li>
<li >Pandas</li>
<li >Shutil</li>
  </ul>
  <b> Or run the following command in cmd/bash </b>
  <pre> pip install -r requirements.txt </pre>
  
### Run the code using: 
<pre>python3 main.py</pre>

### Features of System --> 
<ul>
  <li> Check Camera</li>
<li >Capture Faces</li>
<li >Train Faces</li>
<li >Recognize Faces & Attendance</li>
  </ul>
  Snippet for Same is below --> 
  <img src= "https://github.com/r-sajal/Automatic-Attendance-System-Using-Computer-Vision/blob/main/ResultImages/st1.jpg" >
  1. <b>Check Camera:</b> Checks if webcam is accessible or not<br>
  2. <b>Capture Faces:</b> Registers student with student ID and Student Name. 101 photos of wach student is taken and stored in imagetraining folder with student name and id as image name.<br>
  3. <b>Train Faces:</b> Creates a intermediate vector which will be used to recognize faces later on. Creates a Trainner.yml which will store all the intermediate vectors.<br>
  4. <b>Recognize Faces and Attendance: </b> opens webcam and mark attendance of student.<br>
  You have to press keys according to command you want to execute. <br>
  
  ### Things to keep in mind:
  Onces you start command 4 you can only escape by pressing key- q on keyboard.
  
  ### Results:
  Attendance file will be saved in attendane folder with date. <br>
  Some snapshots of working system are below.<br>
  <b> Not registered would look something like this. </b><br>
  <img src="https://github.com/r-sajal/Automatic-Attendance-System-Using-Computer-Vision/blob/main/ResultImages/Picture1.png">
  
  ### <b> Registered Student would look like below image. </b><br>
  <img src ="https://github.com/r-sajal/Automatic-Attendance-System-Using-Computer-Vision/blob/main/ResultImages/Picture2.jpg" style="height:400px;width:500px">
  
  

