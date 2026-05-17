# Analysis of Surface Water Dynamics in Bhutan (1988-2024)
**Bachelor Thesis Project | Earth System Science**


## Project Context
This study monitors the spatio-temporal dynamics of surface water in the Bhutanese Himalayas over a 36-year period. Utilizing Landsat satellite imagery (5, 7, 8, and 9) and the Modified Normalized Difference Water Index (mNDWI), this project identifies trends in water surface area, focuses on altitudinal distribution, and highlights the acceleration of water body expansion in recent decades.

## Key Findings (Visualized)
![Main Trend Map](outputs/03_theilsen_trend_map.png)
*Note: Run the visualization notebook to generate the latest versions of all figures.*

## Project Structure
- `data/`: 
    - `raw/`: Digital Elevation Model (DEM) and Bhutan boundary shapefiles.
    - `processed/`: Statistical CSVs and intermediate NDWI stacks.
- `notebooks/`: 
    - `01_preprocessing_PRO.ipynb`: Merging rasters, cloud masking, and trend calculation.
    - `02_visualization_PRO.ipynb`: Generating thesis-ready plots and spatial maps.
- `outputs/`: High-resolution figures exported as PNG/PDF.

## Data Note
Due to GitHub's storage limits, raw satellite TIF files (>1GB) are not included in this repository. The provided CSVs in `data/processed/` allow for full reproduction of all visualizations.

## How to Run
1. Create the environment: `conda env create -f environment.yml`
2. Activate environment: `conda activate bhutan-water`
3. Run notebooks in numerical order.