# Machine Learning Project

This repository contains a machine learning project divided into three parts, each focusing on a different topic: Quadratic Discriminant Analysis (QDA), Large Language Models (LLM), and Regression.

## Table of Contents
- [Overview](#overview)
- [Installation](#installation)
- [Usage](#usage)
- [File Structure](#file-structure)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Overview

This project explores three core machine learning techniques:
1. **Quadratic Discriminant Analysis (QDA)** - A classification technique used to separate classes based on quadratic decision boundaries.
2. **Large Language Models (LLM)** - Implementation and exploration of language models for text-based tasks.
3. **Regression Analysis** - Building and evaluating regression models for predictive analytics.

A final report summarizing the findings and methodologies is available in `ML_final.pdf`.

## Installation

To run this project, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/your-repository-name.git
   cd your-repository-name
   ```

2. **(Optional) Create a virtual environment:**
   ```bash
   python3 -m venv env
   source env/bin/activate   # On Windows use: env\Scripts\activate
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

## Usage

To explore the different machine learning techniques, open and run the respective Jupyter Notebooks:

```bash
jupyter notebook
```

Then navigate to one of the following notebooks:
- `Part1 QDA/Part1_QDA.ipynb`
- `Part2 LLM/Part2_LLM.ipynb`
- `Part3 Regression/Part3_Regression.ipynb`

## File Structure

```
├── ML_final.pdf                      # Summary report
├── Part1 QDA/
│   └── Part1_QDA.ipynb               # Notebook for QDA analysis
│   └── TestData.pkl                  # Test Data for the classifier
│   └── TrainData.pkl                 # Train Data for the classifier
├── Part2 LLM/
│   └── Part2_LLM.ipynb               # Notebook for LLM analysis
│   └── TextExamples.csv              # Sentences and their sentiment (positive/negative)
│   └── TextPretrainedEmbeddings.csv  # Pretrained weights for the sentences in TextExamples.csv
│   └── TextFinetunedEmbeddings.csv   # Finetuned weights for the sentences in TextExamples.csv
├── Part3 Regression/
│   └── Part3_Regression.ipynb        # Notebook for Regression analysis
│   └── recorded times.csv            # Collected past trips data for training
│   └── Test.csv                      # Test trips cases for the regression classifier
└── README.md                         # Project documentation
```

## Dependencies

This project requires Python 3.x and the following libraries:
- numpy
- pandas
- scikit-learn
- matplotlib
- seaborn
- jupyter

A complete list of dependencies will be included in a `requirements.txt` file.

## Contributing

Contributions are welcome! If you have suggestions or improvements, please:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes.
4. Open a pull request describing your modifications.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.

## Acknowledgements

Special thanks to the open-source community and the developers of the libraries used in this project.

