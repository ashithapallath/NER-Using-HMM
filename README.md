# HMM for Named Entity Recognition (NER)

This repository contains an implementation of a Hidden Markov Model (HMM) for Named Entity Recognition (NER) using Python. The project demonstrates how to train and evaluate an HMM for recognizing named entities in text data, such as names of persons, organizations, and locations. This work is a part of a Computational Linguistics project based on statistical modeling.

## Features
- **Custom Implementation of HMM**: Includes methods for calculating transition and emission probabilities.
- **NER Task**: Focused on tagging entities in a dataset with predefined labels.
- **Evaluation Metrics**: Provides accuracy and other evaluation metrics to assess the model's performance.
- **Modular Code**: Designed to be easily extensible for other sequence tagging tasks.

## Requirements
Ensure you have the following installed:
- Python 3.8+
- Jupyter Notebook
- NumPy
- Pandas
- scikit-learn

Install the dependencies using pip:
```bash
pip install -r requirements.txt
```

## Project Structure
- `HMMModelNER.ipynb`: The main Jupyter Notebook containing the implementation, training, and evaluation of the HMM for NER.
- `data/`: Folder for storing datasets used for training and testing.
- `utils.py`: Utility functions for preprocessing data and calculating probabilities (if applicable).

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/hmm-ner.git
   cd hmm-ner
   ```

2. Open the Jupyter Notebook:
   ```bash
   jupyter notebook HMMModelNER.ipynb
   ```

3. Follow the instructions in the notebook to:
   - Load and preprocess your dataset.
   - Train the HMM.
   - Evaluate its performance.

## Dataset
This project uses the `ai4bharat/naamapadam` dataset for training and evaluating the HMM. You can also use other datasets such as CoNLL 2003 for NER tasks. Ensure the data is formatted appropriately with token-label pairs for training.

## Example
The notebook provides a step-by-step guide, including:
- Loading a dataset.
- Computing transition and emission probabilities.
- Performing inference to tag new sequences.
- Evaluating the results.

## Contributing
Contributions are welcome! Feel free to submit issues or pull requests for enhancements, bug fixes, or additional features.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments
- Inspired by foundational concepts in HMM and its applications to NLP tasks.
- Thanks to the open-source community for providing datasets and tools.



