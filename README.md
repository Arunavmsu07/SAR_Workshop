# SAR Workshop: Processing Sentinel-1 Data in Google Colab

[<image-card alt="Open in Colab" src="https://colab.research.google.com/assets/colab-badge.svg" ></image-card>](https://colab.research.google.com/github/YOUR_USERNAME/SAR_Workshop/blob/main/workshop_final_version.ipynb)

## Overview
This repository contains materials for a hands-on workshop on processing Synthetic Aperture Radar (SAR) data from Sentinel-1 satellites. The main notebook (`workshop_final_version.ipynb`) covers data acquisition, mosaicing, agricultural masking, visualization, and time series analysis for regions like Morocco.

Key topics:
- Fetching Sentinel-1 RTC data via NASA Earthdata.
- Resampling, mosaicing, and computing Radar Vegetation Index (RVI).
- Interactive mapping with geemap for ROI selection.
- Time series extraction and plotting with Plotly.

This is designed for researchers, students, or practitioners interested in remote sensing and Earth observation.

## Prerequisites
- A Google account (for Colab).
- Google Earth Engine account: Sign up at [signup.earthengine.google.com](https://signup.earthengine.google.com) (approval may take 1-2 days).
- NASA Earthdata account: Register at [urs.earthdata.nasa.gov](https://urs.earthdata.nasa.gov) for Sentinel-1 access.
- Basic Python knowledge (the notebook handles most setup).

## Setup and Usage
1. Click the "Open in Colab" badge above to load the notebook in Google Colab.
2. Run the first cell to install dependencies (e.g., `!pip install geemap earthengine-api rasterio earthaccess plotly tqdm`).
3. Authenticate with Earth Engine and Earthdata when prompted (follow the links/instructions in the output).
4. Draw regions/points on the interactive maps as guided.
5. Input date ranges and run cells sequentially.
6. For local runs: Clone this repo and open in Jupyter Notebook.

**Note:** Colab has limits (e.g., 12GB RAM, session timeouts). Save outputs to Google Drive if needed.

## Repository Structure
- `workshop_final_version.ipynb`: Main workshop notebook.
- `data/`: (Optional) Folder for sample data or exports.
- `LICENSE`: MIT License details.

## Contributing
Feel free to fork this repo and submit pull requests for improvements. Report issues via GitHub Issues.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- Built with tools like Google Earth Engine, earthaccess, and geemap.
- Inspired by open-source remote sensing workflows.

For questions, contact [nandaaru@msu.edu].
