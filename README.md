# Medical Image Segmentation

This project provides a brief introduction to the approach of Image Segmentation using U-Net. It showcases the implementation of image segmentation techniques on medical images, specifically focusing on the segmentation of pelvic bones from 2D X-ray images.

## Documentation

Included in the repository is a comprehensive PDF document titled `Project-Report.pdf`. This document contains detailed descriptions of the problem analysis, the rationale behind the choice of transformer functions and the U-Net model for image segmentation, hyperparameter tuning, and a thorough discussion of the results. It serves as a complete guide to understanding the methodologies and outcomes of this project.

## Code Files

The project consists of three Jupyter Notebook files, each playing a critical role in the segmentation process:

- `1._134.ipynb`: This notebook focuses on the segmentation of the bone 134. It contains all the necessary code and explanations for preprocessing, model training, and the segmentation process specific to this bone structure.

- `1._256-74.ipynb`: Similar to the previous notebook, this one is dedicated to the segmentation of the bone 256. It follows the same structure but is tailored to the characteristics and requirements of segmenting the bone 256.

- `1._combination.ipynb`: This notebook combines the outputs of the previous two notebooks to produce the final segmentation results. It demonstrates how to integrate the segmented images from both bone 134 and bone 256 to achieve comprehensive segmentation outputs.

## Note

Please note that some outputs in the notebooks are exceptionally long due to extensive epochs during model training. There have been instances of keyboard interruptions in two cells due to the prolonged execution time. Despite these interruptions, the models were successfully created, utilized, and analyzed. Detailed explanations and justifications of the code and its functionalities are provided within each notebook.

## Getting Started

To get started with this project:

1. Download the provided notebooks and the PDF document.
2. Ensure you have Jupyter Notebook or JupyterLab installed to run the `.ipynb` files.
3. Read the `Segmentation of Pelvic Bone for 2d X.pdf` document for a detailed understanding of the project scope, methodology, and results.
4. Execute the notebooks in the order mentioned to replicate the segmentation process and results.
