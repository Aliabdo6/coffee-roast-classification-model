# Coffee Roast Classification Neural Network

## Project Overview

This project implements a neural network using TensorFlow to classify coffee roasts as good or bad based on roasting temperature and duration. The model demonstrates how machine learning can be applied to quality control in coffee production.

## Features

- Data generation for coffee roasting scenarios
- Data preprocessing and normalization
- Neural network model creation and training
- Model evaluation and performance visualization
- Decision boundary visualization

## Requirements

- Python 3.7+
- TensorFlow 2.x
- NumPy
- Matplotlib

## Installation

1. Clone this repository:

   ```
   git clone https://github.com/Aliabdo6/coffee-roast-classification-model.git
   cd coffee-roast-classification-model
   ```

2. Install the required packages:
   ```
   pip install tensorflow numpy matplotlib
   ```

## Usage

Run the Jupyter notebook or Python script to:

1. Generate synthetic coffee roasting data
2. Preprocess and normalize the data
3. Create and train the neural network model
4. Evaluate the model's performance
5. Visualize the results

## Model Architecture

The neural network consists of:

- Input layer: 2 nodes (temperature and duration)
- Hidden layer: 3 nodes with sigmoid activation
- Output layer: 1 node with sigmoid activation

## Results

The model achieves:

- Training Accuracy: 97.37%
- Validation Accuracy: 96.50%

For a detailed performance report, see the `model_performance_report.md` file.

## Future Improvements

- Collect real-world coffee roasting data for training
- Experiment with different model architectures
- Implement feature engineering to potentially improve performance
- Develop a user interface for easy model usage in production environments

## Contributing

Contributions to improve the model or extend its functionality are welcome. Please feel free to submit a pull request or open an issue for discussion.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
