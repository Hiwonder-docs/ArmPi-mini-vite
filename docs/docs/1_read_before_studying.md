# 1. Getting Ready

## 1.1 ArmPi mini Introduction

**1.1.1 Product Introduction**

Powered by Raspberry Pi 5, ArmPi mini is an open source robotic arm for  beginners. It takes OpenCV as the image processing library and is loaded with 130° HD camera with the first person view.
With built-in inverse kinematics algorithm, ArmPi mini can use Python to perform different AI vision functions like color recognition, color sorting, target tracking and intelligent stacking.
Not only can it fit the users' needs for learning and testing machine vision, robotic arm motion control and inverse kinematics, but also provide easy-to-learn integration solution for secondary development. Abundance of tutorial material and source code are available for you to start ArmPi mini immediately!

<img class="common_img" src="../_static/media/chapter_1/section_1/image1.png" alt="loading" />

**1.1.2 Usage Precautions**

Please pay attention to the following points when using and storing this product:

This product contains conductive components. Avoid contact with metal objects when powered on.

After the robot is powered on, do not forcibly move the servo, as this may cause damage.

If the robot runs for an extended period, the servos may become hot. Allow the robot to "rest" and wait for the servos to cool before resuming operation.

Keep your face, glasses, and other body parts away from the robot while it is operating. Do not place fingers within the joint movement range to prevent injury. Also, be cautious of falls from high edges.

The robot's servos are precision components and consumable parts. They may need replacement after long-term or intensive use.

If the product will not be used for an extended period, fully charge the battery, remove it, and store it in a cool, dry place.

**1.1.3 Copyright Notice**

This manual is the property of Shenzhen Hiwonder Technology Co., Ltd. No organization or individual is permitted to reproduce, copy, translate, or distribute any content from this manual without authorization.

Any unauthorized use or infringement of this manual's copyright will be subject to legal action by our company.

**1.1.4 Disclaimer**

The product described in this manual (including hardware, software, etc.) is provided "**as is**". Every effort has been made to ensure the accuracy of this manual, but we cannot guarantee it is completely free from errors or omissions. This document is regularly reviewed, and we welcome feedback for improvements.

Product features and specifications may change with version upgrades. For the latest product information, please contact customer service when placing your order.

Furthermore, unless explicitly stated by Hiwonder, we are not responsible for any losses resulting from product malfunctions or damage under extreme conditions outside of typical use cases.

## 1.2  Packing List

<table class="docutils-nobg" border="1" style="text-align: center">
  <tr>
    <th>No.</th>
    <th>Components</th>
    <th>Quantity</th>
    <th>Picture</th>
  </tr>
  <tr>
    <td>1</td>
    <td>Robotic arm (assembled)</td>
    <td>1</td>
    <td><img  src="../_static/media/chapter_1/section_1/image1.0.png" alt="loading" style="width:150px;" /></td>
  </tr>
  <tr>
    <td>2</td>
    <td>Base bracket set<br>(Base plate*1<br>Base top cover * 1<br>Base side cover *4)</td>
    <td>1</td>
    <td><img  src="../_static/media/chapter_1/section_1/image2.png" alt="loading" style="width:300px;" /></td>
  </tr>
  <tr>
    <td>3</td>
    <td>Raspberry Pi 5</td>
    <td>1</td>
    <td><img  src="../_static/media/chapter_1/section_1/image3.png" alt="loading" style="width:200px;" /></td>
  </tr>
      <tr>
    <td>4</td>
    <td>Raspberry Pi 5 expansion board</td>
    <td>1</td>
    <td><img  src="../_static/media/chapter_1/section_1/image4.png" alt="loading" style="width:150px;" /></td>
  </tr>
  <tr>
    <td>5</td>
    <td>Active heatsink Thermal silicone pads</td>
    <td>1</td>
    <td><img  src="../_static/media/chapter_1/section_1/image5.png" alt="loading" style="width:180px;" /></td>
  </tr>
  <tr>
    <td>6</td>
    <td>Card reader</td>
    <td>1</td>
    <td><img  src="../_static/media/chapter_1/section_1/image6.png" alt="loading" style="width:40px;" /></td>
  </tr>
  <tr>
    <td>7</td>
    <td>32GB SD card</td>
    <td>1</td>
    <td><img  src="../_static/media/chapter_1/section_1/image7.png" alt="loading" style="width:35px;" /></td>
  </tr>
  <tr>
    <td>8</td>
    <td>Lithium battery</td>
    <td>2</td>
    <td><img  src="../_static/media/chapter_1/section_1/image8.png" alt="loading" style="width:120px;" /></td>
  </tr>
  <tr>
    <td>9</td>
    <td>Battery holder box</td>
    <td>1</td>
    <td><img  src="../_static/media/chapter_1/section_1/image9.png" alt="loading" style="width:200px;" /></td>
  </tr>
  <tr>
    <td>10</td>
    <td>Battery charger</td>
    <td>1</td>
    <td><img  src="../_static/media/chapter_1/section_1/image10.png" alt="loading" style="width:180px;" /></td>
  </tr>
  <tr>
    <td>11</td>
    <td>USB cable</td>
    <td>1</td>
    <td><img  src="../_static/media/chapter_1/section_1/image11.png" alt="loading" style="width:150px;"/></td>
  </tr>
  <tr>
    <td>12</td>
    <td>Suction cups</td>
    <td>4</td>
    <td><img  src="../_static/media/chapter_1/section_1/image12.png" alt="loading" style="width:120px;" /></td>
  </tr>
  <tr>
    <td>13</td>
    <td>Paper Map</td>
    <td>1</td>
    <td><img  src="../_static/media/chapter_1/section_1/image13.png" alt="loading" style="width:300px;" /></td>
  </tr>
  <tr>
    <td>14</td>
    <td>3*3cm Blocks</td>
    <td>1</td>
    <td><img  src="../_static/media/chapter_1/section_1/image14.png" alt="loading" style="width:150px;" /></td>
  </tr>
  <tr>
    <td>15</td>
    <td>Screwdriver</td>
    <td>1</td>
    <td><img  src="../_static/media/chapter_1/section_1/image15.png" alt="loading" style="width:180px;" /></td>
  </tr>
  <tr>
    <td>16</td>
    <td>Accessory bag<br>
      (M3*4 flat head screw * 4<br>
      M4*8 round head screw * 6<br>
      M2.5*6 round head screw * 6<br>
      M3*6 round head screw * 20<br>
      M4 nut * 6<br>
      M2.5*5+6 Single-pass nylon column * 5<br>
      M2.5*6 Double-pass Copper Column * 10)</td>
    <td>1</td>
    <td><img  src="../_static/media/chapter_1/section_1/image16.png" alt="loading" style="width:300px;" /></td>
  </tr>
