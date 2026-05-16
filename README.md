# CGPA Calculator

A production-grade web-based CGPA calculator for comprehensive academic performance tracking and planning.

## Features

### Semester GPA Calculator
Calculate GPA for individual semesters by inputting course names, grades, and credit values. Supports real-time calculations with dynamic course management.

### CGPA Calculator
Calculate cumulative GPA across multiple semesters with weighted credit calculations. Track overall academic performance with precise weighted averaging.

### CGPA Predictor
Project your final CGPA based on current performance and expected semester results. Plan academic strategy with data-driven predictions.

## Grade Scale

| Grade | Points |
|-------|--------|
| S     | 10     |
| A     | 9      |
| B     | 8      |
| C     | 7      |
| D     | 6      |
| E     | 5      |

## Usage

1. Open `index.html` in any modern browser
2. Select a calculator tab from the top navigation
3. Enter your data in the form fields
4. Click the calculate button to see results
5. Use clear button to reset all values

## Technical Specifications

- **Architecture**: Single-file HTML/CSS/JavaScript application
- **Dependencies**: None
- **Browser Support**: Chrome, Firefox, Safari, Edge (latest versions)
- **Responsive Design**: Mobile, tablet, and desktop optimized
- **Performance**: Real-time calculations with no latency

## Calculation Methods

### Semester GPA
```
Semester GPA = (Σ Grade × Credits) / Σ Credits
```

### Cumulative GPA
```
CGPA = (Σ Semester GPA × Credits) / Σ Credits
```

### CGPA Prediction
```
Predicted CGPA = (Current CGPA × Completed Credits + Current Semester GPA × Current Credits) / (Completed Credits + Current Credits)
```

## Features

- Input validation for all fields
- Real-time weighted calculations
- Support for decimal credit values
- Error messaging and validation feedback
- Dark theme with modern gradient UI
- Mobile-first responsive design
- Hardware-accelerated animations
- No external dependencies

## Browser Compatibility

- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

## License

MIT License - Open source and freely available for educational use.
