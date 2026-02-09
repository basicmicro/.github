# Basicmicro — Brushed & Brushless DC Motor Controllers

We design and manufacture programmable brushed and brushless DC motor controllers for robotics, automation, and industrial applications. Our **RoboClaw** and **MCP** product lines feature auto-tune PID, quadrature encoder feedback, multiple control modes, and USB configuration through our free [Motion Studio](https://www.basicmicro.com/motor-controller-downloads) software.

This GitHub contains our official libraries, example code, and configuration files for integrating RoboClaw and MCP motor controllers into your projects.

---

## Official Libraries

| Library | Platform | Install | Docs |
|---------|----------|---------|------|
| [basicmicro_python](https://github.com/basicmicro/basicmicro_python) | Python 3 / Raspberry Pi / Linux / Windows / macOS | `pip install basicmicro` | [API Reference](https://github.com/basicmicro/basicmicro_python/blob/main/docs/api_reference.md) |
| [basicmicro_arduino](https://github.com/basicmicro/basicmicro_arduino) | Arduino / ESP32 / ESP8266 | Arduino Library Manager → search "Basicmicro" | [README & Examples](https://github.com/basicmicro/basicmicro_arduino) |
| [basicmicro_ros2](https://github.com/basicmicro/basicmicro_ros2) | ROS 2 | See README for install steps | [README & Examples](https://github.com/basicmicro/basicmicro_ros2) |

## Legacy Libraries

The following libraries are for **RoboClaw V5 and earlier** or **RoboClaw 2x60A / 2x60AHV V7 and earlier**. For all current RoboClaw and MCP controllers, use the official libraries above. Raspberry Pi users should use [basicmicro_python](https://github.com/basicmicro/basicmicro_python). ESP32 and ESP8266 users should use [basicmicro_arduino](https://github.com/basicmicro/basicmicro_arduino).

| Repository | Platform | Description |
|------------|----------|-------------|
| [roboclaw_python_library](https://github.com/basicmicro/roboclaw_python_library) | Python | Legacy RoboClaw Python library |
| [roboclaw_arduino_library](https://github.com/basicmicro/roboclaw_arduino_library) | Arduino | Legacy RoboClaw Arduino library |
| [raspberry_pi_packet_serial](https://github.com/basicmicro/raspberry_pi_packet_serial) | Raspberry Pi | Dual motor control with encoder feedback via packet serial |
| [raspberry_pi_standard_serial](https://github.com/basicmicro/raspberry_pi_standard_serial) | Raspberry Pi | Simple motor speed control via standard serial |
| [raspberry_pi_packet_serial_bus](https://github.com/basicmicro/raspberry_pi_packet_serial_bus) | Raspberry Pi | Multi-controller bus mode on one serial connection |
| [roboclaw_esp32_motor_control](https://github.com/basicmicro/roboclaw_esp32_motor_control) | ESP32 | Legacy ESP32 motor control example |
| [roboclaw_esp8266_thing_motor_control](https://github.com/basicmicro/roboclaw_esp8266_thing_motor_control) | ESP8266 | Legacy WiFi-enabled motor control on SparkFun Thing |
| [arduino_standard_serial](https://github.com/basicmicro/arduino_standard_serial) | Arduino | Basic speed and direction control via standard serial |
| [using_encoders_python](https://github.com/basicmicro/using_encoders_python) | Python | Encoder position and speed feedback example |
| [rc_mode_config_files](https://github.com/basicmicro/rc_mode_config_files) | Config files | Pre-configured settings for RC receiver control mode |

---

## Brushed DC Motor Controllers

RoboClaw dual-channel brushed DC motor controllers are available from **2×7A** through **2×60A** at up to 34VDC, plus high-voltage models rated to **60VDC**. All models feature regenerative braking, auto-tune PID, packet serial / RC / analog / simple serial control modes, and onboard scripting.
➡️ **[Browse RoboClaw Motor Controllers](https://www.basicmicro.com/motor-controller)**

**MCP series** industrial motor controllers add CAN bus (CAN, CANopen, SimpleCAN), RS-232 serial, up to 8 configurable I/O pins, and the built-in MCL scripting language for standalone programmable motion control — or integrate directly with existing PLCs over CAN bus. 30A to 60A continuous at 60VDC for AGVs, industrial automation, and commercial OEM applications.
➡️ **[Browse MCP Motor Controllers](https://www.basicmicro.com/motor-controller-industrial)**

## Resources

| | |
|---|---|
| 🌐 **[basicmicro.com](https://www.basicmicro.com/)** | RoboClaw and MCP Product Home |
| 📖 **[Documentation & User Manuals](https://www.basicmicro.com/motor-controller-downloads)** | User Manual, Motion Studio, DataSheets, CAD drawings |
| 💾 **[Tutorials & Guides](https://resources.basicmicro.com/)** | Motor controller configuration, PID tuning, and diagnostics |
| 🛒 **[Motor Controller Products](https://www.basicmicro.com/motor-controller)** | Find the right controller by voltage, current, and features |
| 📧 **[Contact Support](https://www.basicmicro.com/Contact_ep_7.html)** | Technical support and sales inquiries |

## About Basicmicro

Basicmicro has been designing programmable motor controllers in California since 2004. Our RoboClaw controllers are used worldwide in robotics competitions, university research, autonomous vehicles, industrial automation, and consumer products.

[![Basicmicro Website](https://img.shields.io/badge/Website-basicmicro.com-blue)](https://www.basicmicro.com/)
[![Motion Studio](https://img.shields.io/badge/Software-Motion%20Studio-green)](https://www.basicmicro.com/motor-controller-downloads)
[![Documentation](https://img.shields.io/badge/Docs-resources.basicmicro.com-orange)](https://resources.basicmicro.com/)
