# Band Gap Prediction of Inorganic Semiconductors


## Overview

The Band Gap Prediction project aims to predict the band gap of various materials using machine learning techniques. The band gap is a crucial property that determines whether a material is an insulator, semiconductor, or conductor. This prediction can be valuable in material science, electronics, and renewable energy research.


## Background

The electronic band gap is the energy difference between the highest occupied energy state *"valence band"* and the lowest unoccupied energy state *"conduction band"* in a material. It plays a fundamental role in the electrical and optical properties of materials. This project aims to build a predictive model to estimate the band gap based on material characteristics.

## Dataset

The Dataset has been retrieved with the help of `matminer` huge repository.  `expt_gap` Experimental band gap of 6354 inorganic semiconductors.

the Paper and the dataset used: 
> [Refrence](https://pubs.acs.org/doi/suppl/10.1021/acs.jpclett.8b00124)  
> [Dataset `json.gz` format](https://ndownloader.figshare.com/files/13464434)

## Installation
To set up the project environment, follow these steps: 
1. Clone the repository:
    
   ```
   git clone https://github.com/achraf110/Band_gap_prediction.git
   cd Band_gap_prediction
   ```
2. [Install miniconda](https://docs.conda.io/en/latest/miniconda.html)

2. Create a virtual environment **(optional but recommended)**:

     ```
     conda create -n myenv py3
     conda activate py3
     ```
4. Install the required dependencies :

   ```
   pip install -r requirement.txt
   ```

## Feature Engineering with Matminer 

With the help of `.featurizers` package from `Matminer` library, we exacted a wide range of features to properly describe our list of Inorganic Semiconductors. Refer to the code to see more. 

## Model Training and Analysis

We employ two machine learning algorithms for band gap prediction:

1. **Linear Regression:** We utilize linear regression to establish a baseline for band gap prediction and to understand the general trend between features and band gaps. We will visualize the results and evaluate the model's performance.

2. **Random Forest Regression:** The random forest algorithm provides a more sophisticated and robust approach for predicting band gaps. We investigate the feature importance provided by the random forest model to identify the most influential features affecting the predictions.

## Results and Visualization

We present the results of our band gap predictions in an [interactive manner](https://achraf110.github.io/Band_gap_pred_index_html/). The visualizations will showcase the relationship between material features and band gaps, emphasizing the most significant features discovered through feature importance analysis.



https://github.com/achraf110/Band_gap_prediction/assets/59840474/15210079-f297-4d1f-9c5a-cc6234c841cc


## Contributing

We welcome contributions from the community. If you are interested in contributing to this project, please follow the guidelines outlined in the CONTRIBUTING.md file.

## License

GNU General Public License v3.0

## Changelog

* work in progress ... 

## Acknowledgments

We extend our gratitude to the Matminer and Magpie developers for their invaluable contributions to the materials informatics community. We also acknowledge the datasets used in this project and the research papers that inspired our work.

## Contact

For any questions, feedback, or collaboration opportunities, feel free to send me an email. 

**achraf.chahbi-etu@etu.univh2c.ma**

**Chahbi Achraf**.
