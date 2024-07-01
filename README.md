# Concrete Strength Prediction using Neural Networks

This notebook demonstrates building and evaluating neural network models to predict concrete strength based on various features.

## Dataset
The dataset used for this project is the Concrete Compressive Strength Dataset, which can be found [here](https://cocl.us/concrete_data).

## Project Structure

- **Notebook**: `Concrete strength regression.ipynb`
  - Contains Python code for building, training, and evaluating neural networks for concrete strength prediction.
  - Demonstrates different model configurations and evaluations.

- **Dataset**: `concrete_data.csv`
  - The dataset used for training and testing the models.
  - Features include various properties of concrete mixtures.
  - Target variable is the compressive strength of the concrete.

## Steps Covered
1. **Baseline Model**: A simple neural network with one hidden layer.
2. **Normalized Data**: The same model using normalized data.
3. **Increased Epochs**: Training the model for more epochs.
4. **Increased Hidden Layers**: Using a deeper neural network with multiple hidden layers.

## Requirements
- Python 3.x
- Jupyter Notebook
- Libraries: Keras, Pandas, NumPy, Scikit-learn

## Usage
1. Download the dataset from the provided link and place it in the same directory as the notebook.
2. Run the notebook cell by cell to see model training, evaluation, and results.
3. Adjust parameters, such as epochs, layers, and features, for experimentation.

## Notes
- Ensure all dependencies are installed (`pip install -r requirements.txt`).
- The notebook includes markdown cells explaining each step and the rationale behind model configurations.
- Results and insights are summarized at the end of the notebook.
