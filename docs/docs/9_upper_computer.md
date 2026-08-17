# 5. PC Software Learning

## 5.1 PC Software Interface Introduction

PC software is a system built-in software for programming robot action. You can use it to control the servo movement, adjust servo deviation and color threshold.

This lesson will introduction the layout and function of PC software.

### 5.1.1 Start PC Software

* **Use Desktop Icon (for beginner)**

(1) Double click <img src="../_static/media/chapter_9/section_1/image2.png" style="width:50px;" /> to open PC software.

(2) Click **"Execute"** in the pop-up window and open PC software.

<img class="common_img" src="../_static/media/chapter_9/section_1/image3.png"  />

* **Use Command Line**

(1) Click on <img src="../_static/media/chapter_9/section_1/image4.png" style="width:0.31458in;height:0.27361in" /> to open command line terminal.

(2) Enter the command and press "**Enter**" to start PC software.

```bash
python3 ArmPi_mini/armpi_mini_software/ArmPi_mini.py
```

### 5.1.2 Software Interface Layout

PC software has two function interfaces including normal mode and camera tool.

* **Normal Mode**

Under normal mode, you can control servo, adjust deviation and calibrate position. The interface is shown below:

<img class="common_img" src="../_static/media/chapter_9/section_1/image6.png"  alt="loading" />

(1) Language Option

The language of PC software can be switched between Chinese and English. It will synchronize with the interface language of camera tool.

(2)  Servo Control Area

The icons on servo control area correspond to five servos of robotic arm. You can rotate servo by dragging the corresponding slider. 

<img class="common_img" src="../_static/media/chapter_9/section_1/image7.png" style="width:1.1811in;height:1.06099in" alt="loading" />

| **Icon** | **Function** |
|:--:|:--:|
| <img src="../_static/media/chapter_9/section_1/image8.png" style="width:1.1811in;height:0.21984in" alt="loading" /> | Servo ID number. Here it refers to ID1 servo. |
| <img src="../_static/media/chapter_9/section_1/image9.png" style="width:1.1811in;height:0.63011in" alt="loading" /> | Servo slider (big slider) is used to adjust servo angle. It ranges from 500 to 2500, corresponding to angles 0°-180°. The middle value of 1500 corresponding to 90 degrees. |
| <img src="../_static/media/chapter_9/section_1/image10.png" style="width:1.1811in;height:0.27025in" alt="loading" /> | Deviation slider (small slider) is used to adjust servo deviation. It ranges from -150 to 150, corresponding to angle -13°-13°. |

(3) Inverse Kinematics Control Area 

This area is mainly for calibrating the gripping position of robot arm. If the gripping position is incorrect during using robotic arm, you can adjust its position in this area.

<img class="common_img" src="../_static/media/chapter_9/section_1/image11.png" style="width:1.9685in;height:2.63137in" alt="loading" />

