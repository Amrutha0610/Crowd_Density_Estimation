# Crowd Density Estimation using Deep Learning
## Overview
This project applies machine learning-driven analytics to estimate crowd density from images and convert visual data into structured metrics and interpretable insights. Developed during an ML course, the project highlights strong foundations in data preprocessing, regression analysis, model evaluation, and visualization, with a clear focus on real-world analytical use cases.

The outputs: crowd counts, density heatmaps, and performance metrics—illustrate how data analytics solutions can be used to support planning, monitoring, and decision-making across business and operational contexts.

## 🎯 Key Features
### ✔️ Data Preprocessing & Feature Engineering
- Converted raw dot annotations into continuous density maps
- Applied Gaussian smoothing to improve data realism and reduce noise
- Normalized and structured datasets for model training and evaluation

### ✔️ Predictive Modeling & Regression Analysis
- Implemented a CNN-based regression model to predict crowd density
- Estimated total crowd count by aggregating pixel-level predictions
- Designed the workflow to be extensible for models like MCNN, CSRNet, or VGG-based architectures

### ✔️Performance Evaluation & Insights
- Compared predicted vs actual crowd counts
- Tracked loss curves and error trends during training
- Assessed model reliability beyond simple accuracy measures

### ✔️Data Visualization & Reporting
- Heatmap overlays to highlight crowd concentration zones
- Side-by-side comparison of ground truth vs predictions
- Clear visual outputs for non-technical stakeholders

## 🛠️ Technologies Used
- Python 3.x
- TensorFlow / Keras or PyTorch (depending on notebook)
- OpenCV — Image processing
- NumPy, Pandas — Data handling
- Matplotlib / Seaborn — Visualization

## 📂 Project Structure
```bash
Crowd_density_estimation_project.ipynb     # Main notebook
data/
 ├── images/                               # Input crowd images
 ├── annotations/                          # Dot annotation files
 └── density_maps/                         # Generated target maps (optional)
models/                                     # Saved weights/checkpoints
```

## 🚀 How to Run
1. Install dependencies
 ```bash
pip install numpy pandas matplotlib opencv-python tensorflow
```
(or PyTorch if used in the notebook)

2. Open the Notebook
```bash
jupyter notebook Crowd_density_estimation_project.ipynb"
```
3. Run all cells sequentially
The notebook will guide you through:
- Loading data
- Generating density maps
- Training the model
- Visualizing predictions

## 📊 Key Outputs & Visual Insights
- Crowd density heatmaps for spatial analysis
- Predicted vs actual crowd count comparison
- Model performance trends over time
- Visual reports suitable for stakeholder presentations

## 📘 Skills Demonstrated
- Data preprocessing and quality handling
- Regression modeling and evaluation
- Visual analytics and insight communication
- Translating complex ML outputs into business-friendly insights
- Analytical problem-solving using real-world datasets


