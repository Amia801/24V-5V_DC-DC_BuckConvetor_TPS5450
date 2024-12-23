## 24V-5V DC-DC Buck Converter using TPS5450

This project is a compact DC-DC buck converter designed to step down a 24V input to a 5V output using the TPS5450 buck converter IC. The size of the PCB is 27mm x 17.5mm.

### Component List

| **Name** | **Value**   | **Footprint** | **Description**                |
|----------|-------------|---------------|-------------------------------|
| IC1      | -           | -             | TPS5450 buck converter        |
| L1       | 10uH           | SMD,10.1x11.6mm      | SMD Power Inductors             |
| Cin1     | 10uF 50V    | 1210          | X7R Ceramic Capacitor         |
| Cin2     | 10uF 50V    | 1210          | X7R Ceramic Capacitor         |
| Cboot    | 10nF 50V    | 0603          | X7R Ceramic Capacitor         |
| Cout1    | 220uF 6.3V  | 3528B         | Tantalum Capacitor            |
| Cout2    | 220uF 6.3V  | 3528B         | Tantalum Capacitor            |
| Rfbt     | 10kΩ        | 0603          | Resistor                      |
| Rfbb     | 3.24kΩ      | 0603          | Resistor                      |
| D1       | -           | DO-214AB      | SS56 Schottky Diode           |
| D2       | -           | DO-214AA      | SMBJ26A TVS Diode             |


### Schematic

Included in file.

### PCB Layout

Included in file.

### Features

- **High Efficiency**: The TPS5450 buck converter is capable of providing high efficiency in a small package.
- **Compact Size**: The PCB measures only 27mm x 17.5mm, making it suitable for applications with limited space.
- **Robust Design**: The use of high-quality capacitors and diodes ensures reliable performance.

### Applications

- Power supply for microcontrollers and other low-voltage devices.
- Battery-powered devices that require efficient step-down conversion.
- Embedded systems requiring a 5V power rail from a 24V source.

### Usage

1. **Input Voltage**: Connect a 24V input power supply to the input terminals.
2. **Output Voltage**: The output terminals provide a regulated 5V output.
3. **Load Capacity**: The converter is designed to handle load currents up to 5A.
