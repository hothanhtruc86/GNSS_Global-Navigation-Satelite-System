# GNSS_Global-Navigation-Satelite-System1
Reference from # GNSS DATA PROCESSING Volume I: Fundamentals and Algorithms
https://gssc.esa.int/navipedia/GNSS_Book/ESA_GNSS-Book_TM-23_Vol_I.pdf
## TABLE OF CONTENT

- [Definition](#Definition)
- [GNSS-Segments](#GNSS-Segments)
  - [Space-Segment](#Space-Segment)
  - [Control-Segment](#Control-Segment)
  - [User-segment](#User-segment)
- [Usage](#usage)
- [Features](#features)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Definition
GNSS is the generic term denoting a satelite navigation system, for example: GPS (US), Glonass (Russia), Galileo (Europe) and Beidou (China).
3 main elements:
![alt text](https://www.rfwireless-world.com/images/GNSS-architecture.jpg)

- Space segment: comprises the satelites
- Control seegment (Ground Segment): responsible for proper operation of the system.
- User segment: including GNSS receiver providing positioning, velocity, and precise timing to users.
  
## GNSS-Segments
### 1.Space-Segment
Function: Generate and transmit code and carrier phase signals, store and broadcast the navigation message uploaded by the control segment.
Formation: by satelite constellations with enugh satelites to ensure that users will have at least four satelites in view simultanenously from any point on Earth's surface at any time.
The basic observable in a GNSS is the time required for a signal to travel from the satellite (transmitter) to the receiver. This travel time, multiplied by the speed of light, provides a measure of the apparent distance (pseudorange) between them.
