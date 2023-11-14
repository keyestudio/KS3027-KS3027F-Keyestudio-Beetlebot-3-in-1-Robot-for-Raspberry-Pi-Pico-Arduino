## Get started with Arduino

### Windows System

![](media/6cf6312dc7c7db27794b54d58a8bf80c.png)

#### Installing Arduino IDE

When you get control board, you need to download Arduino IDE and driver firstly.

You could download Arduino IDE from the official website:

<https://www.arduino.cc/>, click the **SOFTWARE** on the browse bar, click“DOWNLOADS” to enter download page, as shown below:

![](media/bfe8c9e405c71123dee7921eddff86d3.png)

![](media/7250961db41ba42e4b881d77bd76a319.png)

There are various versions of IDE for Arduino. Just download a version compatible with your system. Here we will show you how to download and install the windows version of Arduino IDE.

![](media/894116c5cf0023dd9720946cfb441790.png)

There are two versions of IDE for WINDOWS system. You can choose between the installer (.exe) and the Zip file. For installer, it can be directly downloaded, without the need of installing it manually while for Zip package, you will need to install the driver manually.

![](media/a983a2f2eceb968afbff8ba0f0376240.png)

You just need to click JUST DOWNLOAD.

After the Arduino is downloaded, click“I Agree”to continue installing

![](media/00e334d3c756a2495da6f0d1b2db680a.png)

Click **Next**

![](media/de541d90a1cda992ad8e3f0cbaf95f94.png)

Then click **Install.**

![](media/7da9aca1e8432c59372e7c7ab2574bd9.png)

If the following page appears, click **Install.**

![](media/85b29de2aa791ecc77280ccde91e53c5.png)

![](media/739c41701fbcab202f0e587f534bad30.png)

![](media/d28223c55a30f949760779720fe4ec24.png)

![](media/a62ae27ea21104076335994547e7f4e4.png)

A- Used to verify whether there is any compiling mistakes or not.

B- Used to upload the sketch to your Arduino board.

C- Used to create shortcut window of a new sketch.

D- Used to directly open an example sketch.

E- Used to save the sketch.

F- Used to send the serial data received from board to the serial monitor.

#### Install the development board Pico

**Open Arduino IDE and click Tools**→**Board**→**Boards Manager...**

![Untitled](media/cc974af6f0b434a21d56bb0a00c8594e.png)

Search **Pico and select Arduino Mbed OS RP2040 Boards and click Install**

![](media/f28ae2a19124bca76f70c3d5cbe1cbec.png)

Click **Install**

![](media/32b8ade56a0e1da272a17abbfd5da41f.png)

![](media/36e0d1363908ff71cecbdee4b9e4e421.png)

Then click **Close**

![](media/2c0d5af2d55f5796444cc6349585e920.png)

#### Upload the pico compatible with Arduino

Disconnect the Raspberry Pi Pico with the computer, press and hold down the white button (BOOTSEL)，then connect the pico board to the computer.

Keep pressing the button before connecting the USB cable to the Pico board, otherwise the firmware can’t be uploaded.

![](media/33c91d51b2aeb2c943691706354aaad1.png)

Open Arduino IDE, click **File**→**Examples**→**01.Basics**→**Blink**

![Untitled](media/0911ade4582bd015f4cd518a5f65253f.png)

**Click Tools**→**Board**→**Arduino Mbed OS RP2040 Boards**→**Raspberry Pi Pico**

![Untitled](media/b5a2d5b5c4b2adb2a6ced1321aadd709.png)

Upload the script Blink to the pico board

![](media/27763aed4103e97b05209c747e53e8ee.png)

You can view this when uploading the sketch.

![](media/4a143c3abe363648730e40181a0e2050.png)

The indicator of the Raspberry Pi Pico starts flashing.

![](media/b282e1fbd4b4d492d19efe7062b7eddb.png) ![](media/529c3be102eb7414ac1e5e66fb203b6e.png)

Click **Tools**→**Port**→**COMx(Raspberry Pi Pico)**

Select the correct COM port on the computer.

In the following picture, the port is COM 15.

![Untitled](media/dd5f48649f98d0e8ac5570e83eb7e186.png)

Note

1.  When you upload a sketch of the Raspberry Pi Pico through Arduino, don’t select the port.

Check the port before uploading sketches.

1.  The Raspberry Pi Pico may not work due to code missing.

You can upload the Raspberry Pi Pico's firmware

### Mac System

![](media/a6fc83596009c574d8e29ef383748549.png)

Download Arduino IDE:

![](media/5d58d3cf67b308423ddb9f286f6cb697.png)

You can refer to the Windows system to operate.
