# Description: 
Effect of delay intervals of teacher joining the live class on student's attendance in lectures.

Dataframe 1: For a respective lecture; strength of students, students attending the lecture, attendance%, students attending within different delay intervals is calculated.
In the data we have excluded the lectures where the present students is zero.

Dataframe2 :For a respective teacher we have calculated average delay time of all the lectures conducted by them. For each distinct teacher we have average strength of students/present students/attendance% in all the lectures conducted by them.

Delay is the difference between the scheduled time of the lecture and the actual start time of the lecture. The actual start time of the lecture is extracted when the teacher starts the class for the first time. Excluded the cases where teacher starts the class and leaves the class multiple times or in case of power cut or internet issue. The very first time when teacher clicks on start live class is considered here.

Attendance is the present students divided by the total strength of students of the lecture.

# DataSet:
https://drive.google.com/file/d/1qmWWOwBD6UMlUFYVYCIu3PkJ1qKa1zTN/view?usp=sharing

# Python Libraries Used: 
numpy,

pandas,

matplotlib,

seaborn

# Set up 
$ pip install numpy

$ pip install pandas

$ pip install matplotlib

$ pip install seaborn

# Analysis: 
1. As the delay increases the attendance distribution decreases.
The more is the delay of teacher starting the live class, the lesser is attendance in the lectures.

2. For teachers whose average delay>10min, attendance reduces drastically.

The difference between the 2 dataframes: 

In first we plotted attendance for lectures with various delays of teacher. In second we plotted average attendance of students of all lectures for a respective teacher post calculating average delays of each teacher joining the live class. We did this in order to be crystal clear of the analysis.
