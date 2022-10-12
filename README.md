# lane-detection
cv project for detecting lanes while driving<br>
<br>
1. Extracting a frame’s data from the video<br>
2. Converting a frame from the video to RGB from BGR<br>
3. Getting the frame shape (height and width)<br>
4. Defining a region of interest to run the algorithm on, we chose an ROI in a shape of a
small triangle so that it will cover the width of the driving lane and will converge ahead
of the car<br>
5. Defined two functions, one that is covering everything else that it is not in our region 
of interest, and the other one is a function for drawing the lines of the lanes.<br>
6. Starting a while loop for the code to run on each frame at a time<br>
7. Converted the image to gray scales and applied canny mask on it, after that we used
the function that covers everything else part for our ROI, on the canny image we created<br>
8. Applied the lanes function to draw the lanes on the frame <br>
