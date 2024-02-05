# Heatstroke Risk Clustering

## Overview

This project utilizes machine learning to identify clusters within a dataset related to heatstroke risk factors. Specifically, it focuses on two main features: heart rate variability mean (`hrv_mean`) and entropy (`hrv_entropy`) to group individuals into clusters. This analysis helps in understanding the variations in heatstroke risk based on physiological data.

## Prerequisites

Before you begin, ensure you have met the following requirements:
- Python 3.6 or higher installed
- Pip for installing Python packages

## Installation

To set up your environment to run this code, follow these steps:

1. Clone the repository or download the source code to your local machine.
2. Install the required Python packages by running the following command in your terminal or command prompt:

```bash
pip install pandas scikit-learn yellowbrick
```

## Usage

To run the clustering analysis, follow these steps:

1. Place your dataset in the root directory or modify the file path in the code to point to your dataset location. The dataset should be a CSV file with at least the following columns: `hrv_mean` and `hrv_entropy`.
2. Run the script using Python:

```bash
python heatstroke_clustering.py
```

The script will perform K-Means clustering analysis and use the KElbowVisualizer to determine the optimal number of clusters based on the elbow method. The visualisation will be displayed, showing the elbow curve to help you identify the best value for `k`.

## Contributing

Contributions to this project are welcome! To contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Commit your changes with clear commit messages.
4. Push your changes to the branch.
5. Submit a pull request.

Please ensure your code adheres to the project's coding standards and includes appropriate tests.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

---

Feel free to customize this template to better suit your project's specific requirements or to add additional sections as needed, such as `Data Description`, `Features and Model Details`, or `Contact Information` for further inquiries.