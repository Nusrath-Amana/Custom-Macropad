# Custom-Macropad

## Introduction

The Custom Macropad is a versatile input device featuring 17 programmable keys and 1 knob.These keys can be assigned to execute various commands, keyboard shortcuts, and macros, allowing users to automate repetitive tasks on their computers. It can be connected via Bluetooth® 4.0 using the ESP32 in BLE mode, making it compatible with various devices such as desktops, laptops, tablets, and smartphones. The device includes two USB ports for charging and power output, along with a power management unit ensuring optimal battery life. This report presents a comprehensive overview of the Custom Macropad, covering its hardware and software design, implementation, functionality, user interface, performance analysis, and conclusion.

### Features and Functionality

The custom macro pad is equipped with the following features:
- 17 Programmable Keys
- 1 Programmable Knob
- Macros and Keyboard Shortcuts
- Mechanical Switches
- Wireless Connectivity
- Dual USB Ports
- Power Management
- Long Battery Life
- Compact and Portable Design
- Versatile Device Support

## Implementation of Custom Macro Pad

The implementation of the custom macro pad involves several key components and steps. 

### Hardware Components

#### Microcontroller:
The heart of the Macro Pad is the ESP32 development board. The ESP32 is chosen for its high processing power, low power consumption, built-in Wi-Fi and Bluetooth capabilities, and sufficient GPIO pins to handle the matrix keypad. Additionally, the ESP32's versatility allows for seamless integration of various communication protocols and user interaction options.

#### Matrix Keypad:
The Macro Pad features a matrix keypad layout with 17 tactile switches. The matrix configuration optimizes the number of GPIO pins used to interface with the switches, making it more efficient than individually wiring each switch. Each switch is assigned a unique position within the matrix, allowing users to press any combination of keys to trigger specific macros. CHERRY G99-0742 mechanical switches are used as the keys to provide durability and tactile feedback during keypresses.

#### Four Levels of Switch Assignment:
A 10-pin four-position sliding switch is used to enable users to toggle between different sets of macros or commands stored in the custom macro pad. Each position of the sliding switch corresponds to a different level, and each level represents a unique configuration of programmable keys and knob assignments.

#### Programmable Knob:
A rotary encoder with a push-button function is employed as the programmable knob for easy interaction.

#### LED Indicators:
LEDs are integrated into each key and the knob to provide visual feedback during testing and operation.

#### Battery and Power Management:
A rechargeable battery and power management circuitry ensure efficient power utilization and extended battery life. Two 3.7V Li-ion 3200mAh batteries are used with the T6845-C power bank module.


## Macro Pad Functionality

The custom macro pad offers several functionalities to enhance productivity and automation:

1. Programmable Keys
2. Programmable Knob
3. Macro Recording and Playback
4. Four Levels of Switch Assignment
5. Wireless Connectivity
6. LED Feedback
7. Power Management

## Applications

The custom macro pad finds applications in various fields, including:
- Gaming
- Programming
- Productivity

## Conclusion

The project aims to design and develop a custom macro pad, a small keyboard with extra programmable keys and a knob, to provide users with enhanced efficiency and productivity. The macro pad allows users to assign various commands, keyboard shortcuts, and macros to the programmable keys, enabling the automation of long and repetitive tasks on a computer. This automation can save valuable time and effort, making the custom macro pad a valuable tool for gamers, programmers, and professionals across different fields.

