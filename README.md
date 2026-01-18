# Human Computer Mouse Interaction Combining Survey Responses, Cursor Motion, and Inertial Sensor Data

This repository contains:
- cursor data aquisition code
  - code written in python and processing language to render participant tasks and record cursor data
- cursor data
  - raw cursor data of participants that can be paired to inertial and survey data by the matching ID in the filename
  - columns represent time in seconds, x cursor position and y cursor position
- example motion analysis
  - example code written using python jupyter notebooks demonstrating loading and pairing mixed datasets
- inertial data acquisition code
  - code written in python and processing language to record inertial data through serial port
  - code written for Arduino microcontroller to collect inertial data and report using serial communication (TBD)
- inertial data
  - raw inertial data of participants that can be paired to cursor and survey data by the matching ID in the filename
  - columns include time in seconds; x, y, and z acceleration in earth gravity units; and x, y, and z axis rotaional acceleration
- survey
  - survey questions as presented to participants
  - survey results as numerical and text bsaed responses
  - column names of survey responses

The study was performed following IRB review and determined to be exempt.
