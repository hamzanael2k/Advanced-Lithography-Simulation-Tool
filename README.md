# Advanced Lithography Simulation Tool

## Overview

This repository contains a comprehensive lithography simulation tool implemented in Python using Streamlit. The tool provides an interactive interface for simulating various aspects of the lithography process, including aerial image formation, resist processes, and 3D resist profile visualization. It's designed for process engineers, researchers, and students working in semiconductor manufacturing and photolithography.

## Features

- Aerial image calculation with customizable parameters (wavelength, NA, sigma, etc.)
- Resist process simulation including:
  - Chemical amplification
  - Acid diffusion
  - Dill's model for resist bleaching
  - Standing wave effects
- 3D resist profile visualization
- Process window analysis
- Parameter optimization
- Sensitivity analysis
- Support for various mask types (Line-Space Grating, Contact Hole Array, Custom Patterns)
- File import capabilities (GDSII, SVG, NumPy arrays)

## Installation

1. Clone this repository:
   ```
   git clone https://github.com/yourusername/lithography-simulation.git
   cd lithography-simulation
   ```

2. Create a virtual environment (optional but recommended):
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

## Usage

To run the simulation tool:

```
streamlit run lithography_simulation.py
```

This will start a local Streamlit server and open the application in your default web browser.

## Dependencies

- streamlit
- numpy
- scipy
- matplotlib
- plotly
- numba
- gdsii (for GDSII file handling)
- svgwrite (for SVG file handling)

For a complete list of dependencies with version numbers, see `requirements.txt`.

## Contributing

Contributions to this project are welcome! Please follow these steps:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- This tool was inspired by the need for accessible and comprehensive lithography simulation in semiconductor manufacturing.
- Special thanks to the open-source community for providing the libraries and tools that made this project possible.


## Disclaimer

This simulation tool is provided for educational and research purposes only. While efforts have been made to ensure accuracy, the results should not be used as the sole basis for real-world manufacturing decisions without proper validation.
