# Intelligence-Expeditious-Accident-Detection


OVERVIEW OF THE PROJECT
-----------------------
Detection of human error caused in driving a 4 wheeler vehicle to prevent accidents expeditiously. The idea behind the human error in driving is to detect the drowsiness of the driver by measuring the facial emotions over real time with the help of Computer Vision and Shape Predictor Model and alert the driver immediately. An alert message is send automatically by the system to the concerned ones if the driver persists in the non-stop dozing or yawning state in order to escape the mishap.The highest advantage of this system is to reduce the chance of human error by detecting it swiftly.

OBJECTIVE
---------
* This system invloves determining how long a given person’s eyes have been closed. If their eyes have been closed for a certain amount of time, we’ll assume that they are starting to doze off and play an alarm to wake them up and grab their attention.

* Apart from this, the system also tests for the same condition of yawning. In this, if the person yawns it would prompt another alert alarm for this to make him/her caution. There is also an another feature by providing the driver’s parents or closed ones specifying the detailed accurate response and expressions of the driver. We have integrated the scan code with the notifications.

* The secured scan code which had been provided to the closed ones can easily track the facial emotions and expressions of the driver seating in the car and let’s suppose when the driver’s response is Yawning a continuous vibration notification will be sent to their closed ones cell phone stating a message “Driver is Dozzy” so that they can take the required measures like calling or texting him/her to prevent causing accidents.

WORKING
-------
* At first, the human face is detected using Open CV and then the various poses are being captured where the closure of eyes is highly analyzed by the Shape Predictor model to find the signs of exhaustion in drivers in order to avoid a misadventure.

* Since a drowsy person can yawn at times, the same can be done for detecting ‘yawning’ too. If the person yawns while driving, it would prompt another alert alarm for this to make him/her caution. 

* After the detection, the model identifies if the driver is dozy or not by comparing with a threshold value to that of the real time. Then the system will alert the driver of the drowsiness.

* In case if the driver wears glasses while driving, detection of mouth is done to identify whether he/she is yawning which ultimately causes the alarm to ring .

* In addition to it, to overcome the drawbacks of the driver’s non-stop dozing or yawning state we will further make an alert message to the concerned ones in order to    escape the mishap.

TECHNOLOGY USED
---------------
* Python

* OpenCV - Open Source Computer Vision Library is an open source computer vision and machine learning software library. A computer vision system can detect the facial 
emotions and detection of eye and mouth outliners in a real time video streamand then alert the driver by prompting an alarm.

* Dlib - Dlib is a general purpose cross platform library written in the programming language in c++. It here used in detection of the facial landmark locaions.

* Shape Predictor 68 Face Landmarks [Trained Model]

