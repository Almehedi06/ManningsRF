# ManningsRF
The Random Forest (RF) Model for large-scale predicition of channel roughness coefficient (Manning's n) over the continental US. This release includes sample codes and datasets akin to those utilized in generating content showcased within the referenced paper. 

![Python Version](https://img.shields.io/badge/python-3.7%20|%203.8%20|%203.9-blue)
![MIT License](https://img.shields.io/badge/license-MIT-green)
![Build Status](https://img.shields.io/github/actions/workflow/status/username/ManningsRF/ci.yml)
![Coverage](https://img.shields.io/codecov/c/github/username/ManningsRF)
[![Google Scholar](https://img.shields.io/badge/Google-Scholar-blue)](https://scholar.google.com/citations?user=4DR2F4kAAAAJ&hl=en&oi=ao)

---

### Connect with Me:

[![Twitter Badge](https://img.shields.io/badge/Twitter-@AlMehedi06-1DA1F2?style=flat&logo=twitter&logoColor=white)](https://x.com/AlMehedi06)
[![LinkedIn Badge](https://img.shields.io/badge/LinkedIn-Md--Abdullah--Al--Mehedi-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/md-abdullah-al-mehedi/)
[![ResearchGate Badge](https://img.shields.io/badge/ResearchGate-Md--Abdullah--Al--Mehedi-brightgreen?style=flat&logo=researchgate)](https://www.researchgate.net/profile/Md-Abdullah-Al-Mehedi)
[![Personal Website](https://img.shields.io/badge/Website-Abdullah--Al--Mehedi-blue?style=flat&logo=google-chrome)](https://almehedi06.wixsite.com/abdullah-al-mehedi)
[![Google Scholar Badge](https://img.shields.io/badge/Google%20Scholar-Citations-blue?style=flat&logo=google-scholar)](https://scholar.google.com/citations?user=4DR2F4kAAAAJ&hl=en)

---

---

# Paper
Al Mehedi, M.A., Saki, S., Patel, K., Shen, C., Cohen, S., Smith, V., Rajib, A., Anagnostou, E., Bindas, T. and Lawson, K., 2024. Spatiotemporal variability of channel roughness and its substantial impacts on flood modeling errors. Earth's Future, 12(7), p.e2023EF004257.

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

