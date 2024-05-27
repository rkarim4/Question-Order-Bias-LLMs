# Investigating Question Order Bias in Large Language Models

This repository contains all the necessary code and the final report for the research project on "Investigating Question Order Bias in Large Language Models." This project was undertaken as a part of the coursework for the CS 516: Responsible data science and algorithmic fairness at the University of Illinois, Chicago. The project explores how the sequencing of questions can influence the responses of large language models, akin to known cognitive biases in human behavior.

## Project Overview

Question order bias is a well-documented issue in survey methodology where the order of questions influences the responses. This project extends this concept to the domain of large language models (LLMs) like Claude-3 Haiku and Llama2-13b-chat, assessing whether LLMs exhibit similar biases and how these biases could potentially affect their application in real-world scenarios.

## Repository Structure

- `QuestionOrderBias.ipynb`: This notebook contains all the Python scripts used for generating the synthetic dataset, executing the model, and performing statistical analysis.
- `Data/`: Includes complete dataset generated synthetically and used in the project.
- `Results/`: Contains the results for the experiments for the two models assessed, Claude-3 Haiku and Llama2-13b-chat.
- `Reports/`: Contains the final project report and additional documentation.
- `README.md`: Provides an overview of the project, repository structure, and setup instructions.

## Key Features
- **Interactive Notebook**: The Jupyter Notebook includes all code, from data generation and model evaluation to statistical analysis, in an interactive format.
- **Built-in Dependencies**: All required libraries are installed directly within the notebook, ensuring all dependencies are correctly managed.
- **Comprehensive Analysis**: Includes detailed statistical analysis and model evaluation to assess question order bias in LLMs.

## Key Features Of the Research Project
- **Synthetic Dataset Generation**: Scripts for creating synthetic data that simulates real-world survey scenarios to test LLM responses.
- **Statistical Analysis**: Implementation of chi-square tests to measure the impact of question order on the probability of biased responses.
- **Model Evaluation**: Code for running the models and analyzing their output under different test conditions.


## Getting Started

To run this project, you will need Python 3.11 or later. Follow these steps to set up the project environment:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/Question-Order-Bias-in-LLMs.git
   cd Question-Order-Bias-in-LLMs
2. **Download the llama2-13b-chat model:**
Please download the llama-2-13b-chat.Q4_K_M.gguf model (https://huggingface.co/TheBloke/Llama-2-13B-GGUF/blob/main/llama-2-13b.Q4_K_M.gguf) to your system and save it within the Question-Order-Bias-in-LLMs directory within the 'Models/' subdirectory.
3. **Launch and run the jupyter notebook**


## Dataset
The questions used in the study can be found here: https://github.com/rkarim4/Question-Order-Bias-LLMs/blob/main/Data/dataset.xlsx 
Original questions were acquired from the BiasMonkey dataset (https://github.com/lindiatjuatja/BiasMonkey)


## Contributing
If you're interested in contributing to this project, please fork the repository and submit a pull request with your suggested changes.

## Contact
For questions or further discussions about the project, please contact rkarim4@uic.edu.

## Citation
If this project informs your research or you find it helpful in any way, please consider citing it in your works.

