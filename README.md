**Code Requirements**
1. Opencv(pip install opencv-python)
2. Tkinter(Available in python)
3. PIL (pip install Pillow)
4. Pandas(pip install pandas)


What steps you have to follow??

Download my Repository

Create a TrainingImage folder in a project.

Open a AMS_Run.py and change the all paths with your system path

Run AMS_Run.py.


Project Structure
After run you need to give your face data to system so enter your ID and name in box than click on Take Images button.
It will collect 200 images of your faces, it save a images in TrainingImage folder
After that we need to train a model(for train a model click on Train Image button.
It will take 5-10 minutes for training(for 10 person data).
After training click on Automatic Attendance ,it can fill attendace by your face using our trained model (model will save in TrainingImageLabel )
it will create .csv file of attendance according to time & subject.
You can store data in database (install wampserver),change the DB name according to your in AMS_Run.py.
Manually Fill Attendace Button in UI is for fill a manually attendance (without facce recognition),it's also create a .csv and store in a database.
