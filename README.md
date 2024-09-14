# ManningsRF
The Random Forest (RF) Model for large-scale predicition of channel roughness coefficient (Manning's n) over the continental US. This release includes sample codes and datasets akin to those utilized in generating content showcased within the referenced paper. 

![Python Version](https://img.shields.io/badge/python-3.7%20|%203.8%20|%203.9-blue)
![MIT License](https://img.shields.io/badge/license-MIT-green)
![Build Status](https://img.shields.io/github/actions/workflow/status/username/ManningsRF/ci.yml)
![Coverage](https://img.shields.io/codecov/c/github/username/ManningsRF)

# Paper
Al Mehedi, Md Abdullah, et al. "Spatiotemporal variability of channel roughness and its substantial impacts on flood modeling errors." Earth's Future 12.7 (2024): e2023EF004257.

### Overview
This repository implements a Random Forest (RF) model for large-scale prediction of Manning's roughness coefficient (Manning's n) across the continental U.S. The project is part of a broader effort to improve flood modeling accuracy using data-driven methods.

### Features:
- Predict channel roughness (Manning's n) using RF with multiple hydrological features.
- Process large-scale geospatial datasets.
- Easy-to-use interface for model training and predictions.

### Installation:
```bash
git clone https://github.com/username/ManningsRF.git
cd ManningsRF
pip install -r requirements.txt
```

### Usage

- To train the model and predict Manning's n:

```bash
python model/Mannings_RF_model.py --data data/Mannings_data.csv
```

### Example Output:

- After running the model, you can expect visualizations or output files that show predicted Manning's n vs. actual values.
  
![Sample Prediction Output](path_to_output_image.png)

### Contributing:

Contributions are welcome! Please feel free to submit issues or pull requests for any improvements, bug fixes, or new features.

### License:

This project is licensed under the MIT License. See the LICENSE file for details.

