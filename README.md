# Multi particle(filler) generator for Ansys DesignModeler or Spaceclaim
ANSYS SpaceClaim RVE Multi-Filler Generator is a scripting tool designed to automate the generation of Representative Volume Elements (RVEs) with multiple fillers in ANSYS DesignModeler. This script helps in modeling composite materials by efficiently placing fillers within a matrix.
In ANSYS, the current support is limited to either a single particle type or a random particle distribution, which restricts the ability to analyze multiple particles effectively. This script was developed to overcome these limitations by enabling the generation of multiple filler types in a structured manner, providing better customization and control over the composite microstructure.


## Features

- Automates RVE generation with multiple fillers.
- Checks for overlap and hollow geometries.
- Ensures all particles remain within the boundaries.
- Supports custom filler shapes, sizes, and distributions.(As of now it only supports Spherical Fillers or particles with different radius)


## Requirements

- ANSYS SpaceClaim and DesignModeler

- Python/IronPython (for scripting in SpaceClaim).

## Installation

Clone this repository:

git clone https://github.com/yourusername/ansys-spaceclaim-rve-multi-filler-generator.git

Open ANSYS SpaceClaim or Designmodeler (BE CAREFUL TO CHECK THE UNITS THE SCIRPT USES UM units, It can be modified by chanigng UM to MM in all places.)

Load the script into the Scripting Environment.

Run the script to generate RVEs with multiple fillers.

## Usage

Open ANSYS SpaceClaim and navigate to the Scripting panel.

Load the script (script.py or .scscript).

Configure filler parameters (size, shape, distribution).

Run the script to generate the RVE model.

## Sample Output
![OUTPUT](https://github.com/user-attachments/assets/0a2968f8-8154-4da4-9a75-590ad0630f41)


## License

This project is licensed under the MIT License – see the LICENSE file for details.

## Contributing

Feel free to submit issues or contribute by opening a pull request.

## Contact

For questions or suggestions, reach out via GitHub issues.
