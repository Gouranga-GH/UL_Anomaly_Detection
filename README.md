
# Anomaly Detection Project

This project showcases anomaly detection techniques using multiple machine learning algorithms. It provides a comprehensive comparison of Isolation Forest, DBSCAN, and Local Outlier Factor (LOF) models applied on a custom dataset. The project includes numerical and visual comparisons of these models to detect anomalies in data.

## Project Overview

Anomaly detection is crucial in various fields, such as fraud detection, network security, and predictive maintenance. This project aims to explore multiple algorithms and evaluate their performance using a dataset with non-linearly separable data. The goal is to identify and compare anomalies using both visualizations and performance metrics.

### Algorithms Implemented:
1. **Isolation Forest**: A tree-based algorithm that isolates observations by randomly selecting a feature and then randomly selecting a split value between the minimum and maximum values.
2. **DBSCAN (Density-Based Spatial Clustering of Applications with Noise)**: A clustering algorithm that finds core samples of high density and expands clusters from them.
3. **Local Outlier Factor (LOF)**: A density-based algorithm that identifies outliers by comparing the local density of a point with that of its neighbors.

### Key Features:
- Non-linear separable dataset for anomaly detection.
- Customizable feature names: `Temperature` and `Pressure`.
- Clear visualizations to compare model outputs.
- Numerical comparison metrics for all models.
  
## Getting Started

### Prerequisites
To run the notebook, you will need the libraries installed via the following:
\`\`\`bash
pip install -r requirements.txt
\`\`\`

### Running the Project
1. Clone this repository:
   \`\`\`bash
   git clone https://github.com/Gouranga-GH/UL_Anomaly_Detection_ISD.git
   \`\`\`
2. Navigate to the project directory:
   \`\`\`bash
   cd anomaly-detection
   \`\`\`
3. Open the Jupyter notebook:
   \`\`\`bash
   jupyter notebook anaomaly_detection.ipynb
   \`\`\`
4. Execute the notebook to run the models and view the comparison.

## Results

### Visual Comparisons
The notebook includes various plots that compare the models visually to show how each algorithm identifies anomalies in the dataset. You will see the separation of normal points from anomalies in 2D plots for each model.

### Numerical Comparisons
The project also evaluates models numerically using metrics such as accuracy, precision, recall, and F1-score.

## Conclusion
This project demonstrates the power and flexibility of different anomaly detection algorithms. By visually and numerically comparing their outputs, it helps in understanding the strengths and weaknesses of each approach in detecting anomalies.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
