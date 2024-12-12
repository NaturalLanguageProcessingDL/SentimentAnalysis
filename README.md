# Sentiment Analysis on IMDB Reviews using TorchText and GRU

This project demonstrates how to perform sentiment analysis on IMDB movie reviews using PyTorch, TorchText, and a Gated Recurrent Unit (GRU) based neural network. The goal is to classify movie reviews as either positive or negative.

## Features

- **Dataset Handling**: Uses the IMDB dataset, preprocessed and tokenized with TorchText.
- **Neural Network**: Implements a GRU-based sequence model for binary classification.
- **Training Pipeline**: Includes data batching, loss computation, and optimization.
- **Evaluation Metrics**: Measures model performance using accuracy and loss.
- **Visualization**: Provides insights into model predictions and performance metrics.

## Getting Started

### Prerequisites

Make sure you have the following installed:

- Python 3.7+
- PyTorch 1.10+
- TorchText 0.11+
- Jupyter Notebook
- Other Python dependencies listed in `requirements.txt`

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/NaturalLanguageProcessingDL/SentimentAnalysis
   ```

## Usage

1. Open the notebook `Sentiment_Analysis_IMDB_TorchText_GRU.ipynb` in Jupyter Notebook.
2. Execute the cells sequentially to:
   - Preprocess and load the IMDB dataset.
   - Define and initialize the GRU-based model.
   - Train the model using the training dataset.
   - Evaluate performance on the test dataset.
3. Review visualizations and metrics to interpret the model’s performance.

## Structure of the Notebook

### Key Sections

1. **Setup and Imports**: Installs and imports necessary libraries.
2. **Data Loading and Preprocessing**:
   - Tokenizes and batches the IMDB dataset.
   - Applies padding and vocab indexing.
3. **Model Definition**:
   - Builds a GRU-based binary classifier.
   - Initializes weights and hyperparameters.
4. **Training**:
   - Implements a training loop with loss computation and gradient descent.
   - Tracks accuracy and loss during training.
5. **Evaluation**:
   - Calculates accuracy on the test dataset.
   - Displays confusion matrices and other metrics.
6. **Visualization**:
   - Graphs training and validation losses.
   - Displays sample predictions.

## Example Output

After training for 5 epochs, the model achieves:

- **Accuracy**: ~85% on the test dataset.
- **Loss**: ~0.35 on the test dataset.

Visualizations include loss trends and sample reviews with predicted sentiments.

## Customization

- **Change Hyperparameters**:
  Modify learning rate, batch size, or GRU layers in the hyperparameter section of the notebook.
- **Use a Different Dataset**:
  Replace the IMDB dataset with your own by following the same preprocessing steps.

## Contributing

Contributions are welcome! If you wish to add features or fix bugs, please:

1. Fork the repository.
2. Create a feature branch.
3. Submit a pull request with a detailed description of your changes.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Acknowledgments

- PyTorch and TorchText documentation for their excellent resources.
- The IMDB dataset creators.
- Open-source community for feedback and contributions.

---

For any issues or questions, please create an issue in the repository or contact [ravijbpatel9124@gmail.com].

