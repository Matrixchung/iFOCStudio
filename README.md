## SimpleFOCStudio

A GIU application developed  with Python/PyQt5 to manage and configure any [SimpleFOC](https://github.com/simplefoc)  BLDC controlled device using serial port communications. It as a UI that plots in real time monitored variables PyQtGraph. It currently supports [SimpleFOC 2.1](https://github.com/simplefoc/Arduino-FOC/releases/tag/v2.1) devices. 

<p align="center">
  <img  src="./DOC/new_gif.gif">
  <!-- <img src="./DOC/treeview.png"> -->
</p>

### Installation and Usage

- Install Python if you don't have it installed yet 
- Clone this repo or download the zip file
- cd to the folder
- run: 
```
pip install -r "requirements.txt"
```
- run: 
```
python simpleFOCStudio.py
```
- Once in the application add a device (+) and configure serial port settings
- Connect to the serial port you have to have a SimpleDOC device that 
attends to the command as explained in [this example](https://docs.simplefoc.com/communication)
- Start playing  and have fun :)
