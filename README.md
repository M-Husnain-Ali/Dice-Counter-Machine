# 🎲 Dice Counter Project

## 📝 Overview

A sophisticated digital circuit design project that accurately tracks and displays dice roll frequencies in real-time. This system integrates with existing mechanical dice-throwing equipment to provide precise counting and display functionality through LCD screens.

## 📊 Circuit Diagram

![Dice Counter Circuit](circuit.png)

*Circuit diagram showing the complete system architecture with:*
- 3-to-8 line Decoder for input processing
- Six 4-bit Counters for frequency tracking
- NAND gates for logic control
- Display ICs for each frequency output
- Binary switches for configuration

## ✨ Key Features

- Real-time dice roll frequency counting
- Six independent LCD display outputs
- Seamless integration with existing mechanical equipment
- High accuracy and reliability
- Zero latency response time
- Automatic sample detection and processing

## 🛠️ Technical Specifications

### Input System
- 4 input lines for dice number detection
- 1 dedicated sample availability signal line
- Compatible with standard TTL/CMOS logic levels

### Core Components
| Component | Quantity | Purpose |
|-----------|----------|----------|
| 3-to-8 Line Decoder | 1 | Input signal decoding |
| 4-bit Counters | 6 | Frequency tracking |
| Display ICs | 6 | LCD screen control |
| NAND Gates | Multiple | Logic control |
| Binary Switches | As needed | Manual configuration |

### Display System
- Six independent LCD screens
- Real-time frequency updates
- Clear numerical display
- Power-efficient operation

## 📋 Prerequisites

### Software Requirements
- LogicWorks (Required to open and simulate the `.cct` circuit file)
  - Download LogicWorks from official sources
  - Minimum version: 5.0 or higher recommended
  - Windows/macOS compatible

### Hardware Requirements
- Mechanical dice throwing equipment
- Dice counter with 5-line output interface
- Power supply (5V DC)
- Basic electronic tools for installation
- LCD display units (6x)

## 🗂️ Project Files

- `Dice Counter Project.cct` - LogicWorks circuit file containing the complete digital design
- `circuit.png` - High-resolution circuit diagram for quick reference
- `README.md` - Project documentation and setup guide

## 🔧 Installation & Setup

1. **Software Setup**
   - Install LogicWorks on your system
   - Open `Dice Counter Project.cct` using LogicWorks
   - Verify all components are properly loaded

2. **Hardware Setup**
   - Mount the circuit board in a suitable enclosure
   - Connect power supply (5V DC)
   - Attach LCD displays to designated ports
   - Connect dice counter output to input terminals

3. **System Integration**
   ```
   Input Connections:
   - PIN 1-4: Dice number input
   - PIN 5: Sample availability signal
   - GND: Common ground
   - VCC: 5V power supply
   ```

4. **Testing**
   - Power on the system
   - Verify all LCD displays are functional
   - Run a test sequence using manual inputs
   - Validate counter accuracy

## 💻 Usage Instructions

1. Ensure all power connections are secure
2. Power on the mechanical dice throwing equipment
3. Initialize the dice counter system
4. Start the dice throwing sequence
5. Monitor real-time results on LCD displays
6. Record or analyze data as needed

## 🔍 Troubleshooting

Common issues and solutions:

- **No Display Output**: Check power connections and LCD interface cables
- **Incorrect Counts**: Verify input signal timing and connections
- **System Reset**: Use the manual reset switch if counting errors occur
- **Display Flickering**: Check power supply stability
- **Circuit Simulation Issues**: 
  - Ensure LogicWorks is properly installed
  - Check for any missing component libraries
  - Verify all connections in the simulation

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👥 Contributors

- [Husnain Ali](https://github.com/M-Husnain-Ali) - *Project Lead*

## 📞 Contact

For support or inquiries:
- Email: m.husnainali.work@gmail.com
- GitHub: [@M-Husnain-Ali](https://github.com/M-Husnain-Ali)

## 🌟 Acknowledgments

- Thanks to all contributors who have helped with testing and improvements
- Special thanks to the mechanical equipment development team
- LogicWorks team for providing the circuit simulation platform

---
*Last Updated: March 2024*
