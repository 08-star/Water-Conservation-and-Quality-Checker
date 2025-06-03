# Water Conservation and Quality Checker

A comprehensive Java Swing application for monitoring water usage, checking water quality parameters, and providing conservation tips to promote sustainable water management.

## Features

### 🚰 Water Usage Calculator
- Calculate daily water consumption based on household activities
- Track usage from showers, toilet flushes, laundry, dishwashing, and outdoor activities
- Get personalized feedback on conservation efforts
- Automatic categorization of usage levels (low, moderate, high)

### 🧪 Water Quality Checker
- Test water quality parameters including pH, turbidity, TDS, and chlorine levels
- Compare results against EPA and WHO standards
- Get detailed analysis and recommendations for each parameter
- Identify potential health and infrastructure concerns

### 💡 Conservation Tips
- Access practical water-saving strategies
- Learn about efficient fixtures and appliances
- Discover landscaping and outdoor water conservation methods
- Get actionable advice for reducing daily water consumption

## Screenshots

The application features a clean, tabbed interface with three main sections:
- **Water Usage**: Input daily activities and get consumption analysis
- **Water Quality**: Enter test results and receive quality assessment
- **Conservation Tips**: Browse water-saving recommendations

## Requirements

- Java 8 or higher
- No external dependencies required (uses built-in Swing library)

## Installation & Usage

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/water-quality-checker.git
   cd water-quality-checker
   ```

2. **Compile the program:**
   ```bash
   javac WaterQualityChecker.java
   ```

3. **Run the application:**
   ```bash
   java WaterQualityChecker
   ```

## How to Use

### Water Usage Calculator
1. Enter your daily water usage activities:
   - Shower time (minutes)
   - Number of toilet flushes
   - Laundry loads
   - Dishwashing time (minutes)
   - Outdoor water use (gallons)
2. Click "Calculate Water Usage" to see your total consumption
3. Review the feedback message for conservation guidance

### Water Quality Checker
1. Enter your water test results:
   - **pH Level**: 0-14 scale (ideal: 6.5-8.5)
   - **Turbidity**: Measured in NTU (should be <5)
   - **TDS**: Total Dissolved Solids in mg/L (should be <500)
   - **Chlorine**: Chlorine content in mg/L (ideal: 0.2-4)
2. Click "Check Water Quality" to analyze your results
3. Review detailed feedback for each parameter

## Water Quality Standards

The application uses the following standards for water quality assessment:

| Parameter | Acceptable Range | Concerns |
|-----------|------------------|----------|
| pH | 6.5 - 8.5 | <6.5: Corrosive; >8.5: Scaling |
| Turbidity | <5 NTU | >5: May contain harmful particles |
| TDS | <500 mg/L | >500: Poor taste, excess minerals |
| Chlorine | 0.2 - 4 mg/L | <0.2: Insufficient disinfection; >4: Health risks |

## Water Usage Calculations

The calculator uses these average consumption rates:
- **Shower**: 2.1 gallons per minute
- **Toilet**: 1.6 gallons per flush
- **Laundry**: 25 gallons per load
- **Dishwashing**: 1 gallon per minute (hand washing)
- **Outdoor**: User-specified amount

## Contributing

Contributions are welcome! Here are some ways you can help:

1. **Bug Reports**: Submit issues with detailed descriptions
2. **Feature Requests**: Suggest new functionality or improvements
3. **Code Contributions**: 
   - Fork the repository
   - Create a feature branch
   - Submit a pull request with clear descriptions

### Potential Enhancements
- Add data persistence to track usage over time
- Include graphical charts for usage trends
- Add more water quality parameters
- Implement water cost calculations
- Create export functionality for reports

## Technical Details

- **Language**: Java
- **GUI Framework**: Swing
- **Architecture**: Single-class application with modular panel design
- **Layout**: GridBagLayout for precise component positioning
- **Error Handling**: Input validation with user-friendly error messages

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Water usage rates based on EPA WaterSense standards
- Water quality parameters aligned with WHO and EPA guidelines
- Conservation tips compiled from leading environmental organizations

## Support

For questions, suggestions, or issues:
- Open an issue on GitHub
- Contact:adtuvedant17@gmail.com

---

**Help conserve water and protect our environment! 🌍💧**
