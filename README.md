# <img src="https://github.com/lglandon1/Power-Tech-Tool/blob/main/Light%20Icon%20No%20Background.png" alt="Tool Icon" width="30" height="30"> Power Tech Tool

A comprehensive web-based utility designed for electrical and mechanical engineers working with international power standards. This tool provides essential calculations and conversions between Kuwait and US units, making it an indispensable resource for professionals in the power engineering field.

## 📱 Live Demo

**[Try Power Tech Tool Now](https://lglandon1.github.io/Power-Tech-Tool/)**

![Power Tech Tool Demo](https://github.com/lglandon1/Power-Tech-Tool/blob/main/Screenshot%202025-03-31%201.png)

## 🔧 Features & Capabilities

Power Tech Tool combines multiple engineering calculators in one convenient interface:

### Electrical Calculations
- **Single Phase Power**: Calculate power from voltage, current, and power factor
- **Three Phase Power**: Calculate three-phase power with support for imbalanced loads
- **kVA to kW Conversion**: Convert between apparent and real power with adjustable power factor
- **Voltage Drop**: Calculate voltage drop based on conductor properties, supporting both mm² and AWG sizes
- **Power Factor Correction**: Determine new power factor after capacitor installation

### Mechanical Calculations
- **Fuel Consumption**: Estimate generator fuel consumption based on power output

### Unit Conversions
- **Liters to Gallons**: Convert volumes with support for tank level monitoring
- **Celsius to Fahrenheit**: Convert between temperature scales

## 💡 How to Use

1. Select a calculation type from the main menu
2. Enter your values in the form fields
3. Press Enter or click "Calculate"
4. View your results instantly with color-coded performance indicators

### Example: Three Phase Power Calculation

```
Voltage: 416V
Current (Phase 1): 25A
Current (Phase 2): 27A
Current (Phase 3): 23A
Power Factor: 0.85
→ Result: 16.2 kW with load percentage visualization
```

## ⚙️ Default Settings

| Parameter | Default Value | Standard |
|-----------|---------------|----------|
| Voltage | 416V | Kuwait Electrical Standard |
| Power Factor | 0.85 | Typical industrial value |
| Efficiency | 0.3 | Standard for fuel consumption |

## 📊 Common Conversion Factors

- **Length**: 1 meter = 3.28 feet
- **Volume**: 1 liter = 0.264 US gallons
- **Power**: 1 kW = 1.34 horsepower
- **AWG to mm²**: Accurate conversion table built-in

## 💻 Technical Specifications

- **Platform**: Web (HTML5, CSS3, JavaScript)
- **Dependencies**: None (runs entirely in browser)
- **Storage**: Uses localStorage for theme preference
- **Compatibility**: All modern browsers (Chrome, Firefox, Safari, Edge)
- **Mobile Support**: Fully responsive design for all screen sizes
- **Theme Options**: Light and dark modes with system preference detection

## 🚀 Installation

### Option 1: Use Online Version
Visit [https://lglandon1.github.io/Power-Tech-Tool/](https://lglandon1.github.io/Power-Tech-Tool/)

### Option 2: Run Locally
```bash
# Clone the repository
git clone https://github.com/lglandon1/Power-Tech-Tool.git

# Navigate to directory
cd Power-Tech-Tool

# Open in your browser
open index.html    # macOS
xdg-open index.html  # Linux
start index.html   # Windows
```

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 📧 Contact & Support

If you encounter any issues or have suggestions for improvement:

- [Open an issue](https://github.com/lglandon1/Power-Tech-Tool/issues) on GitHub
- Contribute to the project via pull requests

---

<p align="center">
  <i>Developed for engineers and technicians working across international power standards</i>
</p>