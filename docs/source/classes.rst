Classes
=====

.. autosummary::
   :toctree: generated

   Controller
   Simulator

Controller
########

reset
**********************
Resets data of controller by setting state estimate to a 6x1 array of zeros.

run
**********************
*Inputs*: 

*  t: Current time (s)
*  star_meas: 1D array of length 14. Contains the image coordinates $y_i$ and $z_i$ of the i'th star at indices $2i$ and $2(i + 1)$ respectively. 

*Outputs*:

*  front_torque: Torque applied to front reaction wheel
*  back_torque: Torque applied to back reaction wheel
*  left_torque: Torque applied to left reaction wheel
*  right_torque: Torque applied to right reaction wheel


Simulator
########

reset
**********************
Resets spacecraft orientation (yaw, pitch, roll), angular velocity to 0, and the scope noise to 0.1. 
