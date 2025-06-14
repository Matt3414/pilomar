# pi-lomar
RaspberryPi based miniature observatory.
A Python3 project to control a small camera and telephoto lens housed in a miniature 3D printed observatory enclosure.
This combines multiple open modules to handle object location, tracking and image capture.

This uses Python3 on the Raspberry Pi and CircuitPython on a connected Seeed Studio XIAO RP2040 microcontroller.

The physical telescope, mechanism and dome is buildable from the Instructables page.
[https://www.instructables.com/Pi-lomar-3D-Printed-Working-Miniature-Observatory-/]

The wiki for pi-lomar is here.
[https://github.com/Short-bus/pilomar/wiki]

Made Compatible with XIAO RP2040, CHDKptp instead of Pi cam,
"Adafruit Perma-Proto HAT for Pi Mini Kit - 
With EEPROM", and custom 1:60 worm gearbox.

### Todo
- [x] Create fork
- [ ] Change pins used in code
  - [ ] Raspberry Pi 4
  - [ ] Seeed Studio XIAO RP2040
- [ ] Change pico code to use neopixel instead of RGB led
- [ ] Change pico code to use 60:1 gear ratio instead of 240:1 (12000 steps per revolution vs 96000)
- [ ] Disable Pi camera from being requiered to be pluged in so i can use an external camera.
- [ ] Use Pio cores on RP2040 to interface with neopixel/Stepper Motors if more efficient
- [ ] Program EEPROM on HAT
- [ ] Connect CHDKptp to this program
