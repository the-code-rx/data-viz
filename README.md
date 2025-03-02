# Readme

This Quarto project is for the University of Colorado Boulder Data Visualization course.

## Installation Instructions

1. Install Quarto
   - Visit [Quarto's official download page](https://quarto.org/docs/get-started/)
   - Download and install the version appropriate for your operating system
   - Verify installation by running `quarto --version` in your terminal

2. Set up Python Environment (Python 3.12+ required)
   ```bash
   # Create and activate a virtual environment
   python -m venv venv
   source venv/bin/activate 
   
   # Install dependencies using uv
   uv venv
   uv pip install .
   ```

3. Run the Project
   ```bash
   # Render the project
   quarto render
   
   # Preview the project (starts local server)
   quarto preview
   ```

## Project Structure

- `index.qmd`: Main dashboard file containing the heart disease analysis
- `heart_disease.csv`: Dataset used for analysis
- `styles.css`: Custom styling for the dashboard

## Dependencies

This project requires Python 3.12 or higher and the following main packages:
- Altair 5.5.0+
- NumPy 2.2.3+
- Pandas 2.2.3+
- SciPy 1.15.2+

For a complete list of dependencies, see `pyproject.toml`.