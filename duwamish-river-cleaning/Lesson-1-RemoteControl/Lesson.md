# Summer Project: Cleaning the Duwamish River with Robots
## Overview
The Duwamish river has been greatly polluted in the past years by companies and public agencies. Cleaning the river will be dangerous and will take a long time. Let's use our coding and robotics skills to remotely clean the river!  

In this project you will build your own car robot, you will learn how to code it to control it with your laptop as a remote control and finally you will use your robot to clean the Duwamish river.

## Pre-requisites
1. Download the mblock3 app from [link](http://www.mblock.cc/software/mblock/mblock3/).
2. Double click on the downloaded file to install it.
3. Open the instructions to setup your robot [here](../resources/0_getting-started-with-mblock.pdf).
4. Go to page 7 for instructions to connect the robot to your laptop.
5. Follow the 4 steps to connect it.

When your robot is connected:
- The mblock app should say 'Connected to 2.4G Serial' at the top of the app
- Under the scripts tab, click on 'Robots'. There should be a green circle besides the mBot section.

## Coding 

### Move the robot when pressing a key
We will code our robot to _listen_ for keys that are pressed in your keyboard to do an action. Your robot can _listens_ to actions we do in the real world through *events*. We will code an event to listen for the right arrow key to start turning right when is pressed.

1. From events, drag 'when space key pressed' to workspace
2. From robots, drag 'run forward at speed 0' under the 'when space key pressed' block in the workspace  
<img src="../images/3_KeyboardController_img001.jpg" width="400" alt="The workspace should look like this">
3. Change 'space' to 'right arrow'
4. Change 'run forward' to 'turn right'
5. Change speed '0' to '100'  
<img src="../images/3_KeyboardController_img002.jpg" width="400" alt="The workspace should look like this">

Try pressing the right arrow in your keyboard. Your robot should start turning now! But... the robot doesn't stop when you stop pressing the right arrow!

How can you stop it from turning? Try changing the speed value and then pressing the right arrow in your keyboard and see what happens.

### Stop the robot when pressing a key
When your robot _listens_ for a key that was pressed, it actually _listens_ for when the key is pressed *and* for when the key is released.

We will now code our robot to also _listen_ for when you stop pressing the right arrow key to stop the robot. We will do this by coding a second event to listen for when the right arrow key was released. This will make the robot turn right while you press the right arrow key, but will stop moving when you release the key.

1. From events, drag 'when space key released' to workspace
2. From robots, drag 'run forward at speed 0' under the 'when space key pressed' block in the workspace
<img src="../images/3_KeyboardController_img003.jpg" width="400" alt="The workspace should look like this">
3. Change 'space' to  'right arrow'
4. Change 'run forward' to 'turn right'
5. Leave the speed as '0'  
<img src="../images/3_KeyboardController_img004.jpg" width="400" alt="The workspace should look like this.">


Try pressing the right arrow in your keyboard.  
Observe that while you hold the right arrow, the robot keeps turning.  
When you release the right arrow key, the robot stops turning.

> Your laptop is now a remote control for the robot!

What you coded is exactly what your game controler does to know what button you press when you play video games!

## Challenge: Finish coding a remote control

We learned how to make the robot to turn right when the 'right arrow' is pressed and make the robot stop when the 'right arrow' is released.

Let's make the robot smarter by coding the events for 3 other keys:

1. The 'left arrow' shoud make the robot 'turn left'
2. The 'up arrow' should make the robot 'run foward' 
3. The 'down arrow' should make the robot 'run backwards'

