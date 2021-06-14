# RobotBox: Assetto Corsa's alternative auto gearbox

RobotBox is a standalone gearbox logic program for use with Assetto Corsa. It receives and processes data from AC in realtime, then feeds "change up/down" commands into AC's manual gearbox through keyboard hooks.

It can produce faster laptimes than the default auto box - video:
https://youtu.be/_aMLFCIFZnI

Built using C++ and the AC Shared Memory Interface.

# Installation
- Download the zip
- Move the files in "Debug" to a folder of your choice
- Unless you want to edit the code, you can safely bin the rest of the downloaded files

# Required AC settings
- "Shift Up/Down" must be set to the defaults of Space/LCtrl respectively
- "Combine with keyboard input" must be checked in the "Advanced" settings for your controller
- "Automatic Gearbox" must be unchecked

# Usage
- Run SharedMemoryExample.exe
- Load up AC and play as normal
- Simply close the application when done

IMPORTANT! Unlike the default auto box, you will need to shift from N to 1st yourself.

# Additional
RobotBox has been tested with the Lotus Elise, Mazda MX-5, Toyota Supra and BMW Z4 road cars. Please feel free to test with other cars, file bug reports, record videos, make PRs etc.
