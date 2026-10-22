# RV-C CAN Bus Analyzer

A lightweight and efficient desktop tool for parsing **RV-C (Recreational Vehicle CAN)** protocol data. Designed for RV enthusiasts and developers, it automatically identifies and decodes data from various devices upon connecting to the CAN bus.

##  Features

- **Auto-Identification**: Automatically recognizes and parses data from connected devices without complex configuration.
- **Supported Devices**:
  -  Inverter
  - ️ Solar Charge Controller
  -  Tank Sensor
  -  Generic DC Load
  - ️ Weather Station
- **Plug & Play**: Simply connect your CAN interface and launch the tool.
- **Lightweight**: No complex installation required, ready to run via batch script.

## ️ Prerequisites

- Windows OS
- A compatible CAN Bus Interface (e.g., Kvaser, Peak CAN, or USB-CAN adapters supported by the underlying driver).

##  Installation & Usage

1. **Download** the latest release from the [Releases](../../releases) page.
2. **Unzip** the package to your desired folder.
3. **Connect** your CAN bus interface to your computer and the RV-C network.
4. **Run** the application:
   - Double-click `RVCTool.bat` to launch the program.
5. The tool will automatically start scanning and parsing messages from supported devices.

## ️ Built With

- C++ / Qt

##  Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](../../issues).

##  License

This project is licensed under the [MIT License](LICENSE).

##  Contact

If you have any questions or need custom development for embedded systems/CAN protocols, feel free to reach out:
- **Email**: [wlc@demmo.top][wlcwjy@163.com]
- **Portfolio**: [https://site.demmo.top/](https://site.demmo.top/)]