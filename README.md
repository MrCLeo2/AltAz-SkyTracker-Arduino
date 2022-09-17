# AltAz-SkyTracker-Arduino
This Project was created with the goal of building an Arduino based Go-To/SkyTracker for the Skywatcher 200p Telescope. Since it uses an Alt-Az mount, traditional Skytracker will not work


**Features**:
- Motorized Go-To System with various Sky-Objectes to choose from the databank
- Automated skytracking

**Hardware Requirement**:
- Arduino (model at the moment unknown)
- 2 NEMA23 stepper motor
- 2 Tb6000 motor driver
- GPS module (gy-gps6mv2)
- 2 360° Hall effect sensor


**Theorie

All known sky-objects are stored using the celestial coordinates.
To get the exact location of the deep sky objects from the observers perspective, we need to convert celestial coordinates to alt/az.



