# Tactile_Sensor
Tactile Sensor (Bead Sight) Project Code 

## Data Collection:
Inside the data colletion folder is the arduino code (in the Arduino folder) which is ran on the aruino to collect force data. Scale Data Reader.py is used to control the arduino over serial link and to save the recorded forces and timestamps

The main data processing is done in the Data Processing.py file, which splits the recorded video into a sub video for each test, and outputs the processed contact info for each test. Info for the test is generated by generate_info_file.py, which extracts and saves information on the calibration frame (for alignign video and arduino time), start frame, stop frame frames, and center point and contact points (extracted from the g-code) the finger presses at.
