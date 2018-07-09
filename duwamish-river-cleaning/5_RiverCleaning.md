# Forward Block
### Create a new block
1. Data&Blocks -> Make a Block
2. Type "Run Forward"
3. Options -> Add number input
4. Options -> Add label text
5. Type "seconds"
6. Click OK
This block will move the car forward X seconds.

### Define the behavior of the new block
Update 'run forward X sec' block behavior:
1. Drag block into workspace (if none exists in the workspace)
2. Drag Robots -> 'run forward' at speed '100' into block
3. Drag Control -> wait '1' sec
4. Drag Robots -> 'run forward' at speed '0' into block

# Turn Right Block
### Create a new block
Data&Blocks -> Make a Block
1. Type "Turn Right"
2. Options -> Add number input
3. Options -> Add label text
4. Type "seconds"
2. Click OK
This block will turn the car to the right X seconds.

### Define the behavior of the new block
Update 'Turn Right X sec' block behavior:
1. Drag block into workspace (if none exists in the workspace)
2. Drag Robots -> 'run forward' at speed '100' into block
3. Select 'Turn Right'
4. Drag Control -> wait '1' sec
2. Drag Robots -> 'run forward' at speed '0' into block
3. Select 'Turn Right'

# Ruler
We will make a ruler with pen and paper to help us plan the path to automate our robot
    1. Place paper parallel to the robot on the side and mark with pen the location of the 'eyes' (distance sensor)
        <img src="images/step_01_1.jpg" height="400" alt="Before running mBot forward 1 second">
    2. Code and run algorithm
        1. When 'Flag' clicked
        2. Run forward 1 sec
        3. Click 'Flag'  
        <img src="images/step_01_2.jpg" height="400" alt="After running mBot forward 1 second">
    3. Mark with pen the new location of the 'eyes' (distance sensor)  
        <img src="images/step_01_3.jpg" height="400" alt="After running mBot forward 1 second">
    4. Cut a rectangle and make 10 marks for each tenth of a second.  
        <img src="images/step_02_1.jpg" height="400" alt="After running mBot forward 1 second">
        <img src="images/step_02_2.jpg" height="400" alt="After running mBot forward 1 second">
This ruller measures how far the robot will move per second. It will allow us to plan the path of the robot.

# Circular Ruler
We will make a circular ruler with pen and paper to help us plan the path to automate our robot
1. Place a small tape in front of the 'eyes' (distance sensor)  
    <img src="images/step_03_1.jpg" height="400" alt="Before running mBot forward 1 second">
2. Code and run algorithm:
    1. When 'Flag' clicked
    2. Run forward 1 sec
    3. Click 'Flag'  
    <img src="images/step_03_2.jpg" height="400" alt="Before running mBot forward 1 second">
3. Place a new small tape in front of the 'eyes' (distance sensor)  
    <img src="images/step_03_3.jpg" height="400" alt="Before running mBot forward 1 second">
4. With paper on top of the tapes, make a mark on the paper where both tapes are.  
    <img src="images/step_04_1.jpg" height="400" alt="Before running mBot forward 1 second">
5. Using a compass draw a circle that passes through both marks.  
    <img src="images/step_04_2.jpg" height="400" alt="Before running mBot forward 1 second">
    <img src="images/step_04_3.jpg" height="400" alt="Before running mBot forward 1 second">
6. Cut the circle with scissors  
    <img src="images/step_05_1.jpg" height="400" alt="Before running mBot forward 1 second">
7. Follow the pictures below to mark: 1 second, .5 second, 1.5 seconds, and 90 degrees  
    <img src="images/step_06_1.jpg" height="400" alt="Before running mBot forward 1 second">
    <img src="images/step_06_2.jpg" height="400" alt="Before running mBot forward 1 second">
    <img src="images/step_06_3.jpg" height="400" alt="Before running mBot forward 1 second">  
    <img src="images/step_07_1.jpg" height="400" alt="Before running mBot forward 1 second">
    <img src="images/step_07_2.jpg" height="400" alt="Before running mBot forward 1 second">
    <img src="images/step_07_3.jpg" height="400" alt="Before running mBot forward 1 second">
    <img src="images/step_07_4.jpg" height="400" alt="Before running mBot forward 1 second">
This circle ruller measures how far the robot will turn per second. It will allow us to plan the path of the robot.

# Robot Arm Extension
1. Roll a large piece of paper thinner than a pen.  
    <img src="images/step_08_1.jpg" height="400" alt="Before running mBot forward 1 second">
    <img src="images/step_08_2.jpg" height="400" alt="Before running mBot forward 1 second">
2. Insert the paper in the front of the robot.  
    <img src="images/step_08_3.jpg" height="400" alt="Before running mBot forward 1 second">
2. Twist the paper to make an extended arm.  
    <img src="images/step_08_4.jpg" height="400" alt="Before running mBot forward 1 second">

#Challenge
Using only the two new blocks, write an algorithm to push one paper ball out of the river. 
Use your rulers to plan the path that your robot has to follow to push the paper ball.

###Challenge setup  
<img src="images/challenge_01.jpg" height="400" alt="Before running mBot forward 1 second">
<img src="images/challenge_02.jpg" height="400" alt="Before running mBot forward 1 second">
<img src="images/challenge_03.jpg" height="400" alt="Before running mBot forward 1 second">

###Tips
1. Measure how many 'seconds' you need to move forward from the starting point.
2. Measure how many 'seconds' you need to turn right.
3. Measure how many 'seconds' you need to move forward after turning and push the paper.
4. Use the new blocks to code your path.  
<img src="images/step_09_1.jpg" height="400" alt="Before running mBot forward 1 second">
<img src="images/step_09_2.jpg" height="400" alt="Before running mBot forward 1 second">
<img src="images/step_09_3.jpg" height="400" alt="Before running mBot forward 1 second">  
<img src="images/step_09_4.jpg" height="400" alt="Before running mBot forward 1 second">
<img src="images/step_09_5.jpg" height="400" alt="Before running mBot forward 1 second">
<img src="images/step_09_6.jpg" height="400" alt="Before running mBot forward 1 second">
<img src="images/step_09_7.jpg" height="400" alt="Before running mBot forward 1 second">
<img src="images/step_09_8.jpg" height="400" alt="Before running mBot forward 1 second">

### Attempt Examples
<img src="images/attempt_fail_01.gif" height="400" alt="Before running mBot forward 1 second">
<img src="images/attempt_fail_02.gif" height="400" alt="Before running mBot forward 1 second">
<img src="images/attempt_fail_03.gif" height="400" alt="Before running mBot forward 1 second">
<img src="images/attempt_success_01.gif" height="400" alt="Before running mBot forward 1 second">

#Notes
We can ease the program by changing the 'turn right' speed to '60'. This will make a 90 degree angle per turn over a clean surface with minimal friction, such as paper. If you need to run the robot on a different surface, you'll need to adjust the turn speed.
