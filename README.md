# Data Visualization Using Different Graph Types Project

## Overview

This project, `iris_visualization.ipynb`, focuses on visualizing the Iris dataset using various graph types to analyze differences between species (_Iris-setosa_, _Iris-versicolor_, _Iris-virginica_). It includes visualizations like histograms, scatter plots, box plots, ridgeline plots, line graphs, bar charts, pie charts, and correlation heatmaps, created with Python libraries.

## The project was developed as part of a **Big Data** course by **Group 13**:

- Harshaanjaneyavarma Samanthapudi
- Pranava Sree Pottipati
- Sana Reddy Gaddam
- Vijaya Raghava Ponnganti
- Ravi Chandra PolavarapuRishik Pendurthi.

## Dataset

The Iris dataset (`Iris.csv`) contains 150 samples (50 per species) with four measurements: sepal length, sepal width, petal length, and petal width, in centimeters. The dataset is included in the repository.

## Prerequisites

- Python 3.13.2 (or a compatible version)
- Visual Studio Code (recommended IDE with Jupyter support)
- Git (optional, for cloning the repository)

## Setup Instructions

### Clone the Repository (if applicable):

```bash
git clone https://github.com/your-repo/iris-visualization.git
cd iris-visualization
```

### Install Python:

Download and install Python from [python.org](https://www.python.org/). Verify the installation:

```bash
python --version
```

### Set Up a Virtual Environment:

Create a virtual environment in the project folder:

```bash
python -m venv .venv
```

Activate the virtual environment:

- On Windows:
  ```bash
  .venv\Scripts\activate
  ```
- On macOS/Linux:
  ```bash
  source .venv/bin/activate
  ```

### Install Required Libraries:

Install the necessary Python libraries:

```bash
pip install pandas matplotlib seaborn numpy joypy jupyter
```

Install specific versions for compatibility:

```bash
pip install pandas==2.2.2 matplotlib==3.8.4 seaborn==0.13.2 numpy==1.26.4 joypy==0.2.6
```

### Set Up VS Code:

Open VS Code and install the Python and Jupyter extensions:  
Go to **Extensions** (`Ctrl+Shift+X`), search for "Python" and "Jupyter," and install both by Microsoft.

Open `iris_visualization.ipynb` in VS Code.  
Select the Python interpreter from the virtual environment (bottom-left corner in VS Code, choose `.venv` interpreter).  
If prompted, install additional Jupyter dependencies like `ipykernel`.

## Usage

### Run the Notebook:

Open `iris_visualization.ipynb` in VS Code.  
Run all cells (**Run All** button or `Shift+Enter` for each cell) to generate visualizations. Outputs include:

- Tables (e.g., `group2.head(6)` for sample data)
- Plots saved as images (e.g., `histogram_view.png`, `scatter_sepal.png`)

### Generate HTML Output:

Convert the notebook to HTML for sharing:

```bash
jupyter nbconvert --to html iris_visualization.ipynb
```

This creates `iris_visualization.html` in the project folder, containing all code, explanations, and plots.

### View Results:

- Open the saved images (e.g., `histogram_view.png`) to see the visualizations.
- Open `iris_visualization.html` in a web browser for a complete report.

## Project Structure

- `iris_visualization.ipynb`: The main Jupyter notebook with code and visualizations.
- `Iris.csv`: The Iris dataset file.
- `*.png`: Generated plot images (e.g., `scatter_sepal.png`, `correlation_matrix.png`).
- `iris_visualization.html`: HTML output of the notebook (after conversion).

## Visualizations Included

- **Histograms**: Show the distribution of measurements (e.g., sepal length).
- **Density and Ridgeline Plots**: Compare distributions across species.
- **Line, Bar, and Pie Charts**: Display averages and counts of species.
- **Box and Violin Plots**: Summarize measurement distributions by species.
- **Scatter Plots**: Show relationships between measurements (e.g., sepal length vs. width).
- **Correlation Heatmaps**: Visualize relationships between all measurements.

## Libraries Used

- `pandas`: For data loading and manipulation
- `matplotlib`: For creating and customizing plots
- `seaborn`: For high-level statistical visualizations
- `numpy`: For numerical computations
- `joypy`: For ridgeline plots

## Presentation

A PowerPoint presentation (`Final-Presentation-Group-13.pptx`) with 22 slides summarizes the project findings and visualizations.  
The notebook can be presented by running cells in VS Code while showing the slides, as outlined in the presentation script.

## Project Walkthrough

<img src="Big_Data_Walkthrough.gif" width="100%" height="100%">

## License

This project is licensed under the **MIT License** && **Group13** [2025 Spring]. See the `LICENSE` file for details.

## Contact

For questions or feedback, reach out to **Group 13** at:

- hsamanth@kent.edu
- ppottipa@kent.edu
- sgadda12@kent.edu
- vponnaga@kent.edu
- rpolavar@kent.edu
- rpendurt@kent.edu