<table class="docutils-nobg" border="1">
<colgroup>
<col style="width: 35%" />
<col style="width: 64%" />
</colgroup>
<tbody>
<tr>
<td style="text-align: center;"><strong>Icon</strong></td>
<td style="text-align: center;"><strong>Function</strong></td>
</tr>
<tr>
<td style="text-align: center;"><img src="../_static/media/chapter_9/section_1/image12.png" style="width:1.5748in;height:0.33461in" alt="loading" /></td>
<td style="text-align: left;">(Take robot as the first ) Used to control the gripper to move left or right.</td>
</tr>
<tr>
<td style="text-align: center;"><img src="../_static/media/chapter_9/section_1/image13.png" style="width:1.5748in;height:0.2699in" alt="loading" /></td>
<td style="text-align: left;">(Take robot as the first ) Used to control the gripper to move forward and backward.</td>
</tr>
<tr>
<td style="text-align: center;"><img src="../_static/media/chapter_9/section_1/image14.png" style="width:1.5748in;height:0.29717in" alt="loading" /></td>
<td style="text-align: left;"><p>Used to control the gripper to move up and down.</p>
<p>Note: the program has set the z-axis value to 1cm and the gripper will be in the middle of the two sides of the block, so it is not commended to modify this value.</p></td>
</tr>
<tr>
<td style="text-align: center;"><img src="../_static/media/chapter_9/section_1/image15.png" style="width:1.5748in;height:0.34171in" alt="loading" /></td>
<td style="text-align: left;">The angel between gripper and x axis. Due to the program settings, it does not need to modify.</td>
</tr>
<tr>
<td style="text-align: center;"><img src="../_static/media/chapter_9/section_1/image16.png" style="width:1.5748in;height:0.25772in" alt="loading" /></td>
<td style="text-align: left;">The movement time used by the gripper to move from the previous position to the set coordinate value. (just for checking the running effect ) </td>
</tr>
<tr>
<td style="text-align: center;"><img src="../_static/media/chapter_9/section_1/image17.png" style="width:0.7874in;height:0.42323in" alt="loading" /></td>
<td style="text-align: left;">Read the current position information of gripper</td>
</tr>
<tr>
<td style="text-align: center;"><img src="../_static/media/chapter_9/section_1/image18.png" style="width:0.7874in;height:0.39833in" alt="loading" /></td>
<td style="text-align: left;">Save the adjusted position coordinate value</td>
</tr>
<tr>
<td style="text-align: center;"><img src="../_static/media/chapter_9/section_1/image19.png" style="width:1.5748in;height:0.42589in" alt="loading" /></td>
<td style="text-align: left;">Control robot to the set coordinate value.</td>
</tr>
</tbody>
</table>

(4) Action Date List

The action data list will display the running time of each action and the value of each servo.

<img class="common_img" src="../_static/media/chapter_9/section_1/image20.png"  alt="loading" />

| **Icon ** | Function |
|:--:|:--:|
| <img src="../_static/media/chapter_9/section_1/image21.png" style="width:0.98425in;height:0.27648in" alt="loading" /> | Action number |
| <img src="../_static/media/chapter_9/section_1/image22.png" style="width:0.98425in;height:0.24528in" alt="loading" /> | Running time |
| <img src="../_static/media/chapter_9/section_1/image23.png" style="width:0.98425in;height:0.33788in" alt="loading" /> | Double click the value<img src="../_static/media/chapter_9/section_1/image24.png" style="width:0.59583in;height:0.16667in" alt="loading" />under this ID to modify. |

(5) Action Setting Area

