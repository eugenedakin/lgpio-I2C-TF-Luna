# lgpio-I2C-TF-Luna
Uses the lgpio library to get sensor data from TF-Luna

The TF-Luna is a LiDAR (Light Radar) that measures accurate, single-point distance measurement in a small package that is ideal for robotics, and obstacle detection.

![](https://github.com/eugenedakin/lgpio-I2C-TF-Luna/blob/main/TF-LunaScreenGrab.png)

The lgpio library can be installed Raspberry Pi OS (Oct 2024) and instructions are available at http://abyz.me.uk/lg/download.html

Install instructions are:

1. install Raspberry Pi OS (64-bit)
2. Open a terminal and type the following commands:
3. sudo apt install swig python3-dev
4. sudo apt install python3-setuptools
5. sudo apt install libunwind8
6. wget https://github.com/joan2937/lg/archive/master.zip
7. unzip master.zip
8. cd lg-master
9. make
10. sudo make install
11. create a TF-Luna example program and copy the program and libraries to the RaspberryPi Desktop
12. give the executable permission to run with something like: 'sudo chmod +x TFLuna'
run the program with something like: 'sudo ./TFLuna'

