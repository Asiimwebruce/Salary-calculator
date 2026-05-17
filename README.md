# Salary Calculator

<div align="center">
  <h2>💰 Track Your Salary with Ease</h2>
  <p>A simple and powerful tool to calculate your monthly salary based on working days, leaves, and overtime.</p>
</div>

## 📋 Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [How to Use](#how-to-use)
- [Salary Calculation](#salary-calculation)
- [Contributing](#contributing)
- [License](#license)

## ✨ Features

- **Easy-to-Use Interface**: Simple form-based salary calculation
- **Comprehensive Calculation**: Accounts for multiple leave types and overtime
- **Input Validation**: Validates all inputs and provides helpful error messages
- **Real-time Results**: Instant salary breakdown with detailed components
- **Responsive Design**: Works seamlessly on desktop and mobile devices
- **Auto-dismissing Alerts**: User-friendly notifications that auto-clear

## 🛠️ Tech Stack

| Technology | Percentage |
|-----------|-----------|
| HTML | 100% |

Pure HTML, CSS, and JavaScript - no dependencies needed!

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- No installation required!

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Asiimwebruce/Salary-calculator.git
   cd Salary-calculator
   ```

2. Open `index.html` in your browser:
   ```bash
   open index.html
   ```

Or simply visit the live version (if deployed).

## 📖 How to Use

1. **Enter Total Salary**: Input your monthly base salary in UGX
2. **Working Days**: Enter total working days in the month
3. **Days Worked**: Enter actual days you worked
4. **Allowances**: Add week offs, paid leave, and casual leave
5. **Deductions**: Enter no-pay leave and late minutes
6. **Overtime**: Add any double-pay/overtime days
7. **Calculate**: Click the "Calculate Salary" button
8. **View Results**: See your final salary and detailed breakdown

## 🧮 Salary Calculation

The calculator computes your salary as follows:

```
Final Salary = (Days Worked × Daily Salary)
             + Week Off Pay
             + Paid Leave Pay
             + Casual Leave Pay
             + Double Pay (Overtime)
             - No Pay Deduction
             - Late Minutes Deduction
```

### Components Explained

| Component | Description |
|-----------|-------------|
| **Daily Salary** | Total Salary ÷ Total Working Days |
| **Week Off Pay** | Paid for scheduled days off |
| **Paid Leave Pay** | Paid for approved leave days |
| **Casual Leave Pay** | Paid for casual leave days |
| **Double Pay** | Extra payment for overtime days |
| **No Pay Deduction** | Days without payment |
| **Late Deduction** | Deduction based on minutes late |

## ⚠️ Input Validation

The calculator validates:
- All fields contain positive numbers
- Worked days don't exceed total working days
- Total days (worked + leave) don't exceed total working days
- Provides helpful error messages for invalid inputs

## 🎨 Features

- ✅ Color-coded results (green for additions, red for deductions)
- ✅ Number formatting with commas for readability
- ✅ Helpful descriptions under each field
- ✅ Reset button to clear all entries
- ✅ Enter key support for quick calculation
- ✅ Mobile-responsive design
- ✅ Accessibility-friendly interface

## 🤝 Contributing

Contributions are welcome! Please feel free to:
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is open source and available under the MIT License.

## 💡 Tips

- Save the HTML file locally for offline use
- Works on all modern browsers
- Keep accurate records of your working days and leaves
- Use this calculator to verify your salary payments

---

**Made with ❤️ by Asiimwe Bruce**
