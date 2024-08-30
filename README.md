# Instruction Tuning for On-Demand Information Extraction

This repository contains the implementation and experiments related to instruction tuning for on-demand information extraction. The goal is to fine-tune language models to extract specific information from text based on given instructions.

## Table of Contents

- [Overview](#overview)
- [Installation](#installation)
- [Usage](#usage)
- [Experiments](#experiments)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Overview

Instruction tuning used to adapt language models to perform specific tasks based on provided instructions. This project explores its application in the context of on-demand information extraction, where a model is trained to extract relevant data from text according to user-defined criteria.

Key components of the project include:

- **Instruction Tuning**: Fine-tuning pre-trained language models with task-specific instructions.
- **Information Extraction**: Extracting targeted information from text data based on instructions.
- **Evaluation**: Assessing the performance of the tuned models on various extraction tasks.

## Installation

To set up the project locally, follow these steps:

1. Clone the repository:
   '''bash
   git clone https://github.com/dipkimyen/Instruction-Tuning-for-On-Demand-Information-Extraction.git'''
2. Navigate to the project directory:
  '''bash
  cd Instruction-Tuning-for-On-Demand-Information-Extraction'''
3. Install the required Python packages:
   '''bash
   pip install -r requirements.txt'''

## Usage
### Running the Training Script
To train the model with your custom dataset and instructions, run:
'''bash
python train.py --config config.yaml'''

Where config.yaml contains the configuration for the training process, including:
* Model parameters
* Dataset paths
* Training hyperparameters
* Instruction templates
* Inference and Evaluation
After training, you can perform inference using:
'''bash
python infer.py --model_path <path_to_model> --input_file <input_data>'''
This will generate the extracted information based on the provided instructions in the input_file.

## Experiments
The project includes several experiments to test the efficacy of instruction tuning in different scenarios. These experiments involve:
* Different Instruction Types: Testing various forms of instructions to see how they impact model performance.
* Data Variety: Evaluating the model on different types of text data, from structured information to more complex, free-form text.
* Model Comparisons: Comparing the performance of instruction-tuned models against baseline models.

## Results
1. Prediction
   
![image](https://github.com/user-attachments/assets/981783c0-6754-4a2a-9d41-d15d7e71cf79)

2. Label
   
![image](https://github.com/user-attachments/assets/b39819b4-733b-4af9-b7ec-5a271cdaf292)

   
## Contributing
Contributions are welcome! If you have ideas, suggestions, or improvements, please fork the repository and submit a pull request. You can also report issues or bugs by opening an issue in the GitHub repository.

## License
You can customize this content to your project's specific needs. If you have any additional information or requests, let me know!
