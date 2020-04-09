# Autonomous Rover - FPGA Controlled Parallel and Perpendicular Parking
The document presents a software solution to be able to autonomously and semi-autonomously park a DE2 robot, or “DE2Bot” for short. DE2Bots expand upon the DE2 boards with motors and I/O devices including IR receivers and sonar capabilities among others. These additions enable a well-programmed DE2Bot to move and detect its surroundings via remote control. This implementation adds three sets of SCOMP assembly code: basic movement commands, specific combinations of movements, and IR-based remote initialization and direct guidance. The fully-programmed DE2Bot met all three requested project goals of semi-autonomous parking in a numbered perpendicular space and manual remote control for a ‘driver’ to park in each of a parallel and a perpendicular parking spot within the mock parking lot.

<p align="center">
  <img width="460" height="300" src="https://github.com/ashwinv96/autonomous-rover-parallel-perpendicular-parking/blob/master/a.png">
</p>
