# ml_dl_gai_2024 Repository

Welcome to the **ml_dl_gai_2024 Projects** repository! This collection contains a variety of data science projects that showcase techniques in machine learning (ML), deep learning (DL), and generative AI (GAI), and more. Each project demonstrates practical solutions to real-world data challenges and provides clear explanations of methodologies used.

## Table of Contents

- [Overview](#overview)
- [Repository Structure](#repository-structure)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Overview

Data Science is a multidisciplinary field that applies statistics, programming, and domain knowledge to extract insights from data. This repository contains several of my data science projects, each focusing on different aspects of the data science workflow, such as data exploration, feature engineering, machine learning, and model evaluation.

The projects in this boot camp are designed to be both educational and practical, offering hands-on solutions and examples that you can adapt for your own work. Covering key areas such as machine learning (ML), deep learning (DL), and generative AI (GAI), these projects are suitable for both beginners and experienced practitioners. They will help you build a deeper understanding of the tools and techniques used in these cutting-edge fields.

## Repository Structure

This repository is organized into several folders to facilitate easy navigation and access to resources:

- **Datasets/**: Contains all datasets used in the projects.
- **Images/**: Stores images, graphs, and visualizations generated or used throughout the projects.
- **week_1/, week_2/, week_3/, etc.**: Each week has its own folder dedicated to different data science projects, covering topics such as machine learning, deep learning, and generative AI. Inside these folders, you will find Jupyter notebooks with detailed comments explaining the methods and approaches used.

The organization is designed to make it easy to explore and adapt the materials to your own projects.

## Getting Started

To get started with any project in this repository:

1. **install this project on your own machine**:
   Start by installing [Anaconda](https://www.anaconda.com/distribution/) (or [Miniconda](https://docs.conda.io/en/latest/miniconda.html)), [git](https://git-scm.com/downloads), and if you have a TensorFlow-compatible GPU, install the [GPU driver](https://www.nvidia.com/Download/index.aspx), as well as the appropriate version of CUDA and cuDNN (see TensorFlow's documentation for more details).

  Next, clone this project by opening a terminal and typing the following commands (do not type the first `$` signs on each line, they just indicate that these are terminal commands):

    $ git clone https://github.com/Somia-Abdelsater/ml_dl_gai_2024.git
    $ cd ml_dl_gai_2024
    
    Next, run the following commands:

    $ conda env create -f environment.yml
    $ conda activate tf2
    $ python -m ipykernel install --user --name=python3

Finally, start Jupyter:

    $ jupyter notebook

If you need further instructions, read the [detailed installation instructions](INSTALL.md).

2. **Install Required Libraries**:
   - Each project may have its own dependencies. Install the required libraries using:
       $ pip install -r requirements.txt

3. **Run the Project**:
   - Open the Jupyter notebook (`.ipynb`) or Python script (`.py`) file and run the code. Follow the instructions and comments in the notebook to execute the analysis or model.

## Usage

Each project folder contains detailed instructions and code with comments to help you understand the process. Here's an example of how to use a machine learning project:

### Example: Machine Learning - Predicting House Prices in week_2

1. Navigate to the `ml_dl_gai_2024/week_2` folder.
2. Open the `housing_end_to_end_project.ipynb` notebook.
3. Follow these steps in the notebook:
   - Load the dataset.
   - Perform exploratory data analysis (EDA).
   - Preprocess the data (e.g., handle missing values, scale features).
   - Train a machine learning model ( Linear Regression).
   - Evaluate the model's performance.

## Contributing


## License


## Contact

For questions, feedback, or suggestions, please reach out:

- [Somia Abdelsater](mailto:SomiaAbdelsater@gmail.com)
- Follow me on GitHub: [Somia-Abdelsater](https://github.com/Somia-Abdelsater)
