**SOURCERER**


<img src="kaviss.png" height="50px" width="50px" alt=""/></a>

**CODE REQUIREMENTS**
1. Opencv(pip install opencv-python)
2. Tkinter(Available in python)
3. PIL (pip install Pillow)
4. Pandas(pip install pandas)

**WHAT STEPS YOU HAVE TO FOLLOW??**

1. Download my Repository
2. Create a Training Image folder in a project.
3. Open a index.py and change the all paths with your system path
4. Run index.py.


**PROJECT STRUCTURE**
1. After run you need to give your face data to system so enter your ID and name in box than click on Take Images button.
2. It will collect 200 images of your faces, it save a images in TrainingImage folder
3. After that we need to train a model(for train a model click on Train Image button.
4. It will take 5-10 minutes for training(for 10 person data).
5. After training click on Automatic Attendance ,it can fill attendace by your face using our trained model (model will save in TrainingImageLabel )
6. It will create .csv file of attendance according to time & subject.
7. You can store data in database (install wampserver),change the DB name according to your in AMS_Run.py.
8. Manually Fill Attendace Button in UI is for fill a manually attendance (without facce recognition),it's also create a .csv and store in a database.


**SCREENSCHOTS**

**BASIC UI**

**HOME PAGE**

<img src="img4.png">

**WHEN IT'S RECOGNISE ME**

**TAKE IMAGE**

<img src="img6.png">

**TRAINING IMAGE**

<img src="img5.png">

**MANNUAL ATTENDANCE FILLIING IT**

**FILL ATTENDANCE**

<img src="img2.png">

**MANUAL ATTENDANCE**

<img src="img9.png">

**ADMIN VISIT**

<img src="img3.png">

**DATABASE DESIGN**

<img src="img7.png">

<img src="img8.png">


**NOTES**

It will requires high processing power(I have 8 GB RAM & 2GB GC)

If you think it will recognise person just like humans, than leave it, its not possible.

Noist image can reduce your accuracy so quality of image matter,