</table>




## 1.3 Introduction to Raspberry Pi 5

Raspberry Pi, known as "**树莓派**" in Chinese, abbreviated as RPi or RasPi/RPI. It is a credit-card sized computer developed by the Raspberry Pi Foundation in the UK. It is hoped that it can help children worldwide to learn programming and understand how computers work. The Raspberry Pi can connect to a keyboard, mouse, and Internet cable. It also features a TV output interface for analog video signals and an HDMI high-definition video output interface. It is a capable little device that enables people of all ages to explore computing and to learn how to program in languages like Python. And it is capable of doing everything you'd expect a desktop computer to do, from browsing the internet and playing high-definition video, to making spreadsheets, word-processing, and playing games.

<img class="common_img" src="../_static/media/chapter_1/6.1/image2.png"  />

<p style="text-align:center">Raspberry Pi icon</p>

**1.3.1 Brief Introduction of Raspberry Pi 5**

Raspberry Pi 5 features a 64-bit quad-core Cortex A76 processor with 2.4 GHz operating frequency. Compared to the Raspberry Pi 4, the CPU performance has increased by 2 to 3 times. Apart from the significant improvement in graphics performance with the 800MHz VideoCore VII GPU, it also supports dual 4Kp60 display output via HDMI, and advanced camera through restructuring Raspberry Pi Image Signal Processor. It provides consumers with a smooth desktop experience and opens up new applications for industrial customers.

This is the first full-sized Raspberry Pi computer, utilizing chips built internally by Raspberry Pi. RP1 provides the majority of the I/O functions for Raspberry Pi 5 and achieves a significant leap in peripheral performance and functionality. The total USB bandwidth has more than doubled, thus speeding up the transfer rate to external UAS drives and other high-speed peripherals. The dedicated dual-channel 1Gbps MIPI camera and display interface on earlier models have been replaced by a pair of quad-channel 1.5Gbps MIPI transceivers, tripling the total bandwidth and supporting a maximum of two cameras or displays in any combination. By supporting SDR104 high-speed mode, the peak performance of the SD card is doubled. This platform introduces a single-channel PCI Express 2.0 interface for the first time, providing support for high-bandwidth peripherals.

**1.3.2 Hardware Structure and Feature**

* **Hardware structure of Raspberry Pi 5 is as pictured**

<img class="common_img" src="../_static/media/chapter_1/6.1/image3.png"  alt="IMG_256" />

* **Main features**

(1) Four Arm Cortex-A76 cores @ 2.4GHz, with hardware AES encryption support, 512KB L2 cache per core, and a 2MB L3 cache;

(2) 4GB or 8GB LPDDR4X-4267 SDRAM;

(3) Dual 4Kp60 HDMI display output, supporting HDR, and a 4Kp60 HEVC decoder;

(4) VideoCore VII Graphics, support OpenGL-ES 3.1、Vulkan 1.2;

