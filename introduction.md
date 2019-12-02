# What is this workshop about?
This workshop will go over how to utilize the Raspberry Pi + MATRIX Creator for IoT, edge, & AI in robotics. 

These tools can be used to accelerate your next product/project.

In this workshop, you will learn how to:
- Read Sensors
- Control NFC
- Set GPIOs
- Set up voice assistant
- Voice control robot to react to sensors with backup NFC control (simulated with IMU controlled servo)

These concepts can be expanded to create voice-based IoT, edge or AI products.

Additionally, the quick and easy API for accessing sensor data with the MATRIX Creator can allow for various robotics control algorithms such as PID, Kalman filters, and more!

![](/images/matrix_robots.gif)

***
The image provided has the following packages installed on the *Raspbian Stretch OS*.
- `matrixio-creator-init` : this package initializes the MATRIX Creator and flashes the FPGA, MCU, and zigbee chip.
- `matrixio-kernel-modules` : this package enables Snips to speak with the MATRIX mics through ALSA
- All Snips packages & services
- [MATRIX HAL](https://matrix-io.github.io/matrix-documentation/matrix-hal/overview/) : The Hardware Abstraction Layer (HAL), based in C++, which handles all the SPI communication between the FPGA and Raspberry Pi
- [MATRIX Lite JS](https://matrix-io.github.io/matrix-documentation/matrix-lite/getting-started/javascript/) : JavaScript wrapped around MATRIX HAL for easy "one line of code" programming
- [MATRIX Lite NFC JS](https://matrix-io.github.io/matrix-documentation/matrix-lite/js-reference/nfc/) : NFC library wrapped around MATRIX HAL NFC which programs the PN512 NXP NFC chip to read/write to NFC tags

