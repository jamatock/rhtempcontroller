I made this to monitor RH and temperature at a remote location and activate an exhaust vent to adjust the environment back down.  It also has a programmable timer and a green LED on an auto off outlet.  More info is available in the product manual available in the download section.

### Brief function overview: ###

Monitors both RH and temp in a single remote location

Monitors onboard temperature

Adjustable recycle timer (1 min to 18 hour on time, 1 min to 12 hour off)

Green LED strip with an auto off time of 30 minutes
  * LEDs dim to 20% 5 minutes prior to shutoff to avoid anybody getting trapped in darkness by surprise
  * Pressing button again resets shutoff timer
Has 4 adjustable values
  1. Timer on time
  1. Timer off time
  1. RH goal
  1. Temperature goal

When either value is exceeded a relay intended for an exhaust vent is activated.  This relay has a minimum on time of 20 minutes to avoid rapid cycling.



### License info : ###

DallasTemp:
Arduino Library for Dallas Temperature ICs, version 2.5.0 Credits
The OneWire code has been derived from
http://www.arduino.cc/playground/Learning/OneWire.
Miles Burton <> originally developed this library.
Tim Newsome <> added support for multiple sensors on
the same bus.
James Whiddon has refactored the core code to provide accurate timings, increased sensor resolution, detect parasite power (etc).
License
This library is free software; you can redistribute it and/or
modify it under the terms of the GNU Lesser General Public
License as published by the Free Software Foundation; either
version 2.1 of the License, or (at your option) any later version.

This library is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU
Lesser General Public License for more details.

You should have received a copy of the GNU Lesser General Public
License along with this library; if not, write to the Free Software
Foundation, Inc., 51 Franklin St, Fifth Floor, Boston, MA 02110-1301 USA"