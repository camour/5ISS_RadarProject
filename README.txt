This projects aims at displaying in real-time, objects detected from a radar.
To do so there are two subprojects : 
- the first one (AWR1843-Read-Data) wants to display on a graphical interface all the objects detected and some informations for each object (distance, velocity etc.)
- the second one (yolov5) displays the classified objects

equipment : 
- Jetson txt 2
- radar AWR1843

requirements : 
- >=Python3.7
- Pi3
- Ubuntu

packages : 
- Matplotlib
- Seaborn
- SerialPort
- Numpy