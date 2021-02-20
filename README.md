# Customize the UI yourself, 800*480 Capacitive
This is Capacitive touch screen,uart serial screen,4.3inch, for marlin based 3D printer control board

### Connect to PandaPI

![Opensource](https://gitee.com/luojin/bob_robot/raw/master/imges/34552.jpg)

![Opensource](https://gitee.com/luojin/bob_robot/raw/master/imges/134412.jpg)

### Connect to SKR E3-DIP
![Opensource](https://gitee.com/luojin/bob_robot/raw/master/imges/151653.jpg)

you can also download all the source code and tools here: https://drive.google.com/drive/folders/1toJU_dtaq2irLVg9aK6b8gs5-JVmY1cc?usp=sharing

### How to customize UI
[How to customize UI](https://github.com/markniu/PandaPi/wiki/Customize-the-UI-(replace-Image)), those pictures of UI are based on the [FYSETC LCD](https://github.com/FYSETC/FYSTLCD). 
Instead of resistive touch and low resolution 480*272, This LCD is capacitive touch and high resolution 800*480 screen

### Uploade UI Files to screen
Step 1：Format the TF card and copy files run windows command system as administrator, then enter：
```c
format g:/fs:fat32/a:4096/q
```
Note: g is the drive letter of your TF card ，and the card size must be 1-16G.

Step 2：Copy the folder DWIN_SET which contained your newest 32.icl to TF card,LCD will only recognize this folder name;

Step3:  Insert the TF card into the card socket (back side of the screen) ,and then power on the screen. Wait for the blue screen and appear on the first line of the screen “SD Card Process... END !” it’s may take 1-2minutes. Turn off the power and unplug out the TF card, re-power the screen Wait for the boot screen.

<img width="450"  src="https://gitee.com/luojin/bob_robot/raw/master/imges/update_lcd.jpg"/>


### where to buy  
https://www.pandapi3d.com/product-page/serial-800-480-capacitive-touch-screen-for-printer


