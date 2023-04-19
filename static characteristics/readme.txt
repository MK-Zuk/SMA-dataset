Description is true for all static dataset (if changes are not mentioned in file).
Measurements are done for constant mechanical load.

Description of columns:
Izadg / Izadd - current set by Power supply for both directions up (g) and down (d)
Izmg / Izmd - current read by multimeter - it should be the same like above but it is measured more precisaly
Uzmg / Uzmd - Voltage read by multimeter
dLzmg0 / dLzmd0 - displacement read by sensor (quadrature encoder) with translation to mm
tempg / tempd - temperature read by Flir A325 IR camera with macro lens
dLg0 / dLd0 - normalized displacement - starts and finish in 0

Proper hysteresis characteristic shoud be generated for
up branch: X -> Izmg, Y -> dLg0
down branch: X -> Izmd, Y -> dLd0