(5) Raspberry Pi Image sensor processor;

(6) Raspberry Pi connector for PCIe (one 2.0 port, additional HAT is needed);

(7) 802.11ac Dual-band Wi-Fi and Bluetooth 5.0 (support BLE);

(8) Gigabit Ethernet;

(9) Two USB2.0, two USB 3.0 (capable of achieving full throughput simultaneously);

(10) Poe support (additional HAT is needed);

(11) Two-lane 4-lane MIPI CSI/DSI connector, support 2x display; or 2x camera; or one display + one camera;

(12) Raspberry Pi 40 pin GPIO connector;

(13) fan port;

(14) Real-time clock;

(15) Power supply key;

* **Advantages**

(1) Powerful computational performance;

(2) Open-source hardware and ease of use;

(3) Compared to Microsoft systems, tools are free;

(4) A low-cost development platform and troubleshooting tool;

(5) All applications can be opened without internet access;

(6) Compact size, equivalent to the size of a credit card;

It is precisely because of these advantages that people around the world choose Raspberry Pi more often to learn programming skills, build hardware projects, undertake home automation projects, and even use them in industrial applications.

**1.3.3 Dimension Diagram (unit: mm)**

<img class="common_img" src="../_static/media/chapter_1/6.1/image5.png"  alt="" />

**1.3.4 The Use of Raspberry Pi**

