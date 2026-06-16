# ML-Based Cardiovascular Disease Prediction

## Overview

This project focuses on predicting the likelihood of cardiovascular disease using Machine Learning techniques. It analyzes patient health and clinical data to identify individuals at risk, enabling early diagnosis and preventive healthcare measures.

The project is implemented as a Jupyter Notebook (`.ipynb`) and can be easily opened and executed using Visual Studio Code.

---

## Project Structure

```text
ML-Based-Cardiovascular-Disease-Prediction/
│
├── cardiovascular_disease_prediction.ipynb   # Main notebook
├── dataset.csv                                # Dataset used for training/testing
├── README.md                                  # Project documentation
└── requirements.txt                           # Required Python libraries
```

---

## Prerequisites

Before running the project, ensure you have:

* Python 3.8 or higher
* Visual Studio Code (VS Code)
* Jupyter extension for VS Code

---

## Installation

### 1. Download the Repository

Clone the repository using Git:

```bash
git clone <repository-url>
```

Or download the ZIP file and extract it.

---

### 2. Open the Project in VS Code

1. Launch **Visual Studio Code**.
2. Click **File → Open Folder**.
3. Select the downloaded project folder.
4. Open the notebook file:

```text
cardiovascular_disease_prediction.ipynb
```

5. If prompted, install the **Jupyter** extension in VS Code.

---

### 3. Install Required Libraries

Open the VS Code terminal and run:

```bash
pip install -r requirements.txt
```

If `requirements.txt` is not available, install the libraries manually:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

---

## Running the Notebook

1. Open `cardiovascular_disease_prediction.ipynb`.
2. Select a Python kernel in VS Code.
3. Run the notebook cells sequentially using:

   * **Run All** button, or
   * `Shift + Enter` to execute each cell.

---

## Features

* Data preprocessing and cleaning
* Exploratory Data Analysis (EDA)
* Feature engineering and selection
* Training multiple machine learning models
* Model evaluation and comparison
* Visualization of results and performance metrics

---

## Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## Requirements

The project requires the following Python packages:

```text
pandas
numpy
matplotlib
seaborn
scikit-learn
jupyter
```

You can save these in a `requirements.txt` file and install them using:

```bash
pip install -r requirements.txt
```

---

## Future Enhancements

* Hyperparameter tuning for improved accuracy
* Deployment as a web application
* Integration with real-time healthcare datasets
* Advanced ensemble and deep learning models

---

## License

This project is intended for educational and research purposes.
