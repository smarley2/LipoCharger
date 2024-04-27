# LiPo Charger 1-4S with BQ25730 and STM32G474 feeded by USB-C adapter.

This GitHub project provides an open-source design for a Lithium Polymer (LiPo) charger with support for 1 to 4S configurations. The goal is to not waste more money and generate more trash with power supplies as we already have at home usb chargers from our smartphones. It uses the Texas Instruments BQ25730 chip and is controlled by the STM32G474 microcontroller. This project includes design files, firmware, and setup instructions.

## Status
**Note:** This project is currently under development. Some features may not be fully implemented, and the design or firmware may change over time. Please check back regularly for updates or join the discussion to stay informed.

## Disclaimer
**This project is provided "as is" without any warranty or guarantee of safety. The user assumes all risks associated with building, using, and modifying the project. The author and contributors are not responsible for any damage, injury, or loss caused by this project.** Users must review all aspects of the project and ensure safety measures are in place before using it.

## Features
- Supports 1 to 4S LiPo battery charging
- Based on Texas Instruments BQ25730
- Controlled by STM32G474 microcontroller
- User interface for setting charging parameters (TBD how to implement, maybe with aditional ESP32 for interface and wifi)
- Safety features for overcurrent and overvoltage protection
- Output status LEDs to indicate charging status

## Contents
- Hardware design files (schematic, PCB layout)
- Firmware source code for STM32G474

## Hardware Requirements
- Texas Instruments BQ25730 chip
- STM32G474 microcontroller
- USB C power adapter
- Components (resistors, capacitors, MOSFETs, etc.)
- Printed circuit board (PCB) for assembly

## Software Requirements
- Development environment for STM32 (such as STM32CubeMX)
- Compiler and debugging tools for STM32
- Version control system (like Git) for firmware development

## Building and Assembling
1. **Hardware Design**
   - Use the provided schematic and PCB layout to design the hardware.
   - Order the PCB and components as specified in the Bill of Materials (BOM).
   - Assemble the PCB, ensuring proper soldering and component placement.

2. **Firmware Development**
   - Clone this repository to your local machine.
   - Open the project in STM32CubeIDE or a similar development environment.
   - Compile and upload the firmware to the STM32G474 microcontroller.

## Setup and Configuration
1. **Power Supply**
   - Connect a suitable power source to the charger.
   - Ensure all safety precautions are followed.

2. **Battery Connection**
   - Connect your LiPo battery to the charger, ensuring the correct polarity.

## Safety Considerations
- Always ensure correct polarity when connecting batteries.
- Do not leave charging unattended.
- Ensure proper ventilation to avoid overheating.
- Follow all safety guidelines regarding lipo charging.

## Contributing
Contributions are welcome! If you'd like to collaborate, please contact me at [smarley2]. Feel free to open issues, suggest features, or submit pull requests.

## License
This project is licensed under the [MIT License](LICENSE). See the LICENSE file for more details.

## Contact
For questions or further information, contact [smarley2].
