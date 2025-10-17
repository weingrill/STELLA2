# STELLA2

STELLA2 is a TwinCAT-based measurement project designed for precise control and data acquisition in automated telescope systems. This repository contains the PLC configuration and associated files necessary for deployment and operation.

## Configuration
*	PLC Model: BTN-000T1J5B
*	AMS Net-ID: 5.122.40.156.1.1
*	IP Address: 141.33.128.170 ￼

## Project Structure
*	STELLA2.sln: TwinCAT solution file for the project.
*	Azimuth (AX5125-0000-0214).xti: Configuration file for the azimuth axis.
*	Elevation (AX5125-0000-0214).xti: Configuration file for the elevation axis.
*	.gitignore: Specifies intentionally untracked files to ignore. ￼ ￼

## Getting Started

To set up and run the STELLA2 project:
1.	Prerequisites:
*	Install Beckhoff TwinCAT 3 on your development machine.
*	Ensure network connectivity to the target PLC device.()
2.	Clone the Repository:
  ``git clone https://github.com/weingrill/STELLA2.git``
3.	Open the Project:
*	Launch TwinCAT XAE.
*	Open the STELLA2.sln solution file.￼
4.	Configure the PLC:
*	Download the project to the PLC.
*	Activate the configuration and restart the PLC in Run mode. ￼

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Contact

For questions or support, please contact the repository maintainer via GitHub issues or email.
