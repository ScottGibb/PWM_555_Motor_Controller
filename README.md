# PWM_555_Motor_Controller
A Simple PCB that contains a 555 timer for PWM control of various small motors. The design approach taken was to use leftover components from different salvages over the years to see what could be built that might be of use. This ended up being a PWM Controller using a 555 Timer. The CAD model of the PCB is shown below:

![3D Model of PWM Controller](docs/3D%20Model%20of%20PWM%20Fan%20Controller%20PCB.png)


# Design
As previously mentioned, the purpose of this PCB was to use existing parts and try something new that wasn't microcontroller based. This is why the 555 Timer was used along with a BJT transistor. The populated PCB can be seen below along with the Veroboard version:

![Populated PCB]()

![Veroboard PCB](docs/Veroboard%20Version.jpg)

# Improvements
As for design improvements, a lot of improvements can be made:

- Swap to fully SMT design as this will reduce EMI and create a better layout.
- Swap BJT for FET as this will reduce current consumption and stop the transistor from heating up during the PWM cycle.
- Due to the low current nature of the design, swapping screw terminals for JSTs would be appropriate as this would yield a better-looking design. It will also reduce the overkill of using 15A-rated terminals for a PCB used to control small motors.

# Software Requirements
The following software packages are required for this project:
- [Eagle](https://www.autodesk.co.uk/products/eagle/overview?term=1-YEAR&tab=subscription)
- [Fusion 360](https://www.autodesk.com/products/fusion-360/overview?term=1-YEAR&tab=subscription)

# Useful Links
- [Thingiverse Case](https://www.thingiverse.com/thing:4596800)
- [JLCPCB](https://jlcpcb.com/)
- [555 Timers](https://electronicsclub.info/555timer.htm)
- [Adjustable PWM 555 Timer](https://www.electronicshub.org/555-timer-pwm/)
