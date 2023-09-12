I have used face-api.js which is a JavaScript face recognition API for the browser and has Node.js implemented on top of tensorflow.js core (tensorflow/tfjs-core).
For further info, look into
[Face-Api](https://github.com/justadudewhohacks/face-api.js/).

## Features of YES MAAM
The web app enables tracking attendance using facial recognition. The application allows a new user to sign up as a lecturer or a student. The student upon signing up has to upload two photos(from webcam or disk) to get the facial features stored in 128Dimensions. 
The student can enroll in a course based on a course id and can view his attendance. <br>The app gives functionality to the lecturer to create any course of his choice. For that given course, the teacher can create an attendance form either in Remote Mode or 
in Face To Face(F2F) Mode. In the attendance room, the professor can either  select "Remote" or "F2F"<br>

For "Remote Attendance", there will be a camera opened at the student's browser when entering the room. 
For "Face to Face Attendance", there will be a camera opened at the lecturer's browser when entering the room.
The lecturer can also "Kick" a student out of a course.<br>
The face photo of the student who is kicked out will not be counted next time taking the attendance.
In the attendance list page, the lecturer can visualize the attendance data by clicking the "Attendance Record" button in the action tab.<br>
After the attendance, the teacher can even close the attendance room so that no more transactions will be done by students.






