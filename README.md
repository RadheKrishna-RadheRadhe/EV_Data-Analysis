## EV_Data-Analysis

**Dataset Link: [Electric Vehicle Population Data](https://catalog.data.gov/dataset/electric-vehicle-population-data)**

This repository contains an Exploratory Data Analysis (EDA) on EV charging data in Washington, D.C.  
You’ll find:

- **`Project.ipynb`** – main Jupyter notebook with data loading, cleaning, analysis & mapping  
- **`Project.pdf`** & **`Presentation_Report.pptx`** – static report and slide deck  
- **Shapefiles** (`WA_County_Boundaries.*`, `WA_State_Boundary.geojson`) for geospatial joins  

---

## 📋 Prerequisites

- **Python 3.8+**  
- **pip** (≥ 19.3) or **Conda**  
- Terminal/command-prompt access  

---

## 🛠️ Setup

### 📥 Download the Shape Files and Dataset csv File

   Dataset Download Link: Dataset Link: [Electric Vehicle Population Data](https://catalog.data.gov/dataset/electric-vehicle-population-data)

   Download the Shapefiles from the Github repository and move them into a folder

   Download the **Project.ipynb** file and move it into the same folder where the shape files and the Dataset iis copied.
   
### 📦 Install Required Libraries (Step-by-Step)

```bash
pip install pandas
pip install numpy
pip install matplotlib
pip install seaborn
pip install plotly
pip install geopandas
pip install shapely
pip install pyproj
pip install pyogrio
pip install scikit-learn
pip install notebook
```

### 📦 Install All Required Libraries (One Line)

You can install everything at once:

```bash
pip install pandas numpy matplotlib seaborn plotly geopandas shapely pyproj pyogrio scikit-learn notebook
```
---

### 🚀 Running the Analysis

1. **Launch Jupyter Notebook**  
   Once you've installed the libraries, launch Jupyter Notebook by running this command in the terminal:

   ```bash
   jupyter notebook
   ```

### Open the Notebook
Your default web browser will open, showing the Jupyter Notebook dashboard. Find and open the `Project.ipynb` file.

### Run the Cells
Inside the Jupyter Notebook, run all cells to execute the analysis.

### Export the Report
If you'd like, you can export the notebook as a PDF or HTML by going to **File → Download as**.

### Additional Resources
For more information on electric vehicles, you can explore the [Electric Vehicle Population Data](https://catalog.data.gov/dataset/electric-vehicle-population-data) from the U.S. Government's data catalog.

