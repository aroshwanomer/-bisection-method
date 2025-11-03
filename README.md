# Bisection Method Implementation

This repository contains a complete implementation of the **Bisection Method** for finding roots of equations, including both Python code and Google Sheets solutions.

## 📋 Project Overview

The Bisection Method is a root-finding algorithm that applies to any continuous function for which one knows two values with opposite signs. The method consists of repeatedly bisecting the interval defined by these values and then selecting the subinterval in which the function changes sign, and therefore must contain a root.

## 🎯 Equation Solved
**f(x) = x³ - 2x - 5 = 0**

## 📊 Results
- **Root Found**: x ≈ 2.09455148
- **Iterations**: 21
- **Final Error**: < 1e-6
- **Initial Interval**: [2, 3]
- **Convergence**: Achieved within tolerance

## 📁 Repository Contents

### 1. Python Implementation (`bisection_method.py`)
- Complete bisection method algorithm with visualization
- Real-time iteration tracking and convergence analysis
- Matplotlib plots showing:
  - Function graph with root location
  - Error convergence (log scale)
- Professional code structure with documentation

### 2. Google Sheets Solution
- Interactive spreadsheet demonstrating manual calculations
- Step-by-step iteration tracking
- Formulas for automated bisection process
- Visual convergence monitoring

### 3. Documentation
- `README.md` - This comprehensive guide
- `requirements.txt` - Python dependencies

## 🚀 Quick Start

### Python Implementation
```bash
# Clone the repository
git clone https://github.com/aroshwanomer/bisection-method.git

# Navigate to the directory
cd bisection-method

# Install dependencies
pip install -r requirements.txt

# Run the bisection method
python bisection_method.py
