# Multi-Branch-Facial-Recognition

This project evaluates the predictive power of individual facial components versus full-face recognition using a multi-branch ResNet-18 architecture.

## Folder Structure
Ensure your local environment is set up as follows:
- `CFD/` : Place your raw CFD image dataset here.
- `processed_cfd_components/` : Generated via the extraction pipeline.
- `MultiBranch_ResNet_Training.ipynb` : Main training and evaluation notebook.

## Setup Instructions
1. Clone this repository.
2. Place your raw CFD dataset into a folder named `CFD/` in the root directory.
3. Run the extraction pipeline in the notebook to generate the `processed_cfd_components` folder.
4. Run the training cells to evaluate the ResNet-18 branches.

## Requirements
- PyTorch
- MediaPipe
- OpenCV
- NumPy/Pandas
