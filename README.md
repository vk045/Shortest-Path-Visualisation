Shortpath visualization:- An program created in python by use of pygame and tkinter as
application program interface which takes coordinates of source object and destination object
from user as input as well as the obstacles between them. The program consists of 48 X 48 boxes
created by G.U.I ,the coordinates range from (1,1) to (48,48).The source and detination can only have
coordinates in this range. The obstacles can also have the coordinates in this range. The program finds
the shortest path using A* search algorithm in terms of block.

The program should be executed in Pycharm for easiness.
The interpreter should be Project default(Python 3.7)
environment variable(Python unbuffered=1)

Steps to run the program::
Step 1.Execute the get_pip.py file to install the pip package.
Step 2.Run the install_requirements.py to install
  pygame A.P.I(Note:- The requirements.txt should be open and in the same folder)
Step 3.Open the .gitpod and .gitpod.dockerfile(the .gitpod gives reference to .gitpod.dockerfile)
  dockerfile ensures that the program on any instance starts with the correct docker image
Step 4.Run the path_finding.py to start the program.
Step 5.First enter the coordinated of source and destination between (1,1) and (48,48) 
  and click on the show step checkbox to see how it works
Step 6.Click on submit button.The selected objects i.e source and destination will turn pink.
Step 7.Click on the boxes to select obstacle.(you can also drag to create a line of obstacles).
Step 8.Enter spacebar.
Step 9.The program will calculate the shortest path and display it as a popup.
