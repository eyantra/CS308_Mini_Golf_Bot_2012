2012 - CS308  Group 6 : Project Mini Golf Robot README TEMPLATE
================================================

Group Info:
------------

Vaibhav Gupta		09005019
Arup Kumar Pal		09005024
Neeraj Toshniwal	09005039
Shrikant Nagori		09005040

Extension Of :
------------

Extension of Tennis Ball Collector Project from previous to previous year(2010)

Project Description
-------------------
The aim of the project is to design a golf playing bot. The game is played on a 4ft x 4ft plywood arena covered with velvet.
Given a hole marked by a blue flag and red foosball,the bot will try to hit the ball as accurately as possible.
The project was divided into many tasks and each task was handled separately and then merged finally.Major part
of the project was making of the required hardware.

Camera was attached at the top of the bot which aims at capturing a image in which the ball is in centre of the frame.
On finding it, it moves towards the ball and searches for blue flag and on success, it align itself in such a way so that
bot, ball and flag are collinear. Angle of inclination of inclined plane is computed from capturing the seemingly height
of the flag from the frame captured. Once it is calculated the angle of inclination plane is set and ball is allowed to 
roll freely. If ball enters the hole the game ends otherwise the above procedure is repeated. 
 

Technologies Used
-------------------

+   Embedded C
+   MATLAB
+   Xbee
+   X-CTU
+   Specialized Hardware

Setup the Project
-----------------

To run the project,open the Codes folder(in the Mini_Golf_Robot folder) in AVR studio and then you can run the project.

Installation Instructions
=========================

You can get all details regarding Matlab and get started with matlab following the link below:
	http://www.mathworks.kin/help/techdoc/

You can download setup of X-CTU(executable file) from link below:
	http://ptf.com/get/11469/
You can run the setup and X-CTU software will be installed.

References
=========== 

+ Eyantra (http://www.e-yantra.org/home/)
+ All details regarding Matlab (http://www.mathworks.in/help/techdoc/)
+ Matlab User Guide ( http://www.mathworks.in/help/pdf_doc/matlab/getstart.pdf)