**(1）Web server**

The Raspberry Pi can stay around the clock because it only requires very little power. No need for cooling fans or large amounts of electricity; accessing web pages through the internet or solely within a local network is also sufficiently fast.

**(2）Laptop**

The Raspberry Pi can be used as the "**brain**" of a laptop, just need to equip it with a computer screen.

**(3）Home theater set-top box**

There are many free operating systems that can turn the Raspberry Pi into a set-top box that can run your favorite content.

**(4）Game simulator**

Use the free RetroPie OS on any Raspberry Pi to play Game Boy, arcade, SNES and other games.

**(5）Monitor**

With simple steps and an external camera, a simple monitoring system can be built.

**(6）Wi-Fi extender**

If you cannot get a good Wi-Fi signal in some rooms of your home, your Raspberry Pi can help by turning into an extender. On the Raspberry Pi's built-in Wi-Fi, only a USB Wi-Fi adapter is required to repeat the signal.

**(7）Music streamer and multi-room audio**

Using the right software and some Raspberry Pi, you can create an inexpensive sound system to play music in different locations in your home.

As mentioned above, Raspberry Pi is not only a small developer, but also a "**caring companion**" in life.

## 1.4 Burn Raspberry Pi Image

Raspberry Pi can work after operating system is installed to SD card. System image and tools can be found in the same folder.

**1.4.1 Preparation**

* **Hardware:**

Prepare a card reader, SD card (over 16GB) and a computer (WIN10).

* **Software:**

Install SD card formatting tool, SD Card Formatter and image burning tool, Win32DiskImager. This section uses these two tools as examples for illustration.

**1.4.2 Format SD Card** 

:::{Note}

If SD card is empty, you can skip this step.

:::

(1) Insert SD card to card reader, and then connect it to your computer.

(2) Open SD Card Formatter. Select corresponding card, and then click "**Format**".

<img class="common_img" src="../_static/media/chapter_1/7.1/image2.png"  />

(3) If window below appears, click **"Yes"**. It takes time to format. Please be patient!

<img class="common_img" src="../_static/media/chapter_1/7.1/image3.png"  />

**1.4.3 Burn Image**

(1) Open Win32DiskImager. Click on <img src="../_static/media/chapter_1/7.1/image4.png"  /> to select system image. (TurboPi image can be found in the same folder. Download and extract the image before operation. The following pictures are just for reference, please subject to the actual TurboPi's system image.) In "**Device**" bar, select boot of SD card. Next, click "**Write**".

<img class="common_img" src="../_static/media/chapter_1/7.1/image5.png"  />

:::{Note}

the storage path for image file cannot contain Chinese.

:::

(2) Click "**Yes**" when the following window pops up.

<img class="common_img" src="../_static/media/chapter_1/7.1/image6.png"  />

(3) Once **"Write Successful"** prompt shows up, the image is written successfully. If error is reported, please close firewall, and then reinsert SD card to operate again.

<img class="common_img" src="../_static/media/chapter_1/7.1/image7.png"  />



:::{Note}

If you are asked to whether to format partition after writing image, just ignore it.

:::

<p id="anchor_1_5"></p>

## 1.5 Assembly

<p class="step">Step 1：Install suction cup</p>

<img class="common_img" src="../_static/media/chapter_1/section_2/image1.png"  alt="loading" />

<p class="step">Step 2：Install battery box</p>

<img class="common_img" src="../_static/media/chapter_1/section_2/image2.png"  alt="loading" />

<p class="step">Step 3：Install Raspberry Pi boad and expansion board</p>

<img class="common_img" src="../_static/media/chapter_1/section_2/image3.png"  alt="loading" />

<img class="common_img" src="../_static/media/chapter_1/section_2/image4.png"  alt="loading" />

<img class="common_img" src="../_static/media/chapter_1/section_2/image5.png"  alt="loading" />

<img class="common_img" src="../_static/media/chapter_1/section_2/image6.png"  alt="loading" />

<img class="common_img" src="../_static/media/chapter_1/section_2/image7.png"  alt="loading" />

<p class="step">Step 4：Install base bracket</p>

<img class="common_img" src="../_static/media/chapter_1/section_2/image8.png"  alt="loading" />

<p class="step">Step 5：Install robotic arm and wiring</p>

<img class="common_img" src="../_static/media/chapter_1/section_2/image9.png"  alt="loading" />

<img class="common_img" src="../_static/media/chapter_1/section_2/image11.png"  alt="loading" />

<img class="common_img" src="../_static/media/chapter_1/section_2/image12.png"  alt="loading" />

<img class="common_img" src="../_static/media/chapter_1/section_2/image13.png"  alt="loading" />

<p id="anchor_1_6"></p>

##  1.6 Charging and Power-On Status Explanation

Before starting this lesson, ArmPi mini needs to be assembled according to [1.5 Assembly](#anchor_1_5).

**1.6.1 Charging Battery**

Please fully charge robot arm at the first use and operate according to the following method.

(1) Take out battery charger and put two 18650 batteries into battery charger. Please pay attention to the positive and negative direction of the batteries.

Then connect the battery charger and charging plug (5V 3A prepare your own one) over a USB cable, and plug it into socket.

<img class="common_img" src="../_static/media/chapter_1/section_3/image1.png"  alt="loading" />

(2) Wait for the charging to complete (The indicator light of charger is green    before charging and turns red when charging. It need to take about 6h to fully charge. When the batteries is fully charged, the indicator will turn green from
red). After the charging is complete, please unplug the charger as soon as possible.

**1.6.2  Install Battery**

(1) Push the switch of battery holder box from **"ON"** to **"OFF"** .

<img class="common_img" src="../_static/media/chapter_1/section_3/image2.png"  alt="loading" />

(2) Install the fully charged batteries into the battery box and attach the cover. Note: Do not make mistake when the batteries are installed!

**1.6.3 Camera Connection**

Before turning on robot, please make sure that the camera cable is firmly connected (The camera cable can be connected to any one of USB interfaces of Raspberry Pi).

<img class="common_img" src="../_static/media/chapter_1/section_3/image3.png"  alt="loading" />

**1.6.4 Turn On ArmPi mini**

(1) Push the switch of battery box to **"ON"** side to turn on Raspberry Pi.

<img class="common_img" src="../_static/media/chapter_1/section_3/image4.png"  alt="loading" />

(2) At this time, the LED1 and LED2 of the Raspberry Pi will be on firstly and then the LED2 will flash every 2 seconds. ArmPi mini will return to the

initial posture and buzzer will make **"Di"** sound, which means the robot is turned on successfully.

:::{Note}

The Raspberry Pi is a small minicomputer. It usually takes about 1 minute to boot up after it is Powered ON, which is normal.

:::

(3) After turning on, Raspberry Pi will be in an AP direct connection mode by default and launch a Wi-Fi hotspot starting with **"HW"** .

<img class="common_img" src="../_static/media/chapter_1/section_3/image5.jpeg"  alt="loading" style="width:50%" />

(4) After turning on ArmPi mini successfully, please refer to "[**1.9.3 Position Calibration**](#anchor_1_9_3)" to calibrate gripping position (Do not skip this step!)

**1.6.5 Start Self-check Service**

After successfully powering on the robot, you can press the KEY1 button on the expansion board to start the self-check service to check its servos. This helps you to ensure the correct wiring.

<img class="common_img" src="../_static/media/chapter_1/section_3/image6.png"  alt="loading" />

If the servos fail to run as described below after starting the self-check service, please refer to "[**1.5 Assembly**](#anchor_1_5)" to rewire them.

The servos should rotate in the following sequence: 1->3->4->5->6.

<img class="common_img" src="../_static/media/chapter_1/section_3/image7.png" />

**1.6.6 Check Battery Level**

(1) If the LED1 and LED2 on expansion board emit a bright blue light, which means the battery level is enough and robot can be use normally , as the figure shown below:

<img class="common_img" src="../_static/media/chapter_1/section_3/image8.png"  alt="loading"  style="width:70%" />

(2) If the  LED  lights on expansion  board emit faint blue light, it means the battery level is is almost dead, you need to charge the battery as soon as possible, as the figure shown below:

<img class="common_img" src="../_static/media/chapter_1/section_3/image9.png"  alt="loading" style="width:70%" />

<p id="anchor_1_7"></p>

## 1.7 Remote Desktop Installation and Connection

**1.7.1 Preparation**

* **Hardware**

Prepare a computer. If you are using desktop computer, wireless network card is required.The network card should support 5G band.

* **Install VNC**

VNC is a graphical remote desktop control software. Through connecting your computer to the WiFi generated by Raspberry Pi, you can control Raspberry Pi. Installation of VNC is as below.

(1) Double-click the installation program **"VNC-Viewer-6.17.731-Windows"** in the same directory as this section. Select the installation language as **"English"** and lick **"OK"**.

<img src="../_static/media/chapter_1/section_4/image1.png" class="common_img" />

(2) Click "**Next**".

<img src="../_static/media/chapter_1/section_4/image2.png" class="common_img" />

(3) Tick **"I accept the terms in the License Agreement"**. Then click **"Next"**.

<img src="../_static/media/chapter_1/section_4/image3.png" class="common_img" />

(4) Remain default location where the software is installed. Click **"Next"** to proceed next interface. Then directly click **"Install"**.

<img src="../_static/media/chapter_1/section_4/image4.png" class="common_img" />

(5) When the installation completes, click **"Finish"**.

<img src="../_static/media/chapter_1/section_4/image5.png" class="common_img" />

(6) Click <img src="../_static/media/chapter_1/section_4/image6.png" style="width:45px;" /> to open VNC.

* **Start Robot**

Start Robot When LED1 on expansion board starts flickering and buzzer emits one beep, robot boots up successfully.

**1.7.2 Connect to Robot**

(1) After turning Robot on successfully, the default mode is AP direct connection mode. Robot generates a WiFi starting with HW. Connect your computer to this WiFi.

<img src="../_static/media/chapter_1/section_4/image7.png" class="common_img"  />

(2) Input password. The password is **"hiwonder"**.

<img src="../_static/media/chapter_1/section_4/image8.png" class="common_img"  />

<img src="../_static/media/chapter_1/section_4/image9.png" class="common_img"  />

(3) After connection, open VNC Viewer. Input the default IP address of Raspberry Pi, **192.168.149.1**, and then press Enter. If you receive security warning, select **"Continue"**.

<img class="common_img" src="../_static/media/chapter_1/section_4/image10.png"  />

(4) Input username and password. **(Username: pi  Password: raspberrypi)**. Click **"OK"** to enter Raspberry Pi desktop.

<img src="../_static/media/chapter_1/section_4/image11.png" class="common_img" />

(5) The desktop is as pictured. If black screen occurs or only cursor leaves on the screen, restart Raspberry Pi.

<img class="common_img" src="../_static/media/chapter_1/section_4/image12.png"  />

**1.7.3 Introduction to Desktop**

The desktop is as pictured after connecting Robot through VNC successfully.

<img class="common_img" src="../_static/media/chapter_1/section_4/image13.png"  />

The following table demonstrates common functions:

<table  class="docutils-nobg" style="margin:0 auto" border="1">
<colgroup>
<col  />
<col  />
</colgroup>
<tbody>
<tr>
<td >Icon</td>
<td >Function</td>
</tr>
<tr>
<td ><img src="../_static/media/chapter_1/section_4/image14.png"   /></td>
<td ><p>Application menu. Click to select different applications.</p>
<p><img src="../_static/media/chapter_1/section_4/image15.png"  /></p></td>
</tr>
<tr>
<td ><img src="../_static/media/chapter_1/section_4/image16.png"   /></td>
<td >Browser.</td>
</tr>
<tr>
<td ><img src="../_static/media/chapter_1/section_4/image17.png"   /></td>
<td >File manager.</td>
</tr>
<tr>
<td ><img src="../_static/media/chapter_1/section_4/image18.png"   /></td>
<td >LX terminal. Click to input command line in the opened interface.</td>
</tr>
<tr>
<td ><img src="../_static/media/chapter_1/section_4/image19.png"   /></td>
<td >Trash. You can find the files deleted here.</td>
</tr>
<tr>
<td ><img src="../_static/media/chapter_1/section_4/image20.png"   /></td>
<td >PC software. You can adjust pan tilt and adjust color threshold on it.</td>
</tr>
<tr>
<td ><img src="../_static/media/chapter_1/section_4/image21.png"   /></td>
<td >Full screen or exit full screen.。</td>
</tr>
<tr>
<td ><img src="../_static/media/chapter_1/section_4/image22.png"   /></td>
<td >Exit full screen.</td>
</tr>
<tr>
<td ><img src="../_static/media/chapter_1/section_4/image23.png"   /></td>
<td ><p>Shut down, reboot and logout</p>
<p><img src="../_static/media/chapter_1/section_4/image24.png"  /></p></td>
</tr>
</tbody>
</table>

<p id="anchor_1_8"></p>

## 1.8 Deviation Adjustment

If the deviation of the servo main shaft is caused by the fall of the robot arm during assembly, or the replacement servo, and other operations, the generated deviation must be adjusted. Deviation is divided into two cases: small deviation and large deviation. Depending on the situation, the debugging method is also different.

**1.8.1 Preparation**

(1) Turn on ArmPi mini according to the tutorial in "[**1.6 Charging and Power-On Status Explanation**](#anchor_1_6)".

(2) Connect the robot via VNC remote tool according to "[**1.7 Remote Desktop Installation and Connection**](#anchor_1_7)".

**1.8.2 Deviation Judgment**

(1) Aftering connecting ArmPi mini, open PC software. 

(2) Then click **"Reset servo"** in the software interface, and then the robot arm will stand up straight.

<img class="common_img" src="../_static/media/chapter_1/section_5/image2.png"  alt="loading" />

(3) Then click **"Read deviation"** to synchronize the deviation to the left servo control area.

<img class="common_img" src="../_static/media/chapter_1/section_5/image3.png"  alt="loading" />

(4) After resetting robotic arm, the main shaft screws of servo ID3-ID5 are in a straight line (it is named as **"centerline"** in the following steps), as the figure shown below:

<img class="common_img" src="../_static/media/chapter_1/section_5/image4.jpeg"  alt="loading" />

(5) The the groove line of the U shape bracket of ID6 servo are parallel with the edge of the upper cover of the base, as the left figure shown below, and the gripper is closed, as the right figure show below. Under this situation, the robotic arm is ready to use, you can skip this lesson.

<img class="common_img" src="../_static/media/chapter_1/section_5/image5.jpeg"  alt="loading" />

<img class="common_img" src="../_static/media/chapter_1/section_5/image6.jpeg"  alt="loading" />

(6) If the angle between centerline and servo is less than 13 degrees, it is classified as small deviation and can be adjusted by PC software. You can follow the operation instruction in "[**1.8.3 Small Deviation Adjustment**](#anchor_1_8_3)" to adjust the small deviation. Here i will take ID3 servo as example, as the figure shown below. 

<img class="common_img" src="../_static/media/chapter_1/section_5/image7.jpeg"  alt="loading" />

(7) If the angle between center line and servo is larger than 13 degree, it is classified as large deviation and can not be adjusted by PC software which the extreme adjustment value is between -150 and +150. Under this situation, you can follow the operation instruction in "[**1.8.4 Large Deviation Adjustment**](#anchor_1_8_4)" to adjust large deviation.

<img class="common_img" src="../_static/media/chapter_1/section_5/image8.jpeg"  alt="loading" />

<p id="anchor_1_8_3"></p>

**1.8.3 Small Deviation Adjustment**

(1) Small deviation can be adjusted by dragging the deviation adjustment slider of PC software. Note: the short slider bar below is for adjusting deviation.

<img class="common_img" src="../_static/media/chapter_1/section_5/image9.png"  alt="loading" />

(2) Drag the slider of ID3 servo to make robot arm stretch straight. (the values in following figure is just for reference, you need to adjust your own robot according to the actual situation.)

<img class="common_img" src="../_static/media/chapter_1/section_5/image10.png"  alt="loading" />

(3) Then click **"Save deviation"** to save the deviation value into the robot arm.

<img class="common_img" src="../_static/media/chapter_1/section_5/image11.png"  alt="loading" />

<p id="anchor_1_8_4"></p>

**1.8.4 Large Deviation Adjustment**

(1) When adjusting the large deviation, U shape bracket must be removed from servo and reset the servo to initial position. Then repeat the operation steps of small deviation adjustment. Again. 

(2) Click **"Reset servo"** in PC software to make robot arm stretch straight.

<img class="common_img" src="../_static/media/chapter_1/section_5/image2.png"  alt="loading" />

(3) At this time, you can find ID3 servo with obvious deviation and the deviation angle is larger than 13 degrees.

<img class="common_img" src="../_static/media/chapter_1/section_5/image8.jpeg"  alt="loading" />

(4) Unplug the robot arm. Servo will be removed in the following steps, so do not operate when power is supplied. 

(5) Unscrew the main servo horn of ID3 servo.

<img class="common_img" src="../_static/media/chapter_1/section_5/image12.jpeg"  alt="loading" />

(6) Next, remove the rivet holding U shape bracket.

<img class="common_img" src="../_static/media/chapter_1/section_5/image13.jpeg"  alt="loading" />

(7) Then pull out the main shaft from the metal servo horn. 

<img class="common_img" src="../_static/media/chapter_1/section_5/image14.jpeg"  alt="loading" />

(8) In addition to ID3 servo, remove all the servo cables from Raspberry Pi expansion board (Do not skip this step), and then turn on Raspberry Pi.

<img class="common_img" src="../_static/media/chapter_1/section_5/image15.jpeg"  alt="loading" />

(9) After turning on robot arm, connect it via VNC and open PC software. Then click **"Reset servo"**. At this time, servo ID3 has been reset to initial position.

<img class="common_img" src="../_static/media/chapter_1/section_5/image2.png"  alt="loading" />

(10) Turn off robot arm. Then assemble the servo horn back to servo in cross shape. 

:::{Note}

The servo has been at initial position, do not forcefully rotate the main servo. If the servo horn is not assembled in cross shape, you need to repeat the operations steps 6-8 to adjust deviation again. 

:::

<img class="common_img" src="../_static/media/chapter_1/section_5/image16.jpeg"  alt="loading" />

(11) Then fix the metal servo horn with screws.

<img class="common_img" src="../_static/media/chapter_1/section_5/image17.jpeg"  alt="loading" />

(12) Assemble the rivet to the side of bracket.

<img class="common_img" src="../_static/media/chapter_1/section_5/image18.jpeg"  alt="loading" />

(13) Connect the servo cables back to the Raspberry Pi expansion board.

:::{Note}

the servo ID tag corresponds to the interface number of expansion board. The yellow cable should be connected to **"S"** signal terminal, red cable to **"+"**, brown cable to **"-"**, white cable to **"S"**, red cable to **"+"**, black cable to **"-"**. Do not wrongly connect the cables, otherwise the servo will be burned out.

:::

<img class="common_img" src="../_static/media/chapter_1/section_5/image19.jpeg" style="width:600px;"  alt="loading" />

(14) Then, repeat the operation steps of "[**1.8.3 Small Deviation Adjustment**](#anchor_1_8_3)" to adjust the small deviation. 

<p id="anchor_6"></p>

## 1.9 MAP Placement

<p id="anchor_6_1"></p>

**1.9.1 Map Layout Instruction**

* **Map Layout Instruction**

From the image below, we can know that map consists of four areas, which are robot placement area, picking area, sorting area and stacking area.

<img class="common_img" src="../_static/media/chapter_1/section_6/image2.png"  alt="loading" />

Place ArmPi mini in the placement area, and place colored blocks in the picking area.
After the color sorting is started, robot arm will pick the blocks in robot placement area, and place them in color sorting area. (About color sorting, please go to folder "[**Quick User Experience ->2.2 App Control**](https://docs.hiwonder.com/projects/ArmPi_mini/en/latest/docs/2_play_first_hand.html#app-control)" and "[**AI Vision Learning -> 4.5 Color Sorting**](https://docs.hiwonder.com/projects/ArmPi_mini/en/latest/docs/8_ai_vision.html#color-sorting)")
After the intelligent stacking is started, robot arm will pick the colored blocks in picking area and place them in stacking area. (About intelligent stacking, please go to folder "[**Quick User Experience ->2.2 APP Control**](https://docs.hiwonder.com/projects/ArmPi_mini/en/latest/docs/2_play_first_hand.html#app-control)" and "[**AI Vision Learning->4.6 Intelligent Stacking**](https://docs.hiwonder.com/projects/ArmPi_mini/en/latest/docs/8_ai_vision.html#intelligent-stacking)")

**1.9.2 Map Placement**

(1) Put map in a flat and smooth surface and glue four corners of the map to avoid map movement when starting game.

<img class="common_img" src="../_static/media/chapter_1/section_6/image3.jpeg"  alt="loading" />

(2) Place the robotic arm in the placement area, and the base board must overlap the three blacks line on map ,as the figure shown below.

<img class="common_img" src="../_static/media/chapter_1/section_6/image4.jpeg"  alt="loading" />

<img class="common_img" src="../_static/media/chapter_1/section_6/image5.jpeg"  alt="loading" />

(3) After placement, gently press on the suction cups better adhere to the desktop.

:::{Note}
When starting color sorting and intelligent stacking, do not have similar color object within the frame to avoid interference.
:::

<p id="anchor_1_9_3"></p>

**1.9.3 Position Calibration**

Before starting game, the picking position of gripper must be calibrated, otherwise the robot may fail to pick object and affect the normal use.

* **Preparation**

(1) Turn on ArmPi mini according to the tutorial "[**1.6 Charging and Power-On Status Explanation**](#anchor_1_6)".

(2) Connect robot via VNC remote tool according to the tutorial "[**1.7 Remote Desktop Installation and Connection**](#anchor_1_7)".

(3) Adjust deviation according to the tutorial "[**1.8 Deviation Adjustment**](#anchor_1_8)".

(4) Place the robot on map according to the tutorial "[**1.9.3 Position Calibration**](#anchor_1_9_3)".

* **Whether the picking position needs to be calibrated?** 

(1) Double click  <img style="width:50px" src="../_static/media/chapter_1/section_6/image16.png"  /> to open PC software.

(2) Click **"Execute"** to enter the editing interface of PC software.

<img class="common_img" src="../_static/media/chapter_1/section_6/image17.png"  />

(3) Then click **"Read"** in the upper left corner and click **"OK"** to read the initial position information of the gripper.

<img class="common_img" src="../_static/media/chapter_1/section_6/image18.png"  alt="loading" />

(4) Click **"Run to Coordinate"** to control the robot arm to move to the top of the picking area and observe its position. If the gripper is right at the 1cm above the center of the cross mark in picking area, the position does not need to calibrate, as the figure shown below. If it does not meet the requirements, you need to continue the following steps for calibration.

<img class="common_img" src="../_static/media/chapter_1/section_6/image19.jpeg"  alt="loading" />

(5) If the following deviation situation occurs, as the figure shown below, you need to calibrate the picking position. Thus the following operation steps will calibrate this deviation.

<img class="common_img" src="../_static/media/chapter_1/section_6/image20.jpeg"  alt="loading" />

* **Calibration Principle**

Take the robot arm as the first person view and take the centre point of the base as the coordinate original point, as the figure shown below.

<img class="common_img" src="../_static/media/chapter_1/section_6/image6.png"  alt="loading" />

The default initial value of the gripping position is X=1.00cm, Y=14.00cm and Z=0.00cm. The pitch angle is 90 degrees and the running time is 1500ms.
The coordinate value of gripper can be set in the position calibration interface of PC software, as the figure shown below.

<img class="common_img" src="../_static/media/chapter_1/section_6/image7.png"  alt="loading" />

| Parameter | Function |
|:--:|:--:|
| X | Adjust x-axis value to control the gripper to move left or right. |
| Y | Adjust y-axis value to control the gripper to move forwards and backwards. |
| Z | Adjust z-axis value to control the gripper move up and down. (The z-axis value has been set as 1cm which is a right position for the gripper to stop the middle position between two blocks. It is not commended to modify this value.) |
| Pitch angle | The angle between gripper and x axis, i.e., the angles when the gripper looks upward and downward. This parameter does not need to be modified. |
| Running time | The movement time used by the gripper to move from the previous position to the set coordinate value. (just for checking the running effect ) |
| Read | Read the current position information of gripper. |
| Save | Save the coordinate value of the adjusted gripping position. |
| Run to Coordinate | Click it to move robot arm to the set coordinate value |

* **Calibration Steps**

Observing the following example, you can find that the picking position of gripper is offset upward relative to the cross mark in the picking area of the map, and then we need to adjust it to 1cm directly above the cross mark.

(1) Click **"Read"** button in the lower left corner, and click **"OK"** to read the position information of picking posture.

<img class="common_img" src="../_static/media/chapter_1/section_6/image8.png"  alt="loading" />

(2) Click **"Run to Coordinate"** to control the gripper to move to the picking area, and observe the offset between the cross mark and the gripper.

<img class="common_img" src="../_static/media/chapter_1/section_6/image9.png"  alt="loading" />

(3) You can find that the gripper is offset to the right (take robot as the first person view), and the offset distance is close to 0.5cm.

<img class="common_img" src="../_static/media/chapter_1/section_6/image5.jpeg"  alt="loading" />

(4) Therefore, subtract 0.5cm from the x-axis value, that is, the X value is set to **"0.5"**. Then click **"Run to Coordinate"** to see the effect after adjustment.

<img class="common_img" src="../_static/media/chapter_1/section_6/image10.png"  alt="loading" />

<img class="common_img" src="../_static/media/chapter_1/section_6/image11.jpeg"  alt="loading" />

(5) Now, the gripper is very close to the center of the cross mark.

(6) Now let's look at the y-axis. The gripper is offset forward a little bit. In this case, y-axis value needs to be adjusted.

<img class="common_img" src="../_static/media/chapter_1/section_6/image12.jpeg"  alt="loading" />

(7) subtract 0.5cm from they-axis value, that is, the y-axis value is set to **"13.5"**. Then click **"Run to Coordinate"** to see the effect after adjustment.

<img class="common_img" src="../_static/media/chapter_1/section_6/image13.png"  alt="loading" />

<img class="common_img" src="../_static/media/chapter_1/section_6/image14.jpeg"  alt="loading" />

(8) Now, the gripper is offset to the right a little bit. Therefore, observe and adjust the x-axis value until the centre of the gripper directly above the centre of the cross mark.

<img class="common_img" src="../_static/media/chapter_1/section_6/image4.jpeg"  alt="loading" />

(9) Because the program has set the z-axis value to 1cm, the gripper is directly above the middle of the two sides of the block, so it is not recommended to modify the values of z-axis and pitch angle.

(10) Then click **"Save"** to save the coordinate value to controller. The gripper will run to this position to pick object next time.

<img class="common_img" src="../_static/media/chapter_1/section_6/image15.png"  alt="loading" />