<table class="docutils-nobg" border="1">
<colgroup>
<col style="width: 28%" />
<col style="width: 71%" />
</colgroup>
<tbody>
<tr>
<td style="text-align: center;"><strong>Icon</strong></td>
<td style="text-align: center;"><strong>Function</strong></td>
</tr>
<tr>
<td style="text-align: center;"><img src="../_static/media/chapter_9/section_1/image25.png" style="width:1.37795in;height:0.30256in" alt="loading" /></td>
<td style="text-align: left;">The time required to run a single action. You can click it to modify.</td>
</tr>
<tr>
<td style="text-align: center;"><img src="../_static/media/chapter_9/section_1/image26.png" style="width:1.37795in;height:0.2319in" alt="loading" /></td>
<td style="text-align: left;">The total time for running an action group</td>
</tr>
<tr>
<td style="text-align: center;"><img src="../_static/media/chapter_9/section_1/image27.png" style="width:0.98425in;height:0.58111in" alt="loading" /></td>
<td style="text-align: left;">Add the current action in servo control area to the last line of the action data list.</td>
</tr>
<tr>
<td style="text-align: center;"><img src="../_static/media/chapter_9/section_1/image28.png" style="width:0.98425in;height:0.40138in" alt="loading" /></td>
<td style="text-align: left;">Delete all the selected actions in action data list</td>
</tr>
<tr>
<td style="text-align: center;"><img src="../_static/media/chapter_9/section_1/image29.png" style="width:0.98425in;height:0.39835in" alt="loading" /></td>
<td style="text-align: left;">Delete all the actions in action data list</td>
</tr>
<tr>
<td style="text-align: center;"><img src="../_static/media/chapter_9/section_1/image30.png" style="width:0.98425in;height:0.41849in" alt="loading" /></td>
<td style="text-align: left;"><p>Replace the value of the selected actions in action data list.</p>
<p>(The value will be replaced with the current servo value in servo control area, and the running time will be replaced with the set running time.)</p></td>
</tr>
<tr>
<td style="text-align: center;"><img src="../_static/media/chapter_9/section_1/image31.png" style="width:0.98425in;height:0.38262in" alt="loading" /></td>
<td style="text-align: left;"><p>Insert a line of action in front of the selected action</p>
<p> </p></td>
</tr>
<tr>
<td style="text-align: center;"><img src="../_static/media/chapter_9/section_1/image32.png" style="width:0.98425in;height:0.43031in" alt="loading" /></td>
<td style="text-align: left;">Swap the selected action with its previous action</td>
</tr>
<tr>
<td style="text-align: center;"><img src="../_static/media/chapter_9/section_1/image33.png" style="width:0.98425in;height:0.40737in" alt="loading" /></td>
<td style="text-align: left;">Swap the selected action with its next action</td>
</tr>
<tr>
<td style="text-align: center;"><img src="../_static/media/chapter_9/section_1/image34.png" style="width:0.59055in;height:1.01417in" alt="loading" /></td>
<td style="text-align: left;">Click on "<b>Run</b>" button to run the action group in action data list once. (If check "<b>loop</b>" robot arm will cyclically execute the action.)</td>
</tr>
<tr>
<td style="text-align: center;"><img src="../_static/media/chapter_9/section_1/image35.png" style="width:1.1811in;height:0.50609in" alt="loading" /></td>
<td style="text-align: left;"><p>Click it to select and open the action group to load it to action data list.</p>
<p>（The path of the action group file：/home/pi/ArmPi_mini/action_groups)</p></td>
</tr>
<tr>
<td style="text-align: center;"><img src="../_static/media/chapter_9/section_1/image36.png" style="width:1.1811in;height:0.52113in" alt="loading" /></td>
<td style="text-align: left;"><p>Save the action group in action data list to the specific position.</p>
<p>（The path of the action group file：/home/pi/ArmPi_mini/action_groups)</p></td>
</tr>
<tr>
<td style="text-align: center;"><img src="../_static/media/chapter_9/section_1/image37.png" style="width:1.1811in;height:0.51694in" alt="loading" /></td>
<td style="text-align: left;">After opening an action group, click it and open another action group file. Then two action groups are integrated into a new action group.</td>
</tr>
<tr>
<td style="text-align: center;"><img src="../_static/media/chapter_9/section_1/image38.png" style="width:1.37795in;height:0.33203in" alt="loading" /></td>
<td style="text-align: left;">Display the action group saved in PC software</td>
</tr>
<tr>
<td style="text-align: center;"><img src="../_static/media/chapter_9/section_1/image39.png" style="width:0.7874in;height:0.49562in" alt="loading" /></td>
<td style="text-align: left;">Refresh the selection bar of the action group</td>
</tr>
<tr>
<td style="text-align: center;"><img src="../_static/media/chapter_9/section_1/image40.png" style="width:1.1811in;height:0.40443in" alt="loading" /></td>
<td style="text-align: left;">Delete the current action group file</td>
</tr>
<tr>
<td style="text-align: center;"><img src="../_static/media/chapter_9/section_1/image41.png" style="width:1.1811in;height:0.46641in" alt="loading" /></td>
<td style="text-align: left;">（<strong>Caution</strong>)Delete all action group files</td>
</tr>
<tr>
<td style="text-align: center;"><img src="../_static/media/chapter_9/section_1/image42.png" style="width:1.1811in;height:0.38845in" alt="loading" /></td>
<td style="text-align: left;">Run the selected action group once</td>
</tr>
<tr>
<td style="text-align: center;"><img src="../_static/media/chapter_9/section_1/image43.png" style="width:1.1811in;height:0.46673in" alt="loading" /></td>
<td style="text-align: left;">Stop running action group</td>
</tr>
<tr>
<td style="text-align: center;"><img src="../_static/media/chapter_9/section_1/image44.png" style="width:0.7874in;height:0.34629in" alt="loading" /></td>
<td style="text-align: left;">Exit PC software</td>
</tr>
</tbody>
</table>

