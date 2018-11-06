# OpenMindPX Autopilot

[![Releases](https://img.shields.io/github/release/PX4/Firmware.svg)](https://github.com/airmind/OpenMindPX/releases) [![DOI](https://zenodo.org/badge/22634/PX4/Firmware.svg)](https://zenodo.org/badge/latestdoi/22634/PX4/Firmware)

[![Build Status](http://ci.px4.io:8080/buildStatus/icon?job=Firmware/master)](http://ci.px4.io:8080/blue/organizations/jenkins/Firmware/activity) [![Coverity Scan](https://scan.coverity.com/projects/3966/badge.svg?flat=1)](https://scan.coverity.com/projects/3966?tab=overview)

[![Slack](https://px4-slack.herokuapp.com/badge.svg)](http://dronetag.slack.com)

This repository holds the [OpenMindPX](http://www.mindpx.net) flight control solution for drones, with the main applications located in the [src/modules](https://github.com/airmind/OpenMindPX) directory. It also contains the OpenMindPX Drone Middleware Platform, which provides drivers and middleware to run drones.

* Official Website: http://www.mindpx.net (License: BSD 3-clause, [LICENSE](https://github.com/PX4/Firmware/blob/master/LICENSE))
* [Supported airframes](https://docs.px4.io/en/airframes/airframe_reference.html) ([portfolio](http://px4.io/#airframes)):
  * [Multicopters](https://docs.px4.io/en/airframes/airframe_reference.html#copter)
  * [Fixed wing](https://docs.px4.io/en/airframes/airframe_reference.html#plane)
  * [VTOL](https://docs.px4.io/en/airframes/airframe_reference.html#vtol)
  * many more experimental types (Rovers, Blimps, Boats, Submarines, etc)
* Releases: [Downloads](https://github.com/airmind/OpenMindPX/releases)


## OpenMindPX users and development

OpenMindPX is a sub-project of DroneTag. To find guides and technical supports on OpenMindPX flight or development, please visit [DroneTag discussion group](http://www.mindpx.net:899)


## Supported Hardware

This repository contains code supporting these Autopilots:
  * [Airmind MindPX V2.8](http://www.mindpx.net/assets/accessories/UserGuide_MindPX.pdf)
  * [Airmind MindRacer V1.2](http://mindpx.net/assets/accessories/mindracer_user_guide_v1.2.pdf)
Following boards are also be supported:
  * [Snapdragon Flight](https://docs.px4.io/en/flight_controller/snapdragon_flight.html)
  * [Intel Aero](https://docs.px4.io/en/flight_controller/intel_aero.html)
  * [Raspberry PI with Navio 2](https://docs.px4.io/en/flight_controller/raspberry_pi_navio2.html)
  * [Parrot Bebop 2](https://dev.px4.io/en/advanced/parrot_bebop.html)
  * FMUv2.x
    * [Pixhawk](https://docs.px4.io/en/flight_controller/pixhawk.html)
    * [Pixhawk Mini](https://docs.px4.io/en/flight_controller/pixhawk_mini.html)
    * [Pixfalcon](https://docs.px4.io/en/flight_controller/pixfalcon.html)
  * FMUv3.x [Pixhawk 2](https://docs.px4.io/en/flight_controller/pixhawk-2.html)
  * FMUv4.x
    * [Pixracer](https://docs.px4.io/en/flight_controller/pixracer.html)
    * [Pixhawk 3 Pro](https://docs.px4.io/en/flight_controller/pixhawk3_pro.html)
  * FMUv5.x (ARM Cortex M7, future Pixhawk)
  * [Gumstix AeroCore](https://www.gumstix.com/aerocore-2/) (only v2)
  * [Bitcraze Crazyflie 2.0](https://docs.px4.io/en/flight_controller/crazyflie2.html)



