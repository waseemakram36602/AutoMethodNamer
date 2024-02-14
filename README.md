# AutoMethodNamer
AutoMethodNamer: A tool leveraging LLMs to auto-suggest descriptive method names from functional descriptions. It uses a multistage training approach to bridge semantic gaps, enhancing code quality
Datasets
This repository includes two key datasets:

Dataset 1: Method Names with English Functional Descriptions.
Dataset 2: Method Names with Chinese Functional Descriptions.
Each dataset is crucial for training and evaluating the models to ensure they perform effectively across linguistic boundaries.

Corpus of Prompts
A curated corpus of prompts is provided to optimize ChatGPT's performance in generating accurate method names from functional descriptions. These prompts are tailored to encourage precise and contextually relevant outputs from the model.

Source Code
Baseline Model
Source code for the baseline model (BiLSTM with attention and copying mechanism) applied to both Dataset 1 and Dataset 2 is available, serving as a comparative benchmark for the BERT-CMNF model's performance.

BERT-CMNF Model
The BERT-CMNF model source code is the centerpiece of this repository, showcasing the application of BERT for semantic analysis and fine-tuning ChatGPT to improve its method naming capabilities. This model represents a significant advancement in the field of automated method naming.

Getting Started
To get started with LLM-MethodNamer:

Clone the repository: git clone https://github.com/yourusername/LLM-MethodNamer.git
Install the required dependencies: pip install -r requirements.txt
Follow the instructions in the usage_instructions.md file for detailed steps on how to train and evaluate the models using the provided datasets and prompts.
Contribution
Contributions to LLM-MethodNamer are welcome. If you have suggestions for improvement or want to report bugs, please open an issue or submit a pull request.
