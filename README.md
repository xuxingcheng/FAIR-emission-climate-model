# FAIR-emission-climate-model

This project investigates the effect of different emissions on global temperature change using the FAIR climate model. The goal is to analyze species' forcing contributions, identify unimportant species, and optimize the model for better performance and reduced overfitting.

---

## Features

- **Species Forcing Analysis**: Analyze the contribution of different species to radiative forcing.
- **Optimization**: Identify and eliminate species with minimal impact to enhance model run speed and prevent overfitting.
- **Maximum Forcing Analysis**: Determine the year of maximum forcing and calculate the coefficient of variation for species.
- **Model Extensions**: Evaluate and extend the FAIR model for specific scenarios (e.g., RCIMP and simplified models).
- **Visualization**: Generate graphs comparing original and optimized models.

---

## Directory Structure

### Main Files
- **`Fair Tests.ipynb`**: General tests and experiments with the FAIR model.
- **`Max Forcing Analysis.ipynb`**: Analysis of maximum forcing and species contributions.
- **`ModelEvaluation_Extension.ipynb`**: Evaluation of the extended FAIR model.
- **`ModelEvaluation_RCIMP.ipynb`**: Evaluation of the FAIR model under RCIMP scenarios.
- **`Original Model.ipynb`**: Baseline FAIR model implementation.
- **`Original_Model_Extension.ipynb`**: Extended version of the original FAIR model.
- **`Simplified_Model_Extension.ipynb`**: Simplified FAIR model with extensions.
- **`Simplified_Model_RCIMP.ipynb`**: Simplified FAIR model under RCIMP scenarios.

### Supporting Files
- **`TOP_species_extension.txt`**: Top species identified for the extended model.
- **`TOP_species_rcimp_modified.txt`**: Top species identified for the RCIMP model.

### Examples
- **`examples/`**: Contains example notebooks demonstrating FAIR model usage, including:
  - Basic runs
  - CO2 effect investigations
  - CMIP6 SSP emissions scenarios
  - Data importing and equilibrium analysis

### Data
- **`examples/data/`**: Input data for examples, including emissions, concentrations, and forcing data.
- **`graph_outputs/`**: Graphical outputs comparing original and optimized models.

### Configuration
- **`.idea/`**: IDE configuration files (specific to IntelliJ-based IDEs).
- **`anaconda_projects/`**: Anaconda project-related files.

---

## Requirements

- Python 3.8+
- FAIR climate model library
- Required Python packages:
  - `numpy`
  - `pandas`
  - `matplotlib`
  - `xarray`
  - `cartopy`

---

## Usage

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd FAIRproject
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Jupyter notebooks:
   ```bash
   jupyter notebook
   ```

4. Explore the example notebooks in the `examples/` directory for guidance on using the FAIR model.

---

## Example Workflow

1. **Species Analysis**:
   - Use `Max Forcing Analysis.ipynb` to identify unimportant species based on maximum forcing and coefficient of variation.

2. **Model Evaluation**:
   - Evaluate the original and extended models using `ModelEvaluation_Extension.ipynb` and `ModelEvaluation_RCIMP.ipynb`.

3. **Visualization**:
   - Generate comparison graphs using the outputs in `graph_outputs/`.

4. **Run Examples**:
   - Explore the `examples/` directory for pre-configured FAIR model runs.

---

## References

- FAIR Model Documentation: [https://docs.fairmodel.net/en/latest/examples.html](https://docs.fairmodel.net/en/latest/examples.html)
- FAIR Model GitHub Repository: [https://github.com/OMS-NetZero/FAIR](https://github.com/OMS-NetZero/FAIR)

---

## License

Open source, free to copy and give suggestions