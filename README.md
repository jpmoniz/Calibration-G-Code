# Calibration-G-Code

Gcode programs used for calibration of a Delta Style robot with MK

G29 Is a Gcode program to probe the Bed of a Delta Printer.

M207 found in remap.py  is the skeleton i'm using to calculate the required adjustments.

M252 & M253 Set offsets in the kinematics from information calculated in M207. 
I plan to embed this into M207 functionality.
