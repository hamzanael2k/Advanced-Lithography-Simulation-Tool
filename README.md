# Advanced Lithography Simulation Tool

## Overview

This Advanced Lithography Simulation Tool is a Streamlit-based application that provides a comprehensive platform for simulating and analyzing various aspects of the lithography process used in semiconductor manufacturing. It offers a user-friendly interface for exploring the effects of different lithography parameters on the final resist pattern.

## Features

- **Interactive Parameter Adjustment**: Easily modify key lithography parameters such as wavelength, numerical aperture, partial coherence factor, and more.
- **Multiple Mask Types**: Support for line-space gratings, contact hole arrays, and custom patterns.
- **Advanced Resist Modeling**: Incorporates chemical amplification effects and acid diffusion simulation.
- **Shot Noise Simulation**: Models photon shot noise to simulate line-edge roughness (LER) and critical dimension variations.
- **Automatic Parameter Optimization**: Utilizes scipy.optimize to find optimal lithography parameters for desired critical dimensions.
- **Preset Configurations**: Includes preset parameter sets for common lithography processes (e.g., DUV, EUV).
- **Performance Optimization**: Leverages Numba for just-in-time compilation to enhance computational speed.
- **Downloadable Results**: Allows users to save and download simulation results for further analysis.
- **Critical Dimension Measurement**: Provides automated measurement of the simulated critical dimension.

## Installation

1. Clone this repository:
   ```
   git clone https://github.com/your-username/advanced-lithography-simulation.git
   cd advanced-lithography-simulation
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

1. Run the Streamlit app:
   ```
   streamlit run lithography_simulation.py
   ```

2. Open your web browser and navigate to the URL displayed in the terminal (usually `http://localhost:8501`).

3. Use the sidebar to adjust simulation parameters and explore different lithography conditions.

4. Click the "Optimize Parameters" button to find optimal settings for a target critical dimension.

5. Download the simulation results using the "Download Results" button for further analysis or reporting.

## Contributing

Contributions to improve the simulation tool are welcome! Please feel free to submit pull requests or open issues to discuss potential enhancements.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- This tool was inspired by the need for accessible lithography simulation in semiconductor education and research.
- Special thanks to the Streamlit team for providing an excellent framework for building interactive data applications.


