# DC-Motor-Controller

This is a locked antiphase drive implementation. Only one drive pulse and its complementary  is generated from microcontroller. Using couple of smitt trigger and capacitor dead time is generated. Then the pulses are given to ir2110 mosfet high low driver. At 50 percent duty cycle motor will stop. Duty cycle greater than 50 percent will move motor in a direction. Duty cycle less then 50 percent will move motor another direction.
