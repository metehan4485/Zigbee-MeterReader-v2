# Zigbee Meter Reader v2 📊

![Zigbee Meter Reader](https://img.shields.io/badge/Zigbee%20Meter%20Reader-v2-brightgreen)

Welcome to the **Zigbee Meter Reader v2** repository! This project features an ESP32-C6 based Zigbee sensor designed to read values from SML energy meters. Whether you want to monitor your energy consumption or develop smart home applications, this device provides a reliable solution.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Getting Started](#getting-started)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Supported Devices](#supported-devices)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)
- [Releases](#releases)

## Introduction

The Zigbee Meter Reader v2 leverages the capabilities of the ESP32-C6 microcontroller to create a low-power, battery-operated device that reads data from SML energy meters. This device can help users track their energy usage effectively, making it a valuable tool for both personal and professional applications.

![ESP32-C6](https://img.shields.io/badge/ESP32--C6%20Microcontroller-blue)

## Features

- **Battery Powered**: Designed for low power consumption, making it ideal for remote installations.
- **Zigbee Connectivity**: Communicates wirelessly with Zigbee networks for seamless integration.
- **SML Protocol Support**: Reads SML energy meter data accurately.
- **User-Friendly Interface**: Simple setup and easy-to-use features.
- **Open Source**: Fully customizable to meet your needs.

## Getting Started

To get started with the Zigbee Meter Reader v2, you will need the following:

1. **Hardware Requirements**:
   - ESP32-C6 microcontroller
   - SML energy meter
   - Zigbee compatible hub
   - Power source (battery or USB)

2. **Software Requirements**:
   - Arduino IDE or PlatformIO
   - Zigbee library for ESP32-C6
   - SML protocol library

## Installation

1. **Clone the Repository**:
   Use the following command to clone the repository to your local machine:
   ```bash
   git clone https://github.com/metehan4485/Zigbee-MeterReader-v2.git
   ```

2. **Install Required Libraries**:
   Open the Arduino IDE and install the necessary libraries for Zigbee and SML protocols.

3. **Upload the Code**:
   Open the project in the Arduino IDE, select the correct board (ESP32-C6), and upload the code.

## Usage

Once the installation is complete, follow these steps to use the Zigbee Meter Reader:

1. **Power On the Device**: Ensure that the device is powered on and connected to the Zigbee network.
2. **Access the Data**: Use a Zigbee-compatible hub to access the data from the SML energy meter.
3. **Monitor Energy Usage**: Track your energy consumption in real-time.

## Configuration

You can configure the Zigbee Meter Reader by editing the configuration file. Here are the key parameters you can adjust:

- **Zigbee Network ID**: Set the network ID for your Zigbee communication.
- **SML Meter Address**: Specify the address of the SML energy meter.
- **Polling Interval**: Adjust how frequently the device reads data from the meter.

## Supported Devices

The Zigbee Meter Reader v2 is compatible with a wide range of SML energy meters. Here are some commonly used devices:

- SML Energy Meter Model A
- SML Energy Meter Model B
- SML Energy Meter Model C

For a complete list of supported devices, refer to the documentation in the repository.

## Contributing

We welcome contributions from the community! If you would like to contribute to the Zigbee Meter Reader v2, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your branch and create a pull request.

Your contributions help improve the project and make it more useful for everyone.

## License

This project is licensed under the MIT License. Feel free to use, modify, and distribute the code as needed.

## Contact

For questions or support, please contact the project maintainer:

- **Name**: Metehan
- **Email**: metehan@example.com

## Releases

To download the latest version of the Zigbee Meter Reader v2, visit our [Releases page](https://github.com/metehan4485/Zigbee-MeterReader-v2/releases). Here, you can find the latest files to download and execute.

Check the Releases section for updates and new features. Your feedback is valuable, and we appreciate any contributions or suggestions you may have!

---

Thank you for checking out the Zigbee Meter Reader v2! We hope you find this project helpful for your energy monitoring needs.