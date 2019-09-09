# EV3G4C
The intention of this project is to provide a set of 'C' functions that emulate the behaviour of the various sensor and motor 'blocks' in the EV3 Graphical programming language.

This should act as a familiar interface layer for those wishing to migrate from the EV3-G language to 'C'.  

The incentive for the project arises from the recent change in the First Lego League (FLL) rules that now allow any language to used to control the EV3 robot rather than being limited to EV3-G.

This API is implemented as a set of wrapper functions using the C4EV3 api and development mechanisms (https://c4ev3.github.io/).  While very useful and helpful in my opinion C4EV3 is just a little too low-level as an introduction to C programming for the children/students in FLL teams.

The original releases of this code will focus on basic motor control and gyro & light sensors... those items being the ones of immediate use in our FLL team - the 'ninjaneers'.

This project is also expected to be a learning opportunity for the team members with regard to writing and maintaining code - as bugs are encountered the members will be encouraged to provide specific descriptions of the issue and then to help identify the cause; propose, implement and test the solution; and finally publish update.  The majority of the code will be implemented in the simplest methods possible - it will be aiming to instruct rather than for efficiency.

It is not expected that this will EVER be a complete and accurate emulation/implementation of the EV3-G functions merely provide a familiar and identifiable interface layer that EV3-G users will at least recognise.