(6) Deviation Setting Area

| **Icon** | Function |
|:--:|:--:|
| <img src="../_static/media/chapter_9/section_1/image45.png" style="width:1.37795in;height:0.49414in" alt="loading" /> | Click to read the saved deviation automatically |
| <img src="../_static/media/chapter_9/section_1/image46.png" style="width:1.37795in;height:0.48874in" alt="loading" /> | After clicking, the deviation adjusted by PC software can be saved to the robot arm |
| <img src="../_static/media/chapter_9/section_1/image47.png" style="width:1.37795in;height:0.4806in" alt="loading" /> | Click it to restore all servos in servo control area to 1500 |

* **Camera Tool**

The camera tool is used to adjust the threshold of the recognized color, as the figure shown below.

<img src="../_static/media/chapter_9/section_1/image48.png"  />

Please refer to the contentin [4. AI Vision Learning -> 4.2 Color Recognition ->Add Recognition Color](https://docs.hiwonder.com/projects/ArmPi_mini/en/latest/docs/8_ai_vision.html#2_add_new_recognition_color).

## 5.2 Import and Call Action

ArmPi mini has built in action group files before shipping and the path of the files is "**/home/pi/ArmPi_mini/action_groups**". The action group you edit can also be saved in this directory.

<img class="common_img" src="../_static/media/chapter_9/section_2/image1.png"  />

This lesson will tell you how to call action group and how to import it into the system of ArmPi mini.

### 5.2.1 Call Action Group by PC Software

(1) Power on the robot and use VNC Viewer to connect to the remote desktop.

(2) Double click <img src="../_static/media/chapter_9/section_2/image2.png" style="width:50px;" /> and click **"Execute"** in the pop-up window to open PC software.

<img class="common_img" src="../_static/media/chapter_9/section_2/image3.png"  />

(3) Click **"Open action file"** button to select the action group to be executed, and click **"Open"**.

<img class="common_img" src="../_static/media/chapter_9/section_2/image4.png"  />

<img class="common_img" src="../_static/media/chapter_9/section_2/image5.png"  />

(4) The servo values will be displayed in action data list.

<img class="common_img" src="../_static/media/chapter_9/section_2/image6.png"  />

(5) Click **"Run"** to run all the actions in action data list. You can click **"Loop"** to cyclically run this action group. 

<img class="common_img" src="../_static/media/chapter_9/section_2/image7.png"  />

### 5.2.2 Import Action Group 

:::{Note}
* The action group must be named in English or with numbers, and the file format is "**d6a**".

* If want to export action group, you can a insert U disk into one of USB interfaces of Raspberry Pi and paste the action group file to the U disk.

  :::

There are two ways to import the external action group file to ArmPi mini. You can transfer action file to ArmPi mini system with a U disk, or use transfer tool to import action file to system desktop. This lesson will take "**3.6a**" action as example.

* **Use a U Disk**

(1) Connect to ArmPi mini system desktop via VNC tool.

(2) Insert the U disk with action group files into one of USB interfaces of Raspberry Pi.

<img class="common_img" src="../_static/media/chapter_9/section_2/image8.png"  alt="loading" />

(3) When the following pop-up window shows in VNC viewer, click **"OK"**.

<img class="common_img" src="../_static/media/chapter_9/section_2/image10.png" style="width:3.14961in;height:3.22012in" />

(4) Paste the action group file to the system desktop.

<img class="common_img" src="../_static/media/chapter_9/section_2/image11.png" style="width:1.52083in;height:2.4375in" />

(5) Click on <img src="../_static/media/chapter_9/section_2/image12.png" style="width:0.31458in;height:0.275in" /> icon to open file manger.

(6) Enter the directory "/home/pi/ArmPi_mini/action_groups", and import the action file to this directory.

<img class="common_img" src="../_static/media/chapter_9/section_2/image13.png"  />

(7) Double click <img src="../_static/media/chapter_9/section_2/image2.png" style="width:50px;" /> icon and click **"Execute"** to open PC software.

<img class="common_img" src="../_static/media/chapter_9/section_2/image3.png"  />

(8) Click **"Open action group"** button to select the imported action group file, and click **"Open"**.

<img class="common_img" src="../_static/media/chapter_9/section_2/image4.png"  />

<img class="common_img" src="../_static/media/chapter_9/section_2/image14.png"  />

(9) You can view the servo values and running time of the imported action group in servo data list.

<img class="common_img" src="../_static/media/chapter_9/section_2/image15.png"  />

## 5.3 Action Programming

:::{Note}
All action parameters in this lesson is only for reference, please operate according to the actual situation.
:::

This lesson will use PC software to edit an action group. Robot Arm will grip down the block and place it on the right side for example. 

### 5.3.1 Edit Action

(1) Connect to ArmPi mini system desktop via VNC tool.

(2) Double click on <img src="../_static/media/chapter_9/section_3/image2.png" style="width:50px;" /> icon, and click **"Execute"** to open PC software.

<img class="common_img" src="../_static/media/chapter_9/section_3/image3.png"  />

(3) Click **"Open action file"** and select **"start"** action group, and then click **"Open"** to set this action as the first action group.

<img class="common_img" src="../_static/media/chapter_9/section_3/image4.png"  />

<img class="common_img" src="../_static/media/chapter_9/section_3/image5.png"  />

(4) Double click the triangle button in front of No.1 action in action data list to synchronize the action status of ArmPi mini. 

<img class="common_img" src="../_static/media/chapter_9/section_3/image6.png"  />

(5) Set the running time to 800ms and click **"Add action"** to get No.2 action. 

<img class="common_img" src="../_static/media/chapter_9/section_3/image8.png"  />

(6) To make the action group run smoother. After setting an action, we need to add a transition action and change the running time to 200ms. Then click **"Add action"** again to get No.3 action.

<img class="common_img" src="../_static/media/chapter_9/section_3/image9.png"  alt="loading" />

(7) Next, the gripper is controlled to grip the block. We need to drag the slider of No.1 servo.

<img class="common_img" src="../_static/media/chapter_9/section_3/image10.png"  alt="loading" />

(8) Set the running time to 800ms and click **"Add action"** to get No.4 action.

<img class="common_img" src="../_static/media/chapter_9/section_3/image11.png"  alt="loading" />

(9) Add a transition action and set the running time to 100ms. Then click **"Add action"** to get No.5 action. 

<img class="common_img" src="../_static/media/chapter_9/section_3/image12.png"  alt="loading" />

(10) Then drag the slide of No.1 servo to control the gripper to close.

<img class="common_img" src="../_static/media/chapter_9/section_3/image13.png"  alt="loading" />

(11) Set the running time to 200ms and click **"Add action"** to get No.6 action.

<img class="common_img" src="../_static/media/chapter_9/section_3/image14.png"  alt="loading" />

(12) Then drag the slider of ID4 and ID5 servos to control the robot arm to grip and lift up the block.

<img class="common_img" src="../_static/media/chapter_9/section_3/image15.png"  alt="loading" />

(13) Set the running time to 1000ms and click **"Add action"** to get No.7 action.

<img class="common_img" src="../_static/media/chapter_9/section_3/image16.png"  alt="loading" />

(14) Set the running time to 100ms and click **"Add action"** to add a transition action.

<img class="common_img" src="../_static/media/chapter_9/section_3/image17.png"  alt="loading" />

(15) Then drag the slider of ID6 servo to control the robot arm to rotate to the right.

<img class="common_img" src="../_static/media/chapter_9/section_3/image18.png"  alt="loading" />

(16) Set the running time to 800ms and click **"Add action"** to get No.9 action.

<img class="common_img" src="../_static/media/chapter_9/section_3/image19.png"  alt="loading" />

(17) Add a transition action. Set the running time to 300ms and click **"Add action"** to get No.10 action.

<img class="common_img" src="../_static/media/chapter_9/section_3/image20.png"  alt="loading" />

(18) Drag the slider of ID4 and ID5 servos to control the robot arm to put down the block.

<img class="common_img" src="../_static/media/chapter_9/section_3/image21.png"  alt="loading" />

(19) Set the running time to 1000ms and click **"add action"** to get No.11 action.

<img class="common_img" src="../_static/media/chapter_9/section_3/image22.png"  alt="loading" />

(20)  Now, drag the slider of ID1 servo to control the gripper to release the block. 

<img class="common_img" src="../_static/media/chapter_9/section_3/image23.png"  alt="loading" />

(21) Set the running time to 300ms and click **"Add action"** to get No.12 action.

<img class="common_img" src="../_static/media/chapter_9/section_3/image24.png"  alt="loading" />

(22) Drag the slider of ID1 and ID4 servos to control the gripper to close and lift up.

<img class="common_img" src="../_static/media/chapter_9/section_3/image25.png"  alt="loading" />

(23) Set the running time to 400ms and click **"Add action"** to get No.13 action.

<img class="common_img" src="../_static/media/chapter_9/section_3/image26.png"  alt="loading" />

(24) Finally, robot arm is controlled to return to the initial position. Click <img src="../_static/media/chapter_9/section_3/image1.png" /> in front of No.1 action to run it and set the running time to 1000ms. Then click "**Add action**" to get No.14 action.

<img class="common_img" src="../_static/media/chapter_9/section_3/image27.png"  />

### 3.2 Save Action

:::{Note}
 It is recommended to use English or numbers to name action group , and use underscore "**\_**" instead of the space bar to avoid failure saving.
:::

To facilitate later debugging and management, it is recommended to save the action. Click **"Save Action File"**, name the file and click **"Save"**.

<img class="common_img" src="../_static/media/chapter_9/section_3/image28.png"  />

<img class="common_img" src="../_static/media/chapter_9/section_3/image29.png"  />

## 5.4 Integrate Action Files

This lesson will integrate action group **"1.d6a"** and **"3.d6a"** to explain how to integrate action files.

### 5.4.1 Integrate Action Groups

(1) Connect to ArmPi mini system desktop via VNC.

(2) Double click <img src="../_static/media/chapter_9/section_4/image1.png" style="width:50px;" /> icon, and click **"Execute"** to open PC software.

<img class="common_img" src="../_static/media/chapter_9/section_4/image2.png"  />

(3) Click **"Integrate action file"**.

<img class="common_img" src="../_static/media/chapter_9/section_4/image3.png"  />

(4) Select action group **"1.d6a"** and click **"Open"**.

<img class="common_img" src="../_static/media/chapter_9/section_4/image4.png"  />

At this time, the parameters of action group **"1.d6a"** are displayed in action data list.

<img class="common_img" src="../_static/media/chapter_9/section_4/image5.png"  />

(5) Then click **"Integrate action file"** and select **"3.d6a"** action group. Then click **"Open"**.

<img class="common_img" src="../_static/media/chapter_9/section_4/image3.png"  />

<img class="common_img" src="../_static/media/chapter_9/section_4/image6.png"  />

Now, the parameters of action group **"1.d6a"** is followed by that of action group **"3.d6a"**.

<img class="common_img" src="../_static/media/chapter_9/section_4/image7.png"  />

(6) Select the first action in action data list, and click **"run"** to execute the integrated action group once.

<img class="common_img" src="../_static/media/chapter_9/section_4/image8.png"  />

<img class="common_img" src="../_static/media/chapter_9/section_4/image9.png"  />

### 5.4.2 Save Integrated Action Group

Click **"Save action file"** to save the integrated action group for later debugging. The new action group is named as  **"Hiwonder"**.

<img class="common_img" src="../_static/media/chapter_9/section_4/image10.png"  />

<img class="common_img" src="../_static/media/chapter_9/section_4/image11.png"  />

:::{Note}
 It is recommended to use English or numbers to name action group , and use underscore "**\_**" instead of the space bar to avoid failure saving.
:::